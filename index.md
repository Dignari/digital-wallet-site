---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

  <section class="usa-hero margin-top-1" aria-label="Introduction">
  <div class="grid-container">
    <div class="usa-hero__callout">
      <h1 class="usa-hero__heading"><span class="usa-hero__heading--alt">Welcome!</span>
      </h1><p>This site provides an overview of the Dignari Digital Wallet Design System, which is a finalist in the United States Department of Homeland Security (DHS) Science and Technology (S&T) Digital Wallet Challenge.</p>
    </div>
  </div>
</section>

# Stage 2 submission

Since this website is serving as the main landing page for our final competition submission, we're going to cover our Stage 2 content first. Click [HERE](#competition-background) to learn more about the DHS Challenge and to see our Stage 1 submission.

## We've been busy

We were so energized after the Stage 1 Community Event that we got to work right away on our Stage 2 submission. Here is a brief recap of some of the things we've done in Stage 2 to further our design and to accomodate feedback from the community.

<div class="grid-row grid-gap margin-top-5 margin-bottom-7">
  <div class="tablet:grid-col-6">
      <h4 class="margin-0">Actions taken after Stage 1</h4>
      <ul class="usa-list">
        <li>Consolidated feedback from Community Event and applied it to our design</li>
        <li>Gathered additional information on the W3C Credential Community Group (CCG) and associated groups (e.g., DIF)</li>
        <li>Compiled additional reseearch, revisited the DHS use case, and reviewed our design to identify gaps and opportunities</li>
        <li>Arranged to present our design at the CCG weekly meeting on 12/1/2020</li>
        <li>Presented our designs and a demo at the 12/1/2020 CCG weekly meeting with an interactive presentation, incorporating feedback from the Stage 1 Community Event and previous CCG meetings, in order to solicit feedback</li>
        <li>After the meeting we provided the CCG with a copy of the designs, with focus area callouts, and a link to our Stage 1 video submission</li>
        <li>Applied CCG feedback to our final design and added enhancements based on our independent research (e.g., lifecycle status)</li>
        <li>Performed a deep dive analysis of the Verifiable Credentials Data Model 1.0 to incorporate accurate data model attributes in our final design</li>
        <li>Explored similar delivery models that follow open source best practices for design systems in order to ensure consistency and interoperability. This included reviewing the <a href="https://designsystem.digital.gov/" target="_blank">U.S. Web Design System</a> as well as international systems such as the <a href="https://designsystem.gov.au/" target="_blank">Australian Government Design System</a></li>
        <li>Established public GitHub repository to host our final design system as well as this website</li>
        <li>Built this Jekyll website, hosted on GitHub Pages, to serve as our main landing page for our final submission and for transparent community engagement</li>
      </ul>
  </div>
  <div class="tablet:grid-col-6">
      <h4 class="margin-0">UI/UX changes made after Stage 1</h4>
      <ul class="usa-list">
        <li>Updated font sizes and data entry elements to follow USWDS</li>
        <li>Expanded account creation workflow and inclusion of EULA acceptance</li>
        <li>Removed statuses from identity domains. It was ambiguous and could not accurately show status if multiple documents were under a particular domain</li>
        <li>Implemented Data First concepts for credential views to the holder; show data elements and have image strictly as representative</li>
        <li>Added acceptance requirement when receiving credential from issuers; holder has opportunity to review credential data and by accepting the credential, the holder is confirming that the data is correct</li>
        <li>Added notifications for particular actions (e.g., when adding credentials to wallets the statuses change on documents)</li>
        <li>Changed the Package creation view. Showing the QR code was not intuitive to the holder. Now we show a list of documents when the Package is created. When the holder clicks Share, the holder is prompted for consent to release information after which the QR Code is presented</li>
        <li>Clarified online job application workflow. Holder would scan QR code to Send Job Application Package. Upon clicking Send, the holder is asked for consent to release information. Package is sent when consent is provided</li>
        <li>Added ability to edit document lists inside domains to allow users to delete multiple documents (e.g., delete driver's license and PRC from Legal Identity domain)</li>
        <li>Added statuses to credentials (e.g., Revoked or Expired showing on the document tabs) and notifications accompany highlighting of documents and printed statuses</li>
      </ul>
  </div>
</div>

<div>
  <img src="{{site.baseurl}}/assets/img/dw-marketing-mobile.png" class="center margin-bottom-7" width="75%">
</div>

## Our digital wallet design principles

Our design principles are aligned with the 5 principles outlined as part of the <a href="https://designsystem.digital.gov/design-principles/" target="_blank">U.S. Web Design System (USWDS)</a> and serve as an overarching framework for our digital wallet design system and approach. **Fun fact:** We decided to use the USWDS when we built this GitHub Pages site. Publishing our content using these established design standards further demonstrates the value of open standards.

Expand each of the sections below to learn more about our design principles.

<div class="usa-accordion usa-accordion--bordered margin-bottom-7" aria-multiselectable="true">
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
        <p>The resulting UI/UX consists of industry best practices and proven components, within a clean and modern design, and places privacy at the forefront of our functionality.</p>
        <p>The delivery of our design system also goes beyond your standard end user and focuses on practitioners within the digital wallet community. Our goal was to provide resources that would be applicable to designers as well as developers. To that end, as part of our Stage 2 submission, we are including artifacts such as Sketch and Sass files consistent with other established design systems such as the US Web Design System.</p>
        <p>This design system is intended to be a living resource and serve as a bootstrapping capability for the digital wallet community. We believe in using the tools and methods that are common in modern application development and open source concepts were at the forefront of our approach. As a result, our design artifacts are intended to be easily shareable and open for ongoing collaboration.</p>
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
        <p>Trust is critical for every digital wallet application and a cohesive design is key in earning the end user's trust. In fact, this is one of the key drivers for the DHS competition—demonstrating and sharing the user experience with the larger community, even while standards and technical aspects are under development, sparks near term interest and enables long term adoption.</p>
        <p>Our design embraces trust as a key tenet and provides a simple to understand experience for the end user. To build trust, people need to understand exactly what the application is doing and how their data is being used. In our design, the user can quickly see which VCs are present in their wallet, organized by domain type (e.g., Education, Identity), and determine their status (e.g., Valid, Expired, Revoked). Each process is easy to follow and provides feedback to the user.</p>
        <p>During transactions our design makes security and privacy apparent by clearly annotating the status of activities, VCs, and other parties throughout the process. Identity verification of all  parties is required and selective disclosure is implemented for uses cases where a subset of attributes are needed to complete a secure transaction.</p>
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
        <p>Our Stage 2 submission includes designs for web and mobile. Each with a consistent user experience that provides a simple and secure capability for conducting digital wallet transactions. The user interface elements are designed for ease of use and accessibility standards such as Section 508 compliance. We also leverage industry leading, proven, and accessible design standards such as USWDS as our baseline and build from there.</P>
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
        <p>As part of Stage 2, we further refined our designs to be even more compliant with USWDS standards and best practices. We also tried to limit unnecessary functionality and only focus on key capabilities that would apply to all digital wallet solutions. For example, we represent VCs in the wallet in a consistent manner similar to commercial wallets such as those from Apple and Google. Users expect features to have a look and feel that is consistent with what they already use. We also leverage industry standard QR codes which are familiar to end users.</p> 
        <p>We use easily comprehensible language and terms within the design of the system and avoid technical jargon specific to those working in the digital wallet solution domain. However, more work will need to be done by the digital wallet community to further define a clear lexicon for users in order to increase adoption and system interoperability.</p>
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
        <p>Features implemented as part of this submission are a direct result of listening to, and engaging with, the digital wallet community. Here are some of the ways we engaged with the community during Stage 2:</p>
        <ul>
        <li>Participated in the DHS S&T Digital Wallet Challenge Community Event, engaging with DHS, the Department of State, the Department of Education, and the W3C CCG. The <a href="https://sri-csl.regfox.com/digital-wallets-challenge" target="_blank">recording of the community event</a> is available to watch online.</li>
        <li>Attended multiple W3C Credentials Community Group (CCG) meetings to better understand concepts of operations, the context for digital wallet use, and the technical details required to implement the solutions.</li>
        <li>Formally presented our Stage 1 design at the <a href="https://w3c-ccg.github.io/meetings/2020-12-01/" target="_blank">12/1/2020 CCG meeting</a> in an interactive demonstration and discussion about our proposed design.</li>  
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

## Resources and design artifacts

Our approach throughout the competition was to look at solutions that worked for both designers and developers. Even though the focus of this competition was on the UI/UX component, we wanted to make sure that our artifacts aligned with expectations of the development community and that, even if it wasn't a complete design system at the time of judging, the framework was in position to assist developers in the future.

<ul class="usa-card-group margin-bottom-7">
  <li class="tablet:grid-col-4 usa-card usa-card--header-first">
    <div class="usa-card__container">
      <header class="usa-card__header">
        <h2 class="usa-card__heading">For designers</h2>
      </header>
      <div class="usa-card__body">
        <img src="{{site.baseurl}}/assets/img/sketch-card-logo.png" >
        <p>At the heart of our design system is our Sketch file. Sketch is an industry leading digital design toolkit for UI/UX that we use regularly in our Human-Centered Design practice here at Dignari.</p>
        <p> Designers interested in using our Sketch file to start their own design process may find it in our GitHub repo.</p>
      </div>
      <div class="usa-card__footer">
        <a class="usa-button" href="https://github.com/Dignari/digital-wallet-ds" target="_blank">Visit Designer Repo</a>
      </div>
    </div>
  </li>
  <li class="tablet:grid-col-4 usa-card usa-card--header-first">
    <div class="usa-card__container">
      <header class="usa-card__header">
        <h2 class="usa-card__heading">For developers</h2>
      </header>
      <div class="usa-card__body">
        <img src="{{site.baseurl}}/assets/img/sass-card-logo.png" >
        <p>For developers, we have included a number of <a href="https://sass-lang.com/" target="_blank">Sass</a> files in our GitHub repo to be used for bootstrapping your projects. These files are intended to be implemented into your project similar to the USWDS.</p><p> These are a work in progress and trail behind development of the UI/UX designer files (Sketch).</p>
      </div>
      <div class="usa-card__footer">
        <a class="usa-button" href="https://github.com/Dignari/digital-wallet-ds" target="_blank">Visit Developer Repo</a>
      </div>
    </div>
  </li>
  <li class="tablet:grid-col-4 usa-card usa-card--header-first">
    <div class="usa-card__container">
      <header class="usa-card__header">
        <h2 class="usa-card__heading">For everyone</h2>
      </header>
      <div class="usa-card__body">
        <img src="{{site.baseurl}}/assets/img/zeplin-card-logo.png" >
        <p>We have also stood up a public Zeplin site where the entire design may be viewed by any interested stakeholders.</p><p> This makes it easy for anyone to take a look at the full collection of screens to hopefully spur thoughts and design considerations for their own digital wallet designs.</p>
      </div>
      <div class="usa-card__footer">
        <a class="usa-button" href="https://scene.zeplin.io/project/5fb41a91183b2377bdd3f4d0" target="_blank">Visit Zeplin Site</a>
      </div>
    </div>
  </li>
</ul>

<div>
  <img src="{{site.baseurl}}/assets/img/dw-marketing-ui.png" class="center">
</div>

# Competition Background

In September 2020, DHS S&T launched the <a href="https://www.dhs.gov/science-and-technology/news/2020/09/08/news-release-st-new-prize-competition-user-interface-digital" target="_blank">Trusted User Interface (UI) Digital Wallet Challenge</a> to call "...on innovators to design an easy-to-use and trustworthy UI that improves the overall user experience (UX) and management of digital wallet-based credentials."

The Challenge was divided into two distinct stages of competition. Stage 1 solicited concepts and ideas from the public and requested a video submission addressing a particular use case. The video was to provide an overview of your design approach as well as a demonstration of how a person would use your digital wallet app to apply for a job. Three finalists were selected from Stage 1 to move on to Stage 2. In Stage 2, finalists build on their Stage 1 concepts, engage further with the community, and deliver a final design system for judging.

<a href="https://www.dignari.com" target="_blank">Dignari</a> responded to the challenge by combining solution architects from their <a href="https://www.dignari.com/emerging-technology" target="_blank">Emerging Technology</a> team and designers from their <a href="https://www.dignari.com/human-centered-design" target="_blank">Human-Centered Design</a> team. This combination turned out to be a great mix as Dignari was <a href="https://www.dhs.gov/science-and-technology/prize-competitions" target="_blank">selected as one of the 3 finalists</a> to move onto Stage 2.

# Stage 1

In Stage 1 we were mostly concerned with immersing ourselves in the digital wallet ecosystem to better understand the state of digital wallet technology, the respective uses cases, and common workflows. While Dignari has an extensive history of identity management solution delivery, we were relatively new to the digital wallet space.

We started by conducted significant research of existing communities of interest such as the W3C CCG and examined solutions within the market. At the same time, our UI/UX designers leveraged their experience developing modern experiences for our clients to re-imagine what a digital wallet app may look like. It was important to us to understand the process as defined for Stage 1 and then apply best practices.

Our Stage 1 video submission included Jane Doe who was applying for a job. In order to submit her application, she needed to provide a number of credentials. In particular, Jane needed to:

1. Get a Verifiable Credential (VC) of her college degree from her university
2. Get a VC of her Permanent Resident Card from the US Citizenship and Immigration Services (USCIS)
3. Submit both credentials to the employer

As you can see in the video below, we provided a comprehensive solution for both web and mobile, using modern design elements and technically sound workflows.

## Our Stage 1 submission

<div class="video-container">
<iframe class="responsive-iframe" src="https://www.youtube.com/embed/6DmcdsEdgZM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

This website serves as our main landing page for the judging panel for Stage 2. For more information on our final submission, jump back to the top of the page and read about Stage 2.
