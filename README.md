@@ -1,63 +1,68 @@
<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.

-->

# Communicate using Markdown

_Organize ideas and collaborate using Markdown, a lightweight language for text formatting._
_Organize ideas and collaborate using Markdow._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  <<< Author notes: Step 1 >>>
  HEllo world 
  easy words 
  linked 
  Encourage users to open new tabs for steps! ok
-->

## Welcome
## Step 1: Add headers

GitHub is about more than code. It’s a platform for software collaboration, and Markdown is one of the most important ways developers can make their communication clear and organized in issues and pull requests. This course will walk you through creating and using headings more effectively, organizing thoughts in bulleted lists, and showing how much work you’ve completed with checklists. You can even use Markdown to add some depth to your work with the help of emoji, images, and links.
_Welcome to "Communicate using Markdown"! :wave:_

- **Who is this for**: New developers, new GitHub users, and students.
- **What you'll learn**: Use Markdown to add lists, images, and links in a comment or text file.
- **What you'll build**: We'll update a plain text file and add Markdown formatting, and you can use this file to start your own GitHub Pages site.
- **Prerequisites**: In this course you will work with pull requests as well as edit files. If these things aren't familiar to you, we recommend you take the [Introduction to GitHub](https://github.com/skills/introduction-to-github) course, first!
- **How long**: This course takes less than one hour to complete.
# This is an `<h1>` header, which is the largest

In this course, you will:
## This is an `<h2>` header

1. Add headers
2. Add an image
3. Add a code example
4. Make a task list
5. Merge your pull request
###### This is an `<h6>` header, which is the smallest
**What is _Markdown_?** Markdown is a [lightweight syntax](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for communicating on GitHub. You can format text to add a heading, lists, **bold**, _italics_, tables, and many other stylings. You can use Markdown in most places around GitHub:

### How to start this course
- Comments on [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), and [discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Files with the `.md` or `.markdown` extension
- Sharing snippets of text in [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'communicate-using-markdown',
  owner: '@me',
  name: 'skills-communicate-using-markdown',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->
**What is a _header_?** A header is a larger bit of text at the beginning of a section. There are six sizes. 

### Example

# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest

#### How it looks

# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=communicate-using-markdown&owner=%40me&name=skills-communicate-using-markdown&description=My+clone+repository&visibility=public)
### :keyboard: Activity: Edit your file with headers

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.
1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Open the **pull requests** tab.
1. Click **New pull request**, for the branches to compare, select `base: main` and `compare: start-markdown`.
1. Click **Create pull request**.
1. In this pull request, go to the **Files changed** tab. We made an empty file `index.md` for you.
1. Select **Edit file** from the three dotted **...** menu in the upper right corner of the file view on `index.md`.
1. On the **Edit file** tab, add a `#`, followed by a **space**, before any content you like to make it an H1 Header. You can add more headers, using one to six `#` characters followed by a **space**.
1. Above your new content, click **Preview**.
1. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file.
1. Click **Commit changes**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

 7 changes: 7 additions & 0 deletions 7  
index.md
 Viewed
 
# ,
# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest
# header 2 ,
# This is an <h1> header, which is the largest ,

# This is an <h2> header , 

# This is an <h6> header, which is the smallest ,

# ⌨️ Activity: Edit your file with headers ,

# Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab. ,
# Open the pull requests tab.
# Click New pull request, for the branches to compare, select base: main and compare: start-markdown. ,
# Click Create pull request. ,
# In this pull request, go to the Files changed tab. We made an empty file index.md for you. ,
# Select Edit file from the three dotted ... menu in the upper right corner of the file view on index.md. ,
# On the Edit file tab, add a #, followed by a space, before any content you like to make it an H1 Header. You can add more headers, using one to six # characters followed by a space. ,
# Above your new content, click Preview. ,
# At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. ,
# Click Commit changes. ,
# Wait about 20 seconds then refresh this page (the one you're following instructions from). GitHub Actions will automatically update to the next step. ,
