---
title: Github way
sidebar: contribute
---


## Prerequisites
1. Make a [GitHub account](https://github.com/join).

## Contribution process
The process of contribution via GitHub is sketched below. 

{% include image.html file="github_way_flow.svg" alt="Process of contributing via GitHub" click=true %}

The steps to be followed by contributors are detailed below.

### Announce and discuss your proposal through GitHub "issues"
1. Go to the [RDM toolkit repo](https://github.com/elixir-europe/rdm-toolkit) on Github.
2. Click on "Issues" in the top menu bar and check existing issues to see if your idea or suggestion is already being addressed.
  * If yes, add your comments to the existing issue.
  * If not, create a new issue by clicking on the green "New issue" on the right.
    {% include image.html file="new_issue_github.png" inline=true alt="Open new issue on GitHub." %}
3. Choose one of the issues template and create a new issue. More information on creating issues can be found [here](https://docs.github.com/en/github/managing-your-work-on-github/creating-an-issue).
  * Report a bug.
  * Fixing an existing page or add tool/resource
  * Add a new topic as a new page.
  * General Discussion.
4. Discuss your idea with the editors through comments in the issues. You will be notified when others comment on your issues. Read the comments and write your opinion/questions/answers on "Leave a comment" box and click on the green "comment" button on the right.

### Write your content

1. When you and the editors have agreed on the type of contribution, you can go to the page you want to edit on the website and click on "Edit me" pencil icon :pencil:, shown next to the page title. OR if you were looking to add new content and require a new page,the editors will provide you the link to the page via comments in the issue you created. The page will come with a predefined template based on the kind of content you want to contribute.
2. The "Edit me" pencil icon will take you to the GitHub repository where you again click on the pencil icon, shown on the right and start editing. 
    {% include image.html file="raw_github.png" inline=true alt="Editing a page on GitHub" %}
3. You can now edit or add new text and images according to the provided template. GitHub provide a guide for writing and formatting in GitHub which can be found [here](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github). We also provide a [markdown cheat sheet](markdown_cheat_sheet) to show you how to write in this webpage. Make sure to read our [style guide](style_guide) before start writing.
4. When you are happy with your first draft of the content, go to the “Propose changes” section at the end of the page and write a title and a brief explanation about your changes.
5. Click on “Propose changes”. 
    {% include image.html file="propose_changes_github.png" inline=true alt="Propose changes on GitHub" %}
6. You are now redirected on the Pull Request (PR) page. By clicking on the Create Pull Request green button you are redirected to Open Pull Request page and from there you can choose to
  * open a "[Draft Pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests#draft-pull-requests)”, if you are not yet done writing. Later on you can always click on "Ready for review" to switch towards a normal pull request.
              **OR**
  * open a "Pull Request", if you are confident about your contribution. In this case the editors will be assigned which are responsible for the sections you will add page to or change the content.
    {% include image.html file="draft_pullrequest_github.png" inline=true alt="PrDraft pull request on GitHub" %}

7. In the description of your pull request it is possible to link the issue that covers this change by typing a hashtag `#` and the correct issue number. Suggestions will appear. This way it is easy for the editors to link back the issue were this change might be discussed beforehand.
    {% include image.html file="linking_issues_github.png" inline=true alt="Linking issues in a pull request on GitHub" %}

8. If you had changed your mind about something in your Pull Request (PR), when the PR is not yet closed, or if the editor tells you to edit your PR during the review process, you have to:
  * Go to the [RDM toolkit repo](https://elixir-europe.github.io/rdm-toolkit/) on Github.
  * Click on the “Pull request” button in the top menu bar.
  * Find your open PR and click on it.
  * Click on "Files changed" in the top menu bar.
      {% include image.html file="files_changed_github.png" inline=true alt="Files changed tab on GitHub" %}
  * Click on the icon with 3 dots "..." of the file you  want to edit and then click on "Edit file".
      {% include image.html file="3_dots_github.png" inline=true alt="File change options on GitHub" %}
  * Make your changes.
  * Click on “Commit changes”.

{% include note.html content="Anyone can [comment on your issue or pull Request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request) and you can reply." %}

### Request a review
1. Go to the [RDM toolkit repo](https://github.com/elixir-europe/rdm-toolkit) on Github.
2. Click on the “Pull request” button in the top menu bar.
3. Find your open PR and click on "[Ready for review](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/changing-the-stage-of-a-pull-request#marking-a-pull-request-as-ready-for-review)". Editors will be notified and they will check your changes.

### Address editors' comments
1. When editors add [comments](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/commenting-on-a-pull-request) or [start a review](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/reviewing-proposed-changes-in-a-pull-request) of your PR, you will be notified.
2. You need to address editors' comments and requests by editing your PR as in step 7 (see above).
  * Go to the [RDM toolkit repo](https://github.com/elixir-europe/rdm-toolkit) on Github.
  * Click on the “Pull request” button in the top menu bar.
  * Find your open PR and click on it.
  * Click on "Files changed" in the top menu bar.
      {% include image.html file="files_changed_github.png" inline=true alt="Files changed tab on GitHub" %}
  * Click on the icon with 3 dots "..." of the file you  want to edit and then click on "Edit file".
      {% include image.html file="3_dots_github.png" inline=true alt="File change options on GitHub" %}
  * Make your changes.
  * Click on “Commit changes”.
3. When all the requests have been addressed, the editors will mark the conversation as "Resolved" and the proposed changes as "Approved".
4. You content is ready to be merged and published in the main website.
5. Editors publish your content.
