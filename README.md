[![Docsify](https://img.shields.io/npm/v/docsify?label=docsify)](https://docsify.js.org/)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/hibbitts-design/docsify-open-multicourse-starter-kit/blob/main/LICENSE)
<a href="https://discord.gg/docsify">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289DA.svg" alt="Docsify Discord Chat" />
</a>

## Instantly Turn Online Markdown Files into Web Pages

This open-source web app, built with the magical documentation site generator [Docsify](https://docsify.js.org), provides a quick way to publish one or more online [Markdown](https://en.wikipedia.org/wiki/Markdown) files as standalone web pages without needing to set up your own website.  

![ Docsify-This](https://raw.githubusercontent.com/paulhibbitts/github-repo-images/master/docsify-this-web-page-builder.png)
_Figure 1. [Docsify-This.net](https://docsify-this.net) Web Page Builder._

## All About Docsify-This

* [What Problem Does Docsify-This Solve?](#what-problem-does-docsify-this-solve)
* [Docsify-This Core Design Principles](#docsify-this-core-design-principles)
* [How Docsify-This Works](#how-docsify-this-works)
* [Read What People are Saying about Docsify-This](#read-what-people-are-saying-about-docsify-this)
* [Example Content Workflows](#example-content-workflows)
* [Ready-to-Use Docsify-This Markdown Templates](#ready-to-use-docsify-this-markdown-templates)
* [Additional Docsify-This Markdown Examples and Templates](#additional-docsify-this-markdown-examples-and-templates)
* [Page Appearance URL Parameters](#page-appearance-url-parameters)
* [Embedding Docsify-This Pages into Other Platforms](#embedding-docsify-this-pages-into-other-platforms)
* [Markdown Syntax References](#markdown-syntax-references)
* [Font Awesome Icons](#font-awesome-icons)
* [Supported Markdown CSS Classes](#supported-markdown-css-classes)
* [Custom Markdown CSS Classes](#custom-markdown-css-classes)
* [Tips and Techniques](#tips-and-techniques)
* [Editing Docsify-This Markdown Files on your Desktop](#editing-docsify-this-markdown-files-on-your-desktop)
* [Improving Markdown Previews in Text Editors](#improving-markdown-previews-in-text-editors)
* [Looking for Even More Customization and Control?](#looking-for-even-more-customization-and-control)
* [Additional Docsify-This Learning Materials](#additional-docsify-this-learning-materials)
* [Troubleshooting](#troubleshooting)
* [Privacy Policy Summary](#privacy-policy-summary)
* [Contact and Support](#contact-and-support)

Have you tried out Docsify-This? Share your [feedback about Docsify-This](https://forms.gle/ViYu2ZdPmj6PeQ439)

---

### What Problem Does Docsify-This Solve?

Docsify-This provides an easy way to display and share [Markdown](https://www.markdownguide.org/basic-syntax/) content in various contexts, with no website setup or build process required. Collaborative authoring using GitHub or Codeberg is also supported.  

With Docsify-This you can:

* Publish your Markdown files as standalone web pages, with no website setup or build process required
* Visually style your standalone web pages using a point-and-click Web Page Builder
* Share existing GitHub-hosted Markdown files as standalone web pages, with an optional 'Edit this Page' link
* Seamlessly embed constraint-free Markdown/HTML, which you have authored, into other platforms (e.g. LMS or CMS)
* Reuse existing Markdown content by seamlessly embedding it within other platforms (e.g. LMS or CMS)
* Utilize the supported URL parameters when embedding content to match each destination platform better visually

---

### Docsify-This Core Design Principles

* Frictionless Markdown publishing
* Flexible content display handling
* Your content, your control
* Support the 5 Rs of OER
* Authors helping other authors

---

### How Docsify-This Works

Docsify-This is a customized [Docsify Open Publishing Starter Kit](https://github.com/hibbitts-design/docsify-open-publishing-starter-kit) site configured to render remote Markdown files via URL parameters in the following format:

`https://docsify-this.net?basePath=URLpath&homepage=filename.md`

The **basePath** Docsify parameter is the URL path containing the raw source Markdown file to render. If the file is named the expected default **README.md** then no other parameter are required, otherwise the **homepage** Docsify parameter must also be included set to the name of the file to render. An example Docsify-This URL would be:
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md  

To render a file stored in a public GitHub repository you need to use the raw source URL of that file (i.e. raw.githubusercontent.com) - tap the **Raw** button when [viewing a file](https://docs.github.com/en/repositories/working-with-files/using-files/viewing-a-file) to get this URL when not using the above Web Page Builder, which does this automatically. It is also possible to render a file stored in a private GitHub repository by activating GitHub Pages within that repository and then using the GitHub Pages URL of that file (i.e. username.github.io).  

The appearance of rendered Markdown files can be customized by optional [URL parameters](/?id=page-appearance-url-parameters) and a small set of available [CSS Classes](/?id=supported-markdown-css-classes) within source Markdown files. In addition to supporting standard Markdown, [Embed.ly](https://embed.ly/code), [H5P](https://h5p.org/), [Katex](https://github.com/upupming/docsify-katex), [Mermaid Diagrams](https://github.com/Leward/mermaid-docsify) and [RunKit](https://runkit.com/) are included. Optionally, page annotation with [Hypothes.is](https://hypothes.is) can be enabled.  

Looking for an overall introduction to publishing with Docsify-This? Check out [Markdown Publishing with Docsify-This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main&sidebar=true&edit-link=https://github.com/hibbitts-design/publishing-with-docsify-this/blob/main/README.md&maxLevel=4&title=Markdown%20Publishing%20with%20Docsify-This).

---

### Read What People are Saying about Docsify-This

> I’m blown away just by the fact you put a (Markdown file) URL into Docsify-This and then you get a URL back for a web page… done! Take the URL and go. It is so seamless.  
— J. Groom, [Reclaim Today Episode 39](https://today.reclaimhosting.com/podcast/039-docsify-this-with-paul-hibbitts/) (Co-founder, Reclaim Hosting)

> I've been using Docsify-This for my graduate publishing production course, partly to explore new models in markdown publishing, but partly also to tame Canvas, which I find awkward and cumbersome. Keeping all my course notes as plain text files and deploying them through Github and Docsify-this is easy and makes my course development a breeze. Plus, I keep all my materials locally, and can use re-use them without being reliant on Canvas.  
— J. Maxwell (Director & Associate Professor in the Publishing Program at Simon Fraser University)

> Best tool I’ve found in years - this is one of those creations that is just done right, all the way to the core.  
— D. Malawey (Multidisciplinary Lab Coordinator, Texas A&M University, United States)

> Docsify-This has significantly improved my WordPress themes by being able to seamlessly embed into the interface the same documentation I use in the GitHub repository. This in turn has lead me to write better docs! I've barely scratched the surface of what Docsify-This can do as a simple-to-use web publishing tool.  
— A. Levine aka CogDog (Independent Educational Technologist)

---

### Example Content Workflows

<div class="row">
<div class="column">

![Docsify-This.net open and collaborative workflow using GitHub Markdown files](docs/images/docsify-this-gitHub.jpg ':class=image-border-rounded')  
_Docsify-This.net open and collaborative workflow using GitHub Markdown files._

</div>
<div class="column">

![Docsify-This.net workflow using Webserver Markdown files](docs/images/docsify-this-webserver.jpg ':class=image-border-rounded')
_Docsify-This.net workflow using Webserver Markdown files._

</div>
</div>

---

### Ready-to-Use Docsify-This Markdown Templates

While all you need to get going with Docsify-This is a basic Markdown file, below are some templates you can use that show what is possible with Markdown, images, and even a few HTML snippets!

To use these templates you would generally do the following (template specific instructions are included with each template):

1. Tap **Use this template** in the chosen template repository (upper-right green button) and then choose **Create a new repository**

2. Choose the name for your new repository to contain the files and then tap **Create repository** to copy the template files to your own GitHub account

3. View the **home.md** Markdown file in your newly created repository and copy it's URL

4. Go to https://docsify-this.net and paste the copied URL into the **Markdown File URL** field

5. Select the page options you want (e.g. Docsify Sidebar) and tap the **Publish as a Standalone Web Page** button to view your Markdown file as a web page for sharing or embedding  

Now that the template files are located on your own GitHub account, modify their content to fit your needs.  

#### [Docsify-This One Page Article Template](https://github.com/hibbitts-design/docsify-this-one-page-article)

![Docsify-This One Page Article Template](docs/images/docsify-this-one-page-article-readme.png)

One Page Article [home.md](https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md) file displayed by Docsify-This as a:  
* [Standalone Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md "Single Page Docsify Open Course Starter Kit - Standalone Page")  
* [Standalone Page with Table of Contents including h2 and h3 Headers and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&toc=true&toc-headings=h2,h3&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md "Single Page Docsify Open Course Starter Kit - Standalone Page with Table of Contents")  
* [Standalone Page with Docsify Sidebar with maxLevel of 3 (H3) and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true&maxLevel=3&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md "Single Page Docsify Open Course Starter Kit - Standalone Page with Docsify Sidebar")

#### [Docsify-This One Page Course Template](https://github.com/hibbitts-design/docsify-this-one-page-course)

![Docsify-This One Page Course Template](docs/images/docsify-this-one-page-course-readme.png)

One Page Course [home.md](https://github.com/hibbitts-design/docsify-this-one-page-course/blob/main/home.md) file displayed by Docsify-This as a:   
* [Standalone Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-course/main&homepage=home.md "Single Page Docsify Open Course Starter Kit - Standalone Page")  
* [Standalone Page with Table of Contents and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-course/main&homepage=home.md&toc=true&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-course/blob/main/home.md "Single Page Docsify Open Course Starter Kit - Standalone Page with Table of Contents")  
* [Standalone Page with Docsify Sidebar and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-course/main&homepage=home.md&sidebar=true&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-course/blob/main/home.md "Single Page Docsify Open Course Starter Kit - Standalone Page with Docsify Sidebar")

#### [Docsify-This Multiple Page Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-site)

![Docsify-This Multiple Page Site](docs/images/docsify-this-multiple-page-site-readme.png)

Multiple Page Site [home.md](https://github.com/hibbitts-design/docsify-this-multiple-page-site/blob/main/home.md) file, including the use of the Markdown CSS class `header-image-full-width`, displayed by Docsify-This as:  
* [Standalone Pages](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md "Docsify-This Multiple Page Site - Standalone Pages")
* [Standalone Pages using the Merriweather font](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&font-family=Merriweather,Georgia,serif "Docsify-This Multiple Page Site - Standalone Pages using the Merriweather font")
* [Standalone Pages using the Merriweather font and red links](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&font-family=Merriweather,Georgia,serif&link-color=CC0000 "Docsify-This Multiple Page Site - Standalone Pages using the Merriweather font and red links")
* [Standalone Pages and 'Edit this Page' links](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-site/blob/main/home.md "Docsify-This Multiple Page Site - Standalone Pages with 'Edit this Page' link")
* [Standalone Pages and 'Edit this Page' links using the Merriweather font](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-site/blob/main/home.md&font-family=Merriweather,Georgia,serif "Docsify-This Multiple Page Site - Standalone Pages with 'Edit this Page' link using the Merriweather font")
* [Standalone Pages with Docsify Navbar](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&loadNavbar=_navbar "Docsify-This Multiple Page Site - Standalone Pages with Docsify Navbar and an 'Edit this Page' link")
* [Standalone Pages with Footer and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&loadFooter=_footer&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-site/blob/main/home.md "Docsify-This Multiple Page Site - Standalone Pages with Footer and an 'Edit this Page' link")
* [Standalone Pages with Docsify Navbar and 'GitHub Repository' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&loadNavbar=_navbar&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-site&edit-link-text=GitHub%20Repository "Docsify-This Multiple Page Site - Standalone Pages with Docsify Navbar and an 'GitHub Repository' link")

#### [Docsify-This Multiple Page Course Site Template](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site)

![Docsify-This Course Site Template](docs/images/docsify-this-multiple-page-course-site-readme.png ':class=docsify-this-screenshot')

Multiple Page Course Site [home.md](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main/home.md) file, including the use of a Docsify custom [Sidebar](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main/_sidebar.md) file and Docsify custom [Navbar](https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main/_navbar.md) file, displayed by Docsify-This as:  
* [Standalone Site](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&hide-credits=true&browser-tab-title=CPT-363 "Docsify-This Multiple Page Course Site - Standalone Site")  
* [Standalone Site with custom Favicon](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadFavicon=favicon.png&hide-credits=true&browser-tab-title=CPT-363 "Docsify-This Multiple Page Course Site - Standalone Site")  
* [Standalone Site with Website logo](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&loadFavicon=favicon.png&hide-credits=true&browser-tab-title=CPT-363&logo=images/logo.png "Docsify-This Multiple Page Course Site - Standalone Site with Website logo")  
* [Standalone Site with Search](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&hide-credits=true&browser-tab-title=CPT-363&search=true  "Docsify-This Multiple Page Course Site - Standalone Site with Search")  
* [Standalone Site with Pagination buttons](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&hide-credits=true&browser-tab-title=CPT-363&pagination=true "Docsify-This Multiple Page Course Site - Standalone Site with Pagination buttons")  
* [Standalone Site with a 'Propose an Edit to this Site' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main&edit-link-text=Propose%20an%20Edit%20to%20this%20Site&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&hide-credits=true&browser-tab-title=CPT-363 "Docsify-This Multiple Page Course Site - Standalone Site with a 'Propose an Edit to this Site' link")
* [Standalone Site with Footer and a 'Propose an Edit to this Site' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main&edit-link-text=Propose%20an%20Edit%20to%20this%20Site&sidebar=true&loadSidebar=_sidebar.md&name=CPT-363&loadNavbar=_navbar.md&hide-credits=true&loadFooter=_footer.md&browser-tab-title=CPT-363 "Docsify-This Multiple Page Course Site - Standalone Site with Footer and a 'Propose an Edit to this Site' link")

#### [Docsify-This LMS Content Pages Template](https://github.com/hibbitts-design/docsify-this-lms-content-pages)

![Docsify-This LMS Content Pages Template](docs/images/docsify-this-lms-content-pages-readme.png)

Example pages, including the use of the `font-family`, `font-size` and `hide-credits` URL parameters for seamless content embedding within the Canvas LMS, as displayed by Docsify-This:  
* [Embeddable Home Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=home.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Home Page")
* [Embeddable Weekly Module Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=module-01.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Weekly Module Page")
* [Embeddable Schedule Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=schedule.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Schedule Page")
* [Embeddable Topics Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=topics.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Topics Page")
* [Embeddable Resources Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=resources.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Resource Page")
* [Embeddable UX Techniques Guide Page (using Accordion format)](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=ux-techniques-guide.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable UX Techniques Guide Page (using Accordion format)")
* [Embeddable Contact Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-lms-content-pages/main&homepage=contact.md&font-family=Lato%20Extended,%20Lato,Helvetica%20Neue,%20Helvetica,%20Arial,%20sans-serif&amp;font-size=1&amp;hide-credits=true "Embeddable Contact Page")

View an example Canvas LMS site using Docsify-This content at https://canvas.sfu.ca/courses/76692.

---

### Additional Docsify-This Markdown Examples and Templates

#### Examples

[GitHub Training Manual Working Locally with Git Markdown file](https://github.com/githubtraining/training-manual/blob/main/docs/06_working_locally.md), displayed by Docsify-This as a:  
* [Standalone Page](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/githubtraining/training-manual/main/docs&homepage=06_working_locally.md "GitHub Training Manual Working Locally with Git - Standalone Page")  
* [Standalone Page with Table of Contents](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/githubtraining/training-manual/main/docs&homepage=06_working_locally.md&toc=true&toc-headings=h2,h3 "GitHub Training Manual Working Locally with Git - Standalone Page with Table of Contents")
* [Standalone Page with Docsify Sidebar](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/githubtraining/training-manual/main/docs&homepage=06_working_locally.md&sidebar=true&maxLevel=3 "GitHub Training Manual Working Locally with Git - Standalone Page with Docsify Sidebar")

[Easy Markdown to Github Pages linked set of Markdown files](https://github.com/nicolas-van/easy-markdown-to-github-pages), displayed by Docsify-This as:   
* [Standalone Pages](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/nicolas-van/easy-markdown-to-github-pages/master&homepage=README.md "Easy Markdown to Github Pages - Standalone Page")  
* [Standalone Pages with Table of Contents and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/nicolas-van/easy-markdown-to-github-pages/master&homepage=README.md&toc=true&edit-link=https://github.com/nicolas-van/easy-markdown-to-github-pages/blob/master/README.md "Easy Markdown to Github Pages - Standalone Page with Table of Contents")  
* [Standalone Pages with Docsify Sidebar and an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/nicolas-van/easy-markdown-to-github-pages/master&homepage=README.md&sidebar=true&edit-link=https://github.com/nicolas-van/easy-markdown-to-github-pages/blob/master/README.md "Easy Markdown to Github Pages - Standalone Page with Docsify Sidebar")

[A Collection of GitHub Markdown files](https://github.com/paulhibbitts/cmpt-363-222-pages) used as course content [within an SFU CMPT-363 Canvas LMS site](https://canvas.sfu.ca/courses/69678).  

[A Collection of GitHub Markdown files with inline CSS](https://github.com/paulhibbitts/docsify-this-cmpt-363-222-site) used as a [standalone multiple page SFU CMPT-363 course site with SFU visual branding and the Docsify Search plugin enabled](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&loadNavbar=_navbar.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&dark-mode=true&name=CMPT-363-222&search=true#/course-welcome), [standalone multiple page SFU CMPT-363 course site with SFU visual branding and website logo](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&loadNavbar=_navbar.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&dark-mode=true&name=CMPT-363-222&logo=images/logo.png#/course-welcome), and an example [single Markdown file with default visual styling for embeddeding](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&hide-credits=true#/course-welcome).

[GitHub Markdown Content Demo file](https://github.com/hibbitts-design/docsify-this-markdown-content-demo/blob/main/README.md), displayed by Docsify-This as a [Standalone Page with 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-content-demo/main&homepage=README.md&edit-link=https://github.dev/hibbitts-design/docsify-this-markdown-content-demo/blob/main/README.md) using the new [GitHub.dev Web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor) (currently in Beta).  

[GitHub Markdown Content Demo file](https://github.com/hibbitts-design/docsify-this-markdown-content-demo/blob/main/README.md), displayed by Docsify-This as a [Standalone Page with 'View raw Markdown' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-content-demo/main&edit-link=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-content-demo/main/README.md&edit-link-text=View%20raw%20Markdown).  

[Codeberg Markdown Content Demo file](https://codeberg.org/paulhibbitts/docsify-this-markdown-content-demo/src/branch/main/README.md), displayed by Docsify-This as a [Standalone Page with 'View raw Markdown' link](https://docsify-this.net/?basePath=https://raw.codeberg.page/paulhibbitts/docsify-this-markdown-content-demo/&edit-link=https://codeberg.org/paulhibbitts/docsify-this-markdown-content-demo/raw/branch/main/README.md&edit-link-text=View%20raw%20Markdown).  

[GitHub's LaTeX Support Examples Markdown file](https://github.com/dotcom-poland/medium-latex-support/blob/main/README.md), displayed by Docsify-This as a [Standalone Page with an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/dotcom-poland/medium-latex-support/main&edit-link=https://github.com/dotcom-poland/medium-latex-support/blob/main/README.md#/).

[Mermaid-Docsify Example GitHub Markdown file](https://github.com/Leward/mermaid-docsify/blob/master/example/README.md), displayed by Docsify-This as a [Standalone Page with an 'Edit this Page' link](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/Leward/mermaid-docsify/master/example&edit-link=https://github.com/Leward/mermaid-docsify/blob/master/example/README.md#/).  

#### Templates

[Docsify-This Multi-language Site Template](https://github.com/hibbitts-design/docsify-this-multilanguage-site), displayed by Docsify-This as a:
* [Standalone Site with Docsify Sidebar and Navbar](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-multilanguage-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&name=Multi-language%20Site)
* [Standalone Site with Docsify Sidebar, Navbar and Footer](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-multilanguage-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&loadFooter=_footer.md&hide-credits=true&name=Multi-language%20Site)  

[Docsify-This Simple Visual Portfolio Template](https://github.com/hibbitts-design/docsify-this-simple-visual-portfolio) (based on [Notion Portfolio Template](https://www.notion.so/templates/design-portfolio-notion)), displayed by Docsify-This as a:  
* [Standalone Site](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-simple-visual-portfolio/main&homepage=README.md&font-size=1.25&browser-tab-title=Design%20Portfolio&loadFavicon=favicon.png "Docsify-This Simple Visual Portfolio")  
* [Standalone Site with automatic light/dark theme switching](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-simple-visual-portfolio/main&homepage=README.md&font-size=1.25&browser-tab-title=Design%20Portfolio&loadFavicon=favicon.png&dark-mode=true "Docsify-This Simple Visual Portfolio")  
* [Standalone Site using the Merriweather font](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-simple-visual-portfolio/main&homepage=README.md&font-size=1.25&browser-tab-title=Design%20Portfolio&loadFavicon=favicon.png&font-family=Merriweather,Georgia,serif "Docsify-This Simple Visual Portfolio")
* [Standalone Site with zoomable images](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-simple-visual-portfolio/main&homepage=README.md&font-size=1.25&browser-tab-title=Design%20Portfolio&loadFavicon=favicon.png&zoom-images=true "Docsify-This Simple Visual Portfolio")

[Docsify-This Visual Portfolio Template](https://github.com/hibbitts-design/docsify-this-visual-portfolio) (based on [Notion Portfolio Template](https://www.notion.so/templates/design-portfolio-notion)), displayed by Docsify-This as a:  
* [Standalone Site](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-visual-portfolio/main&homepage=README.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&name=Design%20Portfolio "Docsify-This Visual Portfolio")  
* [Standalone Site with automatic light/dark theme switching](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-visual-portfolio/main&homepage=README.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&name=Design%20Portfolio&dark-mode=true "Docsify-This Visual Portfolio")  
* [Standalone Site with larger font size](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-visual-portfolio/main&homepage=README.md&sidebar=true&loadSidebar=_sidebar.md&loadSidebar=_sidebar.md&loadFavicon=favicon.png&name=Design%20Portfolio&font-size=1.25 "Docsify-This Visual Portfolio") 
* [Standalone Site with zoomable images](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-visual-portfolio/main&homepage=README.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&name=Design%20Portfolio&zoom-images=true "Docsify-This Visual Portfolio")
* [Standalone Site with pagination](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-visual-portfolio/main&homepage=README.md&sidebar=true&loadSidebar=_sidebar.md&loadFavicon=favicon.png&name=Design%20Portfolio&pagination=true#/ "Docsify-This Visual Portfolio") 

A simple [Markdown Student Portfolio Starter Template](https://github.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter) (based on [Markdown Student Portfolio Template](https://github.com/thoresonjd/markdown-portfolio-template) by [Justin Thoreson](https://github.com/thoresonjd)) which is viewable on both GitHub and with Docsify-This.net, displayed by Docsify-This as:  
* [Standalone Site](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md "Docsify-This Markdown Student Portfolio Starter Template")  
* [Standalone Site with automatic light/dark theme switching](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md&dark-mode=true "Docsify-This Markdown Student Portfolio Starter Template")  
* [Standalone Site using the Merriweather font](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md&font-family=Merriweather,Georgia,serif "Docsify-This Markdown Student Portfolio Starter Template")
* [Standalone Site using the Merriweather font and red links](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md&font-family=Merriweather,Georgia,serif&link-color=cc0000#/ "Docsify-This Markdown Student Portfolio Starter Template")
* [Standalone Site with zoomable images](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md&zoom-images=true "Docsify-This Markdown Student Portfolio Starter Template")
* [Standalone Site with 'Edit this Page' links](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/main&homepage=README.md&edit-link=https://github.com/hibbitts-design/docsify-this-markdown-student-portfolio-starter/blob/main/README.md "Docsify-This Markdown Student Portfolio Starter Template")  

---

### Page Appearance URL Parameters

#### Base URL Parameters (included in the standard Web Page Builder)

* [browser-tab-title](#browser-tab-title)
* [edit-link](#edit-link)
* [edit-link-text](#edit-link-text)
* [edit-link-top](#edit-link-top)
* [font-family](#font-family)
* [font-size](/#font-size)
* [header-weight](#header-weight)
* [hide-credits](#hide-credits)
* [hypothesis](#hypothesis)
* [line-height](#line-height)
* [link-color](#link-color)
* [maxLevel](#maxLevel)
* [sidebar](/#sidebar)
* [toc](#toc)
* [toc-headings](#toc-headings)
* [toc-narrow](#toc-narrow)
* [zoom-images](#zoom-images)

##### browser-tab-title
Set a custom title on Browser tab for your standalone pages with the optional **browser-tab-title** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/demo-grav-open-matter-course-hub/master/pages/04.resources&homepage=page.md&browser-tab-title=Resources Please note to use titles with spaces they must be [encoded](https://meyerweb.com/eric/tools/dencoder/), so "My Page" would be "My%20Page".  

##### edit-link
Display a "Edit this Page" link (default location is bottom of page) with the optional **edit-link** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&edit-link=https://github.com/hibbitts-design/docsify-open-publishing-starter-kit/blob/main/README.md

##### edit-link-text
Change the default text for a "Edit this Page" link with the optional **edit-link-text** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&edit-link=https://github.com/hibbitts-design/docsify-open-publishing-starter-kit/blob/main/README.md&edit-link-text=View%20as%20Markdown Please note to use text with spaces they must be [encoded](https://meyerweb.com/eric/tools/dencoder/), so "View as Markdown" would be "View%20as%20Markdown".  

##### edit-link-top
Change the location of the "Edit this Page" link from the bottom of pages to be the top of pages with the optional **edit-link-top** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&toc=true&edit-link=https://github.com/hibbitts-design/docsify-open-publishing-starter-kit/blob/main/README.md&edit-link-top=true

##### font-family
Set a custom font for your standalone pages with the optional **font-family** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&font-family=Helvetica,Arial,sans-serif. This parameter can be particularly valuable when trying to better match the visual presentation of embedded content with your destination platform. Please note to use fonts with spaces in their names they must be [encoded](https://meyerweb.com/eric/tools/dencoder/), so "Courier New" would be "Courier%20New".  

##### font-size
Set a custom font size for your standalone pages with the optional **font-size** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&font-size=1. This parameter can be particularly valuable when trying to better match the visual presentation of embedded content with your destination platform. Please note the font size is set in [REM units](https://www.freecodecamp.org/news/what-is-rem-in-css/).  

##### header-weight
Set a custom header weight (default is 400 - regular) for your standalone pages with the optional **header-weight** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&header-weight=600. 

##### hide-credits
Hide the credits usually shown at the bottom of every displayed Docsify-This page with the optional **hide-credits** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&hide-credits=true.

##### hypothesis
Enable page annotation with [Hypothes.is](https://hypothes.is) with the optional **hypothesiss** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&hypothesis=true.  

##### line-height
Set a custom line height for your standalone pages with the optional **line-height** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&line-height=1.5. 

##### link-color
Set a custom color for all links, defined using the standard hexadecimal format _without the '#' symbol_ with the optional **link-color** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&link-color=CC0000.

##### maxLevel
Set the maximum header level of the Docsify sidebar with the optional **maxLevel** Docsify parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&sidebar=true&maxLevel=3 

##### sidebar
Display a Docsify sidebar with the optional **sidebar** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&sidebar=true 

##### toc
Display a page table of contents with the optional **toc** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&toc=true

##### toc-headings
Set the page heading levels (i.e. h1, h2, etc.) to be included in the Page Table of Contents with the optional **toc-headings** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&toc=true&toc-headings=h1,h2,h3.

##### toc-narrow
Use a less wide Page Table of Contents with the optional **toc-narrow** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&toc-narrow=true. This parameter can be particularly valuable when embedding content where a smaller screen area is likely.  

##### zoom-images
Enable image zoom (tapping on images to enlarge them) with the optional **zoom-images** Docsify parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-markdown-content-demo/main&zoom-images=true. To exclude images, use `![](image.png ":no-zoom")`.  

#### Additional URL Parameters (included in the Advanced Web Page Builder)

The following additional URL parameters are also available for use in Docsify-This URLs, and are included in the [Advanced Web Page Builder](ttps://docsify-this.net?advanced=true) unless otherwise indicated.

* [coverpage](#coverpage)
* [coverpage-color](#coverpage-color)
* [coverpage-color-dark-mode](#coverpage-color-dark-mode)
* [dark-mode](#dark-mode)
* [edit-link-emoji](#edit-link-emoji)
* [link-color-dark-mode](#link-color-dark-mode)
* [loadFavicon](#loadFavicon)
* [loadFooter](#loadFooter)
* [loadNavbar](#loadNavbar)
* [loadSidebar](#loadSidebar)
* [logo](#logo)
* [name](#name)
* [page-title](#page-title)
* [pagination](#pagination)
* [search](#search)
* [submaxLevel](#subMaxLevel)

##### coverpage
Display a [Docsify custom coverpage](https://docsify.js.org/#/configuration?id=coverpage) with the optional **coverpage** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=home.md&coverpage=_coverpage.md

##### coverpage-color
Set a custom color for the coverpage with the optional **coverpage-color** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=home.md&coverpage=_coverpage.md&coverpage-color=cc0000

##### coverpage-color-dark-mode
Set a custom color for the coverpage in dark mode with the optional **coverpage-color-dark-mode** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=home.md&dark-mode=true&link-color=CC0000&link-color-dark-mode=FF9E9E&coverpage=_coverpage.md&coverpage-color=cc0000&coverpage-color-dark-mode=4d0000

##### dark-mode
Automatically switch light/dark theme based on system OS-level preference, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&dark-mode=true

##### edit-link-emoji
Change the default emoji for a "Edit this Page" link with the optional **edit-link-emoji** parameter (not included in the Advanced Web Page Builder), for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&edit-link=https://github.com/hibbitts-design/docsify-open-publishing-starter-kit/blob/main/README.md&edit-link-text=View%20on%20GitHub&edit-link-emoji=:file_folder:

##### link-color-dark-mode
Set a custom color for all links in dark mode, defined using the standard hexadecimal format _without the '#' symbol_ with the optional **link-color-dark-mode** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/docs&homepage=resources.md&link-color=CC0000&dark-mode=true&link-color-dark-mode=FF9E9E.

##### loadFavicon
You can set a custom Favicon from the image file passed from the optional **loadFavicon** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-markdown-content-demo/main&loadFavicon=open-access.png

##### loadFooter
Load a Docsify footer from the Markdown file in the current directory passed with the optional **loadFooter** Docsify parameter, for example:
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&loadFooter=_footer.md

##### loadNavbar
Load a [Docsify custom navbar](https://docsify.js.org/#/custom-navbar?id=custom-navbar) from the Markdown file passed with the optional **loadNavbar** Docsify parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-publishing-starter-kit/main/docs&homepage=introduction.md&loadNavbar=_navbar.md

##### loadSidebar
Load a [Docsify custom sidebar](https://docsify.js.org/#/more-pages?id=sidebar) from the Markdown file passed with the optional **loadSidebar** Docsify parameter, for example:  
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar-with-home.md  

##### logo
Display a logo image for the Website in a Docsify custom Sidebar (i.e. file 'logo.png) with the optional **logo** Docsify parameter, for example:  
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&name=CPT-363&logo=/images/logo.png The full folder path and filename must be provided. When a Website name is provided it will be used as the alt text for the logo.  

##### name
Display the name for the Website in a Docsify custom Sidebar (i.e. file '_sidebar.md) with the optional **name** Docsify parameter, for example:  
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&search=true&name=CPT-363  When this parameter is provided it will be automatically used as the Browser tab title as well.  

##### page-title
Set a custom page title at the top of your standalone pages with the optional **page-title** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/demo-grav-open-matter-course-hub/master/pages/04.resources&homepage=page.md&page-title=Resources Please note to use titles with spaces they must be [encoded](https://meyerweb.com/eric/tools/dencoder/), so "My Page" would be "My%20Page".  

##### pagination
Display Pagination buttons in page content area (Docsify custom Sidebar required) with the optional **pagination** parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&search=true&pagination=true  

##### search
Enable the Docsify Search plugin (which currently includes matches for text and markup) on multiple page sites including a custom Sidebar with the optional **search** Docsify parameter, for example:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-course-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar.md&loadNavbar=_navbar.md&search=true

##### subMaxLevel
Set the maximum automatic table of contents header levels in Docsify custom Sidebar (i.e. file '_sidebar.md) with the optional **subMaxLevel** Docsify parameter, for example:  
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&sidebar=true&loadSidebar=_sidebar-with-home.md&subMaxLevel=1

---

### Embedding Docsify-This Pages into Other Platforms

#### Canvas LMS

[Embed content in Canvas](https://www.howtocanvas.com/create-amazing-pages-in-canvas/embedding-content)  
iFrame code example, including URL parameters to seamlessly match Docsify-This content to Canvas:  

```html
<p><iframe style="overflow: hidden; border: 0px #ffffff none; background: #ffffff;" src="https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363-222-pages/main&homepage=home.md&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica,Arial,sans-serif&font-size=1&hide-credits=true" width="800px" height="1400px" allowfullscreen="allowfullscreen"></iframe></p>
```

If a scroll bar is present, you may want to re-edit your iFrame code and adjust the "height" value.  

[How do I add an external URL as a module item?](https://community.canvaslms.com/t5/Instructor-Guide/How-do-I-add-an-external-URL-as-a-module-item/ta-p/967)  
Module external link example, with Page Table of Contents:  

```html
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363/main/docs/222&homepage=week-02.md&toc-narrow=true&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica,Arial,sans-serif&font-size=1&hide-credits=true
```

[Creating a custom link in your course navigation using the Redirect Tool](https://help.canvas.yale.edu/m/55452/l/914676-creating-a-custom-link-in-your-course-navigation-using-the-redirect-tool)  
Redirect URL field example:  

```html
https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363-222-pages/main&homepage=resources.md&edit-link=https://github.com/paulhibbitts/cmpt-363-222-pages/blob/main/resources.md&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica,Arial,sans-serif&font-size=1&hide-credits=true
```

#### Moodle LMS

[iFrame (for embedding content within pages)](https://docs.moodle.org/401/en/Iframe)  

[External tool (for adding a link to course navigation or elements)](https://docs.moodle.org/401/en/External_tool)

---

### Markdown Syntax References

* [What Is Markdown, and How Do You Use It?](https://www.howtogeek.com/448323/what-is-markdown-and-how-do-you-use-it/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Guide](https://www.markdownguide.org/)

---

### Font Awesome Icons

The display of [Font Awesome Free](https://fontawesome.com/icons) icons within Markdown content is supported with the following format:

:`fas fa-home fa-fw`:

The above Markdown is equivalent to the HTML markup `<i class="fas fa-home fa-fw" aria-hidden="true"></i>`.

When using the above shortcode for Font Awesome icons, it is assumed it is assumed to be for decorative purposes, and so for improved accessibility an `aria-hidden="true"` attribute is automatically added to the icon. For semantic purposes, it is recommended you refer to the [Font Awesome Icons and Accessibility](https://docs.fontawesome.com/web/dig-deeper/accessibility) guidelines.

The following style prefixes are available with Docsify-This:

* fas (i.e. [Solid](https://fontawesome.com/search?o=r&m=free&s=solid))
* fab (i.e. [Brands](https://fontawesome.com/search?o=r&m=free&f=brands))

---

### Supported Markdown CSS Classes

* [accordion](#accordion)
* [badge](#badge)
* [banner-image](#banner-image)
* [banner-tall-image](#banner-tall-image)
* [button](#button)
* [button-rounded](#button-rounded)
* [button-secondary](#button-secondary)
* [button-secondary-rounded](#button-secondary-rounded)
* [embedly-card](#embedly-card)
* [header-image-fade](#header-image-fade)
* [header-image-full-width](#header-image-full-width)
* [image-75/image-50/image-25](/#image-75image-50image-25)
* [image-75-border/image-50-border/image-25-border](#image-75-borderimage-50-borderimage-25-border)
* [image-border](#image-border)
* [image-border-rounded](#image-border-rounded)
* [navpill](#navpill)
* [responsive](/#responsive)
* [row/column](#rowcolumn)
* [video-container-4by3](#video-container-4by3)
* [video-container-16by9](#video-container-16by9)

The following CSS classes are available when authoring your own Markdown content.  

#### accordion

```html
<div class="accordion">

<details>
  <summary>Topic One</summary>
  
  Topic one details here.
  
</details>

<details>
  <summary>Topic Two</summary>
  
  Topic two details here.
  
</details>

</div>
```

#### badge

```html
<span class='badge'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge' style='--badge-bg-color: #0164db;'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge' style='--badge-bg-color: #e7c500; --badge-text-color: #000;'> Tue Jun 12th 11:59pm PDT</span>
```

```html
<span class='badge'> [Tue May 16 2:30pm PT](https://www.timeanddate.com/worldclock/fixedtime.html?msg=CMPT-363+Blackboard+Mini-lectures+and+Activities&iso=20220516T1430&p1=256&ah=1&am=50)</span>  
```

#### banner-image
Cropped to height of 250px on large screens, 125px on small screens.  

```markdown
![UX - User Experience](images/12650723674_d5c85af332_k.jpg ':class=banner-image')
```

#### banner-tall-image
Cropped to height of 350px on large screens, 175px on small screens.   

```markdown
![UX - User Experience](images/12650723674_d5c85af332_k.jpg ':class=banner-tall-image')
```

#### button

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button')
```

```markdown
[:fa fa-download fa-fw:Download](https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip ':class=button')
```

```html
<a class="button" href="https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip" target="_blank"><i class="fa fa-download fa-fw"></i>Download</a>
```

#### button-rounded

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-rounded')
```

```markdown
[:fa fa-download fa-fw:Download](https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip ':class=button-rounded')
```

```html
<a class="button-rounded" href="https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip" target="_blank"><i class="fa fa-download fa-fw"></i>Download</a>
```

#### button-secondary

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-secondary')
```

```markdown
[:fa fa-download fa-fw:Download](https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip ':class=button')
```

```html
<a class="button-secondary" href="https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip" target="_blank"><i class="fa fa-download fa-fw"></i>Download</a>
```

#### button-secondary-rounded

```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=button-secondary-rounded')
```

```markdown
[:fa fa-download fa-fw:Download](https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip ':class=button-secondary-rounded')
```

```html
<a class="button-secondary-rounded" href="https://creativecommons.org/wp-content/uploads/2019/02/ccheart_black.svg_.zip" target="_blank"><i class="fa fa-download fa-fw"></i>Download</a>
```

#### embedly-card
For linked article previews, embedded slides/videos, etc.  

```html
<a class="embedly-card" data-card-controls="0" data-card-align="left" href="https://blog.prototypr.io/defining-usability-e7bf42e8abd0">Defining usability</a>
```

#### header-image-fade
Suggested width of 1200px to 2000px.  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image-fade')
```

#### header-image-fade-full-width
Suggested width of 1200px to 2000px, and display of Table of Contents is not available.  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image-fade-full-width')
```

#### header-image-full-width
Suggested size of 1200px to 2000px width and 400px to 600px height, and display of Table of Contents is not available.  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=header-image')
```

#### image-75/image-50/image-25
Scale images to %.  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-75')
```

#### image-75-border/image-50-border/image-25-border
Scale images with border to %.  

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-75-border')
```

#### image-border

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-border')
```

#### image-border-rounded

```markdown
![Photo of Mountain](images/mountain.jpg ':class=image-border-rounded')
```

#### navpill

```markdown
[GitHub](https://github.com/hibbitts-design/docsify-this ':class=navpill')
```

```markdown
[:fab fa-github fa-fw:GitHub](https://github.com/hibbitts-design/docsify-this ':class=navpill')
```

```html
<a class="navpill" href="https://github.com" target="_blank"><i class="fab fa-github fa-fw"></i>GitHub</a>
```

#### responsive
Make raw HTML images that include size dimensions responsive.

```html
<img src="https://raw.githubusercontent.com/hibbitts-design/publishing-with-docsify-this/main/images/docsify-this-web-page-builder.jpg" width="910" height="682" class="responsive image-border" alt="Docsify-This Web Page Builder">
```

#### row/column

```html
<div class="row">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

#### row/column with reversed column order

```html
<div class="row reverse-columns">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

#### row/column with right-aligned second column

```html
<div class="row">
<div class="column">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
<div class="column-right">

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

</div>
</div>
```

#### video-container-4by3

```html
<div class="video-container-4by3"><div class="video-container-16by9"><iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ"></iframe></div>
```

#### video-container-16by9
Automatically added to all iFrames with the source domains 'youtube.com' or 'docs.google.com'.  
```html
<div class="video-container-16by9"><iframe width="560" height="315" src="https://www.youtube.com/embed/lJIrF4YjHfQ"></iframe></div>
```

---

### Custom Markdown CSS Classes

In addition to the Markdown CSS classes supported by Docsify-This, you can also define your own custom classes within your displayed Markdown files, for example:

CSS in Markdown file:  
```css
<style>
.markdown-section .mybutton, .markdown-section .mybutton:hover {
  cursor: pointer;
  color: #CC0000;
  height: auto;
  display: inline-block;
  border: 2px solid #CC0000;
  border-radius: 4rem;
  margin: 2px 0px 2px 0px;
  padding: 8px 18px 8px 18px;
  line-height: 1.2rem;
  background-color: white;
  font-family: -apple-system, "Segoe UI", "Helvetica Neue", sans-serif;
  font-weight: bold;
  text-decoration: none;
}
</style>
```

Markdown:  
```markdown
[Required Reading Quiz due Jun 4th](https://canvas.sfu.ca/courses/44038/quizzes/166553 ':class=mybutton')
```

---

### Tips and Techniques

#### Making a Raw Markdown File Available Online
There are multiple ways to get a raw Markdown file available online, here are three options to help you get started:

**GitHub or Codeberg:**  
1. Signup for a [GitHub](https://github.com) or [Codeberg](https://codeberg.org) account
2. Create a new repository and upload your Markdown file
3. View the uploaded file, and copy/paste that URL into the Docsify-This **Markdown File URL** field

**Gist (GitHub Gists):**
1. Signup for a [GitHub](https://github.com) account
1. Create a gist with your Markdown file at https://gist.github.com
2. Enter a filename ending with `.md` (e.g. `myfile.md`)
3. Choose **Create public gist** and tap on that button
4. Tap on **Raw** button in the upper right of your Gist field and copy/paste that URL into the Docsify-This **Markdown File URL** field

**Personal or Organizational Website:**  
1. Obtain login information for your server
2. Upload the Markdown file to your server
3. Navigate to the location of that file, view the contents in your Browser, and copy/paste that URL into the Docsify-This **Markdown File URL** field

#### Matching Fonts with Your Destination Platform Content
Use a page inspector to identify the font family and font size used in the platform you are embedding Docsify-This content in, and then pass that font family using the `font-family` ([encoded](https://meyerweb.com/eric/tools/dencoder/), where spaces are replaced with '%20') and `font-size` (REM units) URL parameters to Docsify-This. For example, to match fonts with the Canvas LMS:  
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363-222-pages/main&homepage=topics.md&font-family=Lato%20Extended,Lato,Helvetica%20Neue,Helvetica,Arial,sans-serif&font-size=1  

#### Providing a Page Table of Contents within a Smaller Destination Platform Screen Area
If you want to include a Page Table of Contents with embedded Docsify-This content, but the destination platform screen area is not very wide, you might want to try the optional `toc-narrow` display option. For example, to use a narrower Table of Contents area that includes a smaller screen breakpoint:
https://docsify-this.net?basePath=https://raw.githubusercontent.com/paulhibbitts/cmpt-363/main/docs/222&homepage=week-01.md&toc-narrow=true  

#### Including Code Blocks
Using [Prismjs](https://prismjs.com/) code blocks with syntax highlighting is supported for the languages [included with Docsify](https://docsify.js.org/#/language-highlight?id=language-highlighting) and as well Bash, Go, Java, Kotlin, PHP, Python and Swift. To embed a code block use the Markdown standard of triple backticks and start the block with the name of the language, for example to embed a block of Javascript code with syntax highlight the following would be used:  

<pre>
```javascript
function test() {
  console.log("Hello world!");
}
```
</pre>

Which would then appear as:

```javascript
function test() {
  console.log("Hello world!");
}
```

#### Including Interactive Javascript Blocks
Using the Docsify Plugin [RunKit](https://jhildenbiddle.github.io/docsify-plugin-runkit/) interactive JavaScript <abbr title="Read-Eval-Print Loop">REPLs</abbr> powered by RunKit can be embedded, for example to embed a data visualization rendered using [D3.js](https://d3js.org/) the following would be used:  


````html
<div
  data-runkit
>

```javascript
var R = require("ramda");
var randrange = require("random-number-in-range");
var d3Graph = require("@runkit/runkit/d3-graph/1.0.0");

var count = 100;
var nodes = R.range(0, 100).map((_, x) => ({ "name": x, "group": Math.floor(x * 7 / count) }));

var links = R.range(0, Math.floor(count * 1.15)).map(function(_, x) {
    var source = x % count;
    var target = Math.floor(Math.log(1 + randrange(0, count)) / Math.log(1.3));
    var value = 10.0 / (1 + Math.abs(source - target));

    return { "source": source, "target": target, "value": value };
});

d3Graph(nodes, links);
```

</div>
````

#### Including External Markdown Content

The content of external Markdown files can be embedded into Docisfy-This Web pages with the following:

```markdown
[included Markdown from same source location](example.md ':include')
```

```markdown
[included Markdown from URL](https://raw.githubusercontent.com/paulhibbitts/Markdown-File-Tests/main/itworks.md ':include')
```

For additional examples of including external content, view [Docsify Embeded Files](https://docsify.js.org/#/embed-files?id=embed-files).

#### Use of WikiLinks
[WikiLinks format](https://help.obsidian.md/Linking+notes+and+files/Internal+links) for links and images are supported, as also found in the desktop editor [Obsidian](https://obsidian.md) and other platforms.  

#### Display of AsciiDoc files (file extension .adoc)
The display of [AsciiDoc](https://asciidoc.org/) files ('.adoc' extension) via [DownDoc](https://github.com/opendevise/downdoc) is possible by manually passing the relevant filenames within a Docsify-This URL (not available in the Docisfy-This.net Web Page Builder), for example: https://docsify-this.net/?basePath=https://raw.githubusercontent.com/asciidoctor/asciidoctor-pdf/main/examples&homepage=basic-example.adoc&edit-link=https://github.com/asciidoctor/asciidoctor-pdf/blob/main/examples/basic-example.adoc  

You can support the display of AsciiDoc files in the Web Page Builder of your own instance of Docsify-This by locating the function `getAllowedFileExtensions()` within the `index.html` file and add the file extension '.adoc' to the `return` statement, for example `return ".md,.adoc";`.  

#### Display of HedgeDocs files
The display of [HedgeDoc](https://hedgedoc.org/) files containing basic Markdown (as well as Mermaid and MathJax elements) is possible by manually using 'download' for the `homepage` URL parameter within a Docsify-This URL (not available in the Docisfy-This.net Web Page Builder), for example: https://docsify-this.net/?basePath=https://demo.hedgedoc.org/crN3ispNQdejWkUXXIXYQA&homepage=download  

Here is an additional example, using the HedgeDoc file https://demo.hedgedoc.org/oisWMy9ZS36PE6TvYhJC4A?both (seen in split-screen view) and and rendered as a standalone Web page by Docsify-This https://docsify-this.net/?basePath=https://demo.hedgedoc.org&homepage=oisWMy9ZS36PE6TvYhJC4A/download&edit-link=https://demo.hedgedoc.org/oisWMy9ZS36PE6TvYhJC4A?both&toc=true&edit-link-text=Edit%20this%20Page%20in%20HedgeDoc  

You can support HedgeDoc URLs (e.g. https://demo.hedgedoc.org/ip4SRxZYTEKa6JHr62XTiA) in the Web Page Builder of your own instance of Docsify-This by locating the line `var hedgedocInstances = '';` within the `index.html` file and include your HedgeDoc instances separated by commas, for example `var hedgedocInstances = 'demo.hedgedoc.org';`. Try out a demo instance of Docsify-This with support for demo.hedgedoc.org files at https://hibbitts-design.github.io/hedgedoc-docsify-this.  

#### Changing the Default Values of the Docsify-This Web Page Builder
You can configure the default values of the Docsify-This Web Page Builder via URL parameters - this is especially useful when doing Docsify-This online sessions/workshops as well as Docsify-This users helping each other out. In addition to Docsify-This URL parameters, the following Web Page Builder URL parameters are available:  

##### url-field
```html

https://docsify-this.net/?url-field=https://codeberg.org/paulhibbitts/docsify-this-one-page-course/src/branch/main/home.md

```

```html

https://docsify-this.net/?url-field=empty

```

##### edit-link-checkbox
```html

https://docsify-this.net/?url-field=https://codeberg.org/paulhibbitts/docsify-this-one-page-course/src/branch/main/home.md&edit-link-checkbox=true

```

##### show-page-options
```html

https://docsify-this.net/?show-page-options=true

```

##### advanced
```html

https://docsify-this.net/?advanced=true

```

For example, the following URL will display the Advanced Web Page Builder, with the Markdown file URL set to `https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main/home.md`, the site name 'CPT-363' along with a Docsify custom Sidebar and Navbar to be included: https://docsify-this.net/?url-field=https://github.com/hibbitts-design/docsify-this-multiple-page-course-site/blob/main/home.md&sidebar=true&loadSidebar=true&loadNavbar=true&name=CPT-363

The quickest way to create such a shareable URL is to use the Docsify-Web Page Builder to generate a Docisfy-This web page URL, and then replace the URL parameter `basepath` with `url-field` using the full path of the source Markdown file URL. For example, the URL https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&sidebar=true&maxLevel=3 would be changed to https://docsify-this.net/?url-field=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md&homepage=home.md&sidebar=true&maxLevel=3.

#### Use of Camel case (e.g. camelCase) format for Docsify-This URL parameter names instead of hyphenated names
You can use [camel case](https://en.wikipedia.org/wiki/Camel_case) instead of hyphens for the names of Docsify-This URL parameters if prefered. For example, https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&toc=true&toc-headings=h2,h3&edit-link=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md and https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-one-page-article/main&homepage=home.md&toc=true&tocHeadings=h2,h3&editLink=https://github.com/hibbitts-design/docsify-this-one-page-article/blob/main/home.md are equilivent.

#### Use of New Web Editor GitHub.dev
To use the new GitHub.dev Web editor (currently in Beta) for 'Edit this Page' links, change `github.com` to `github.dev` for GitHub.com files entered into the Web Page Builder Markdown File URL field.

---

### Editing Docsify-This Markdown Files on your Desktop

When using Docsify-This to display Markdown files located on Git-based services such as GitHub or Codeberg you can download (clone) files to your desktop for local editing and then upload (push) changes back to the online files.

For example, to edit GitHub Markdown files on your desktop you would do the following:

1. Tap **Code** on your GitHub Markdown files repository (upper-right green button)
2. Choose **Open Desktop** and follow the prompts, installing [GitHub Desktop](https://desktop.github.com/) if not already present
3. You will now be able to edit the Docsify-This Markdown files using the desktop text editor of your choice such as [Microsoft Visual Studio](https://code.visualstudio.com/), [Pulsar](https://pulsar-edit.dev/) (was Atom.io), [Typora](https://typora.io/) etc.
4. Use GitHub Desktop to push any changes to your repository.  

[Learn more about getting started with GitHub Desktop](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop).

---

### Improving Markdown Previews in Text Editors

Some text editors, such as [Microsoft Visual Studio](https://code.visualstudio.com/) (including the online [GitHub.dev Web editor](https://docs.github.com/en/codespaces/the-githubdev-web-based-editor)), have the ability to link your own CSS so Markdown previews are more visually accurate. If your editor supports this ability, the below CSS files can be used.

Docsify-This (based on the Docsify Open Publishing Starter Kit) CSS:  
https://docsify-this.net/assets/css/editor.css

FontAwesome CSS:  
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css

---

### Looking for Even More Customization and Control?

Docsify-This is intended as a quick way to display one or more remotely located Markdown files. To further customize the rendering of remote files and have the posibility to have an instance of Docsify-This running on a custom domain, fork/clone your own instance of [Docsify-This](https://github.com/hibbitts-design/docsify-this) on GitHub and enable GitHub Pages with the folder `/docs`.  

You can also have an instance of Docsify-This run on [Codeberg](https://codeberg.org/) such as https://docsify-this.codeberg.page by creating a new repository called `pages`, then choosing **paulhibbitts/docsify-this-app** in the **template** dropdown menu, choosing the **Git Content (Default Branch)** option and then tapping the **Create Repository** button.  

Alternatively, you can upload the files in the Docsify-This `/docs` folder into a newly created Codeberg repository and then manually enable [Codeberg Pages](https://docs.codeberg.org/codeberg-pages/). An example Docsify-This instance running on Codeberg is available at https://codeberg.org/paulhibbitts/docsify-this-app, which uses a Branch renamed to `pages`.  

If you want to run Docsify-This on your own Websever, create a destination folder on your server and then copy the files within the Docsify-This folder `/docs` to your newly created server folder. 

A more future-friendly setup would be to fork the Docsify-This repository (to support getting upstream updates) and use a GitHub Action such as [FTP-Deploy](https://github.com/SamKirkland/FTP-Deploy-Action) to deploy all repository files to a Webserver and set the `docs` folder as a custom domain root. You can limit the domains which remote files can be rendered from by locating the line `var allowedDomains = '';` within the `index.html` file and include your list of allowed domains separated by commas, for example `var allowedDomains = 'codeberg.org,raw.githubusercontent.com,hibbittsdesign.org';`.  

You can even run Docsify-This on LMSs that support file libraries such as Canvas and Moodle. For example, here is a [Docsify-This instance on Canvas](https://canvas.instructure.com/courses/6321275/files/folder/docsify-this/docs?preview=212476355).

To host a Docsify-This instance on your LMS, do the following:  
1. Tap **Download** on the [Docsify-This repository page](https://github.com/hibbitts-design/docsify-this)
2. Upload to your LMS file storage area, and unzip the upload file
3. Based on your LMS, determine the external URL required to load the `index.html` file within the Docsify `Docs` folder. In Canvas, an example URL would look similar to `https://canvas.instructure.com/courses/6321275/files/211083785/download`.

If you want to further customize and control the presentation of your Markdown content, especially when rendering multiple page sites, you can install your own [Docsify Open Publishing Starter Kit](https://github.com/hibbitts-design/docsify-open-publishing-starter-kit) (that this hosted web app is based on) and store all Markdown files within that site. You can learn more about the capabilities of Docsify itself at [Docsify.js.org](https://docsify.js.org).  

Looking for some help with getting a Docsify custom-This instance up and running for your organization? Paul provides a range of professional services related to Docsify-This - [contact him to learn more](https://docsify-this.net/#/?id=contact-and-support).  

---

### Additional Docsify-This Learning Materials

[Introduction to Docsify⁠–⁠This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/otessa-2024/main/pages&homepage=introduction-to-docsify-this.md&edit-link=https://github.com/paulhibbitts/otessa-2024&sidebar=true&edit-link-text=View%20on%20GitHub&edit-link-emoji=:file_folder:&browser-tab-title=Introduction%20to%20Docsify-This&header-weight=600&dark-mode=true&coverpage=_coverpage.md)  
_Introductory, beginner to intermediate._  
An introduction of Markdown publishing using the open source project Docsify⁠–⁠This.  

[Self-Publishing with Docsify⁠–⁠This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/self-publishing-with-docsify-this/main/pages&homepage=introduction-to-self-publishing-with-docsify-this.md&edit-link=https://github.com/paulhibbitts/self-publishing-with-docsify-this&sidebar=true&maxLevel=4&edit-link-text=View%20on%20GitHub&edit-link-emoji=:file_folder:&browser-tab-title=Overview%20to%20Self-Publishing%20with%20Docsify-This&header-weight=600&dark-mode=true&coverpage=_coverpage.md)  
_Intermediate, with a mix of basic and advanced aspects._  
An overview to self-publishing with Markdown using the open source project Docsify⁠–⁠This, with a focus on digital literacy.

---

### Troubleshooting

_'404 - Not found' message is displayed._  
The provided **basePath** parameter and/or optional **homepage** parameter may not be correct, verify that these items lead to accessible content. This error message may also result from a [Cross-Origin Resource Sharing (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) policy, which restricts resources on a web page to be requested from another domain. If possible, relocate files to a domain that supports cross-origin requests or alternatively if the domain in question is under your control explore re-configuring [CORS related settings](https://www.w3.org/wiki/CORS_Enabled). You can confirm the cause of the 404 message by viewing the errors displayed in the [Browser Javascript Console](https://balsamiq.com/support/faqs/browserconsole/).  

When displaying GitHub Markdown files, the branch name is assumed to be `main`, and other paths will likely cause a 404 message. When displaying Codeberg Markdown files, the path is assumed to contain `/src/branch/main` and other paths will likely cause a 404 message.  

_Generation of 'Edit this Page' links on multiple page Markdown sites with a Navbar or custmom Sidebar not working as expected._   
Due to not being able to update Navbar or custom Sidebar links before page rendering, 'Edit this Page' links cannot be automatically updated to their correct target pages. Manually pass a URL pointing to the Git Repository using the URL parameter `edit-link` as a workaround, for example https://docsify-this.net/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-this-multiple-page-site/main&homepage=home.md&loadNavbar=_navbar&edit-link=https://github.com/hibbitts-design/docsify-this-multiple-page-site&edit-link-text=GitHub%20Repository and https://docsify-this.net/?basePath=https://raw.githubusercontent.com/paulhibbitts/docsify-this-cmpt-363-222-site/main&homepage=home.md&loadNavbar=_navbar.md&sidebar=true&loadSidebar=_sidebar.md&edit-link=https://github.com/paulhibbitts/docsify-this-cmpt-363-222-site/tree/main&edit-link-text=GitHub%20Repository

_Updated Markdown file not displayed in the Browser._  
Docsify is likely displaying the last cached version. To ensure the most recent version of a file is loaded, do a [hard refresh of your Browser cache](https://www.makeuseof.com/hard-refresh-browser/).

_Embedded image not displayed as expected._  
The most likely cause for embedded images in Markdown not being displayed as expected is the use of relative paths (i.e. `![Alt Text](images/filename.jpg)`) - review image paths and ensure the full path to each image is used (i.e. `![Alt Text](/folder/images/filename.jpg)`). Likewise, if images in HTML are not being displayed as expected the likely cause is again the use of relative paths (i.e. `<img src="images/filename.jpg" alt="Alt Text">`) - use absolute URLs for HTML image sources (i.e. `<img src="https://raw.githubusercontent.com/user/repository/main/images/filename.jpg" alt="Alt Text">`).

_Embedded iFrame not displayed as expected._   
Due to iframe cross-domain issues embedded content may not be able to be displayed. Use the included rich media embed service [embed.ly](https://embed.ly/) as a workaround.  

For example, the following iFrame HTML:  

```html
<div class="video-container-16by9"><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRnnRFelgw1ksq_p8Eryg3dnyLCRRLPf5fBgdwdv9p-tCIwcxqWvzDGrGbjxGHL7HqEJVpmV26ntk3a/embed?start=false&loop=false&delayms=3000" frameborder="0" width=780" height="585" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></div>
```

Would be changed to:  

```html
<a class="embedly-card" data-card-controls="0" data-card-align="left" data-card-width="100%" href="https://docs.google.com/presentation/d/1BLaaOTsGxDmNcAhg6pdx3hl9IvI8NErg8Oe5ceh83fw/edit?usp=sharing">Grav and Docsify Slides Placeholder</a>
```

_Docsify Sidebar or custom Sidebar is not displaying individual page header levels as expected._  
When displaying a Docsify Sidebar or custom Sidebar, it is expected that page header levels start with a H1 level header.  

_Search results do not seem to return all expected matches._  
When the search field is enabled in a Docsify custom Sidebar, only pages listed and linked in the Sidebar will be indexed for the search. Any pages linked in an optional Navbar will not be included in searches.  

_Multiple embedded scripts are not working as expected._  
Docsify-This (as with Docsify itself) will only execute the first script included in a Markdown page, as described in the [Docsify documentation](https://docsify.js.org/#/configuration?id=executescript).

---

### Privacy Policy Summary

* This website is hosted by [GitHub Pages, which is GDPR compliant](https://github.blog/2018-04-19-updates-to-our-privacy-statement-and-terms-of-service/)
* Only this web page (containing the Web Page Builder) uses [Google Analytics in a GDPR manner](https://support.google.com/analytics/answer/9019185?hl=en#IP&zippy=%2Cin-this-article)
* Web pages generated by remote Markdown files are not tracked in any manner by Google Analytics
* The web service [H5P](https://h5p.org/privacy) is automatically loaded when displaying remote Markdown files
* The open source JavaScript tool [Mermaid](https://mermaid.js.org/) is automatically loaded via [jsDelivr](https://www.jsdelivr.com/terms) when displaying remote Markdown files
* The web service [Hypothes.is](https://web.hypothes.is/privacy/) is only loaded if chosen when displaying remote Markdown files
* The web service [Embed.ly](https://embed.ly/legal/privacy) is only loaded if [Embedly Card](https://embed.ly/cards) elements are present in remote Markdown files

---

### Contact and Support

- Follow [@hibbittsdesign@mastodon.social](https://mastodon.social/@hibbittsdesign) on Mastodon for updates, or subscribe via [RSS feed](https://mastodon.social/@hibbittsdesign.rss)
- 👩🏻‍💻🧑🏻‍💻 Join the [Docsify Discord](https://discord.gg/docsify) and visit the **#Docsify-This** Channel
- Add a ⭐️ [star on GitHub](https://github.com/hibbitts-design/docsify-this) to the Docsify-This project repository

Have you tried out Docsify-This? Share your [feedback about Docsify-This](https://forms.gle/ViYu2ZdPmj6PeQ439)

By leveraging his extensive UX design expertise and systems-oriented approach, Paul helps teams and individuals utilize open content in a range of education and publication settings, especially in connection with his Markdown-based [Docsify](https://docsify.js.org/#/) and [Grav CMS](https://getgrav.org/) open-source projects. Professional services include user experience and workflow consulting, premium support subscriptions, workshops, and custom development.  Sound of interest? Send a note to [paul@hibbittsdesign.org](mailto:paul@hibbittsdesign.org).

---

This [open source project](https://github.com/hibbitts-design/docsify-this) is by Paul Hibbitts of [HibbittsDesign.org](https://hibbittsdesign.org/).  

**🙇🏻‍♂️Special Thanks**  
[Beau Shaw](https://github.com/DaddyWarbucks) for his [Remote Docsify](https://github.com/DaddyWarbucks/remote-docsify) example.  
[Alan Levine](https://github.com/cogdog) for the inspiration of a consolidated ReadMe collection.
