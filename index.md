---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Welcome!

<p class="usa-intro">This site provides an overview of the Dignari digital wallet design system, which is a finalist in the United States Department of Homeland Security (DHS) Science and Technology (S&T) Digital Wallet Challenge.</p>

# Stage 2 submission

Since this website is serving as the main landing page for our final competition submission, we're going to cover our Stage 2 content first. Click [HERE](#competition-background) to learn more about the DHS Challenge and to see our Stage 1 submission.

## Our digital wallet design principles

Our design principles are aligned with the 5 principles outlined as part of the <a href="https://designsystem.digital.gov/design-principles/" target="_blank">U.S. Web Design System (USWDS)</a> and serve as an overarching framework for our digital wallet design system and approach. **Fun fact:** We decided to use the USWDS when we built this GitHub Pages site. Since the challenge requested submissions consistent with the USWDS, we felt publishing our content using these established design standards further demonstrated the value of open standards.

Expand each of the sections below to learn more about our design principles.

<div class="usa-accordion usa-accordion--bordered" aria-multiselectable="true">
      <h2 class="usa-accordion__heading">
        <button class="usa-accordion__button"
          aria-expanded="true"
          aria-controls="m-a1">
          1. Start with real user needs
        </button>
      </h2>
      <div id="m-a1" class="usa-accordion__content">
        <p>Our design system focuses on the end user (Subject/Holder) of the digital wallet rather than Verified Credential (VC) Issuers, Verifiers, or other system roles. We designed the User Interface/User Experience (UI/UX) based on what we believed would be the most intuitive and effective experience for your typical end user.  </p>
        <p>To better define the digital wallet experience, we researched common use cases and evolving industry standards to gain a better understanding for how someone would use the wallet to not only collect and store their credentials but also to easily conduct secure transactions.</p>
        <p>As part of Stage 2 we attended multiple <a href="https://w3c-ccg.github.io/" target="_blank">W3C Credentials Community Group (CCG)</a> meetings in order to understand the context for digital wallets so that we could take these into consideration for our design system. We also solicited feedback directly from the community when we formally presented our Stage 1 submission on 12/01/2020 to the CCG.
        <a href="https://w3c-ccg.github.io/meetings/2020-12-01/" target="_blank">(Meeting minutes from our Presentation to the W3C CCG)</a></p>
        <p>The resulting UI/UX consists of industry best practices and proven components, within a clean and modern design, and places privacy at the forefront of our funcionality.</p>
        <p>The delivery of our design system also goes beyond your standard end user and focuses on practitioners within the digital wallet community. Our goal was to provide resources that would be applicbale to designers as well as developers. To that end, as part of our Stage 2 submission, we are including artifacts such as Sketch and Sass files consistent with other established design systems such as the US Web Design System.</p>
        <p>This design system is intended to be a living resource and serve as a bootstrapping capabilty for the digital wallet community. We believe in using the tools and methods that are common in modern application development and open source concepts were at the forefront of our approach. As a result, our design artifacts are intended to be easily shareable and open for ongoing collaboration.</p>
      </div>
      <!-- Use the accurate heading level to maintain the document outline -->
      <h2 class="usa-accordion__heading">
        <button class="usa-accordion__button"
          aria-expanded="false"
          aria-controls="m-a2">
          2. Earn trust
        </button>
      </h2>
      <div id="m-a2" class="usa-accordion__content">
        <p>Trust is critical for every digital wallet application and requires a design that builds it in from the start. In fact, this is one of the key drivers for the DHS competition—demonstrating and sharing the user experience with the larger community, even while standards and technical aspects are under development, sparks near term interest and enables long term adoption.</p>
        <p>Our design embraces trust as a key tenet and provides a simple to understand experience for the end user. To build trust, people need to understand exactly what the application is doing and how their data is being used. In our design, the user can quickly see which VCs are present in their wallet, organized by domain type (e.g., Education, Identity), and determine their status (e.g., Valid, Expired, Revoked). Each process is easy to follow and provides feedback to the user.</p>
        <p>During transactions our design makes security and privacy apparent by clearly annotating the status of activites, VCs, and other parties throughout the process. Identity verification of all  parties is required and selective disclosure is implemented for uses cases where a subset of attributes are needed to complete a secure transaction.</p>
        <p>As part of Stage 2, we have added attributes from the draft W3C data models directly into the UI/UX. This keeps solutions compliant with evolving standards while also providing users the flexibility to only divulge attributes deemed necessary during the selective disclosure process. This also positions digital wallet application providers with interoperable attributes for data exchange.</p>
        <p>Trust is gained by engaging with the digital wallet community, learning from others, incorporating those changes, and seeking affirmation and clarification when necessary. Trust for end users comes with significant transparency. Our entire design system embraces transparency and seeks to augment the work being done across the community to build trust among users and solution providers.</p>
      </div>
      <!-- Use the accurate heading level to maintain the document outline -->
      <h2 class="usa-accordion__heading">
        <button class="usa-accordion__button"
          aria-expanded="false"
          aria-controls="m-a3">
          3. Embrace accessibility
        </button>
      </h2>
      <div id="m-a3" class="usa-accordion__content">
        <p>Solution success is driven by its accessibility. Our design follows published design standards and is modeled after much of what is presented within international design systems such as the U.S Web Design System.</p>
        <p>Our Stage 2 submission includes designs for web and mobile. Each with a consistent user experience that provides a simple and secure capability for conducting digital wallet transactions. The user interface elements are designed for ease of use and accessibility standards such as Section 508 compliance. We also leverage industry leading, proven, and accessible design stanards such as USWDS as our baseline and build from there.</P>
        <p>Accessibility standards continue to evolve and our design will do so as well. As digital wallet use cases evolve and user experiences are defined, accessibility features will continue to be layered into designs and subsequent digital wallet delivery.</p>
      </div>
      <!-- Use the accurate heading level to maintain the document outline -->
      <h2 class="usa-accordion__heading">
        <button class="usa-accordion__button"
          aria-expanded="false"
          aria-controls="m-a4">
          4. Promote continuity
        </button>
      </h2>
      <div id="m-a4" class="usa-accordion__content">
        <p>Continuity of UI/UX is important, especially for nascent technology such as digital wallets. We embrace continuity of design by applying a similar look and feel and experience across platforms (e.g., mobile, web) and across use cases.</p>
        <p>As part of Stage 2, we further refined our designs to be even more compliant with USWDS standards and best practices. We also tried to limit unnecessary functionality and only focus on key capabilities that would apply to all digital wallet solutions. For example, we represent VCs in the wallet in a consistent manner similar to commerical wallets such as those from Apple and Google. Users expect features to have a look and feel that is consistent with what they already use. We also leverage industry standard QR codes which are familiar to end users.</p> 
        <p>We use simple to understand language and terms within the design of the system and avoid technical jargon specific to those working in the digital wallet solution domain. However, more work will need to be done by the digital wallet community to further define a clear lexicon for users in order to increase adoption and system interoperability.</p>
        <p>Our "package" concept provides a consistent way in which users can combine verifiable credentials into a single submission given a use case's requirements. Common concepts and approaches like this may provide consistent mechanisms moving forward for systems across the digital wallet ecosystem to share credentials.</p>
      </div>
      <!-- Use the accurate heading level to maintain the document outline -->
      <h2 class="usa-accordion__heading">
        <button class="usa-accordion__button"
          aria-expanded="false"
          aria-controls="m-a5">
          5. Listen
        </button>
      </h2>
      <div id="m-a5" class="usa-accordion__content">
        <p>Listening is frequently overlooked in system design. Too often developer assumptions are implemented and end users are left scratching their heads when it comes time to actually use the software. For our design system, we have been listening intently to the digital wallet community throughout the competition. As we are new to this space, listening has served as our greatest asset in developing and delivering our Stage 2 submission.</p>
        <p>Features implemented as part of this submission are directly a result of listening to, and engaging with, the digital wallet community. Here are some of the ways we engaged with the community during Stage 2:</p>
        <ul>
        <li>Participated in the DHS S&T Digital Wallet Challenge Community Event, engaging with DHS, the Department of State, the Department of Education, and the W3C CCG. The <a href="https://sri-csl.regfox.com/digital-wallets-challenge" target="_blank">recording of the community event</a> is available to watch online.</li>
        <li>Attended multiple W3C Credentials Community Group (CCG) meetings to better understand concepts of operations, the context for digital wallet use, and the technical details required to implement the solutions.</li>
        <li>Formally presented our Stage 1 design at the <a href="https://w3c-ccg.github.io/meetings/2020-12-01/" target="_blank">12/1/2020 CCG meeting</a> in an interactive demonstration and disucssion about our proposed design.</li>  
        <li>Participated in the <a href="https://www.federalblockchainnews.com/podcast/episode/79d5c394/digital-identity-wallet-ui-competition" target="_blank">Federal Blockchain News podcast</a> with our competitors to discuss the competition and our design principles.</li>
        </ul>
        <p>Some of these features in our Stage 2 submission, which were a direct result of listening to the community, in addition to our continued research, include:</p>
        <ul>
        <li>Implementation and clarity of VC lifecycle status (e.g., Revoked, Expired).</li>
        <li>Inclusion of official data model attributes during the selective disclosure process.</li>
        <li>Feature three</li>
        </ul>
        </div>
</div>

## For Designers

<img src="{{site.baseurl}}/assets/img/sketch-logo.png" width="20%"/>

At the heart of our design system is our Sketch file. Sketch is an industry leading digital design toolkit for UI/UX that we use regularly in our Human-Centered Design practice here at Dignari.

Designers interested in using our Sketch file to start their own design process may find it in our <a href="https://github.com/Dignari/digital-wallet-ds" target="_blank">digital-wallet-ds</a> repo

## For Developers

<img src="{{site.baseurl}}/assets/img/sass-logo.png" width="15%"/>

For developers, we have included a number of <a href="https://sass-lang.com/" target="_blank">Sass</a> files in our <a href="https://github.com/Dignari/digital-wallet-ds" target="_blank">GitHub repo</a> to be used for bootstrapping your projects. These Sass files are intended to be implemented into your project similar to how USWDS design tokens and Sass files are used. These are a work in progress and trail behind development of the UI/UX designer files (Sketch).

---

# Competition Background

In September 2020, DHS S&T launched the <a href="https://www.dhs.gov/science-and-technology/news/2020/09/08/news-release-st-new-prize-competition-user-interface-digital" target="_blank">Trusted User Interface (UI) Digital Wallet Challenge</a> to call "...on innovators to design an easy-to-use and trustworthy UI that improves the overall user experience (UX) and management of digital wallet-based credentials."

The Challenge was divided into two distinct stages of competition. Stage 1 solicited concepts and ideas from the public and requested a video submission addressing a particular use case. The video was to provide an overview of your design approach as well as a demonstration of how a person would use your digital wallet app to apply for a job. Three finalists were selected from Stage 1 to move on to Stage 2. In Stage 2, finalists build on their Stage 1 concepts, engage further with the community, and deliver a final design system for judging.

<a href="https://www.dignari.com" target="_blank">Dignari</a> responded to the challenge by combining solution architects from their <a href="https://www.dignari.com/emerging-technology" target="_blank">Emerging Technology</a> team and designers from their <a href="https://www.dignari.com/human-centered-design" target="_blank">Human-Centered Design</a> team. This combination turned out to be a great mix as Dignari was <a href="https://www.dhs.gov/science-and-technology/prize-competitions" target="_blank">selected as one of the 3 finalists</a> to move onto Stage 2.

# Stage 1

In Stage 1 we were mostly concerned with immersing ourselves in the digital wallet ecosystem to better understand the state of digital wallet technology, the respective uses cases, and common workflows. While Dignari has an extensive history of identity management solution delivery, we were relatively new to the digital wallet space.

We started by conducted significant research of existing communities of interest such as the W3C CCG and examined solutions within the market. At the same time, our UI/UX designers leveraged their experience developing modern experiences for our clients to re-imagine what a digital wallet app may look like. It was important to us to understand the process as defined for Stage 1 and then apply best practices.

Our Stage 1 video submission included Jane Doe who was applying for a job. In order to submit her application, she needed to provide a number of credentials. In particular, Jane needed to:

1. Get a Verifiable Credential (VC) of her college degree from her university
2. Get a VC of her Permanent Resident Card from the US Citizenhip and Immigration Services (USCIS)
3. Submit both credentials to the employer

As you can see in the video below, we provided a comprehensive solution for both web and mobile, using modern design elements and technically sound workflows.

## Our Stage 1 submission

<div class="video-container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/6DmcdsEdgZM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

This website serves as our main landing page for the judging panel for Stage 2. For more information on our final submission, jump back to the top of the page and read about Stage 2.
