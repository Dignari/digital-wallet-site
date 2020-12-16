# Dignari Digital Wallet Design System Site

This repo includes code and documentation for the website that serves as the information hub for the [Dignari](https://www.dignari.com) Digital Wallet Design System.

It also serves as our landing page for our Stage 2 (Final) submission as part of the [Department of Homeland Security (DHS) Trusted User Interface (UI) for Digital Wallets Challenge](https://www.dhs.gov/science-and-technology/prize-competitions). You can find the design system artifacts located in our [digital-wallet-ds repo](https://github.com/Dignari/digital-wallet-ds).

This website is built with Jekyll and is hosted via GitHub Pages. The site also incorporates the [U.S. Web Design System (USWDS)](https://designsystem.digital.gov/) in order to be consistent with best practices and to show the value of open design standards.

## To access the production site

The GitHub pages URL for the site is [dignari.github.io/digital-wallet-site/](https://dignari.github.io/digital-wallet-site/). This is the default URL scheme used by GitHub pages. Since we are nice, and in order to make it a bit easier for our end users we implemented a redirect to the site so you can access it by simply browsing to [dignari.com/digitalwallet](https://www.dignari.com/digitalwallet).

## To run the code

In order to run the application locally you'll want to switch to your local copy of the repository and run:

`bundle exec jekyll serve --baseurl '' --livereload`

Bundler is installed and used to serve the site and there are a couple of flags listed that you'll want to use.

The `--baseurl` flag is needed as GitHub Pages is a bit tricky when building and serving your website and differs from what is needed locally. The website URL when served on GitHub Pages is `orgranization.github.io/project-name` where `organization` is your GitHub org and `project-name` is the particular repo.

However, when running locally, you don't have the `project-name` appended to the URL and this can cause problems. The best way to address this is by setting `baseurl` in your `_config.yml` file to reflect the project name with a leading `\` but no ending `\`. So, it would be:

`baseurl: "/digital-wallet-site"`

The `--livereload` is exactly what you'd think it was. It provides the ability for hot reload of changes made in your project during development. **NOTE:** If you change something in the `_config.yml` you'll need to close down the running instance and relaunch using the `bundle exec...` command from above.

## Project structure

Here are a few notes regarding the structure of the project.

### Theme

This is a basic Jekyll site that uses the `minima` theme that ships with Jekyll. We moved away from using the default gem-based minima theme and instead migrated to a regular theme, seeded with the minima files.

### USWDS

As mentioned earlier, the site uses the USWDS. In order to use the USWDS _and_ to host on GitHub Pages, we found it easier to include the USWDS directly in the project itself. Using the `npm` package for USWDS standard worked fine for our initial development but we decided given GitHub Pages capabilities it was best to just use the code directly. . At least this is easier and the path we took given the short timeframe to launch the site.

When using the USWDS we also use `gulp` for compiling the sass files into css. Again, we leveraged the USWDS for our gulp process which can be found by following the directions [in their uswds-gulp repo](https://github.com/uswds/uswds-gulp).

This is a single page app and leverages the [Documentation Page template](https://designsystem.digital.gov/page-templates/) from the USWDS. We started with the template and made changes for our particular needs. `index.md` in the project root is the main content file and it uses `home.html` and `default.html` for layout.

### A work in progress

The intent of this website was to quickly stand up a site to share some basic information about our digital wallet design system and serve as the landing page for our final submission in the competition. The site will remain a work in progress and will be updated over time.
