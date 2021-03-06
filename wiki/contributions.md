---
title: Contributions
permalink: "/:basename"
layout: git-wiki-default
---

# How to contribute to this wiki

### Create a github account and join the NBMG organization
1. Create a github user account at (github.com)[github.com]
2. Once you have done so, send an email to eodean@unr.edu with your github username.
3. You will then receive an invite to join the "wiki-collaborators" group within the NBMG github organization. Once you have accepted the invite, you can then contribute.

If you want to contribute but do not want to make a github account, you can send text that you want included in the wiki to eodean@unr.edu.

### How to edit content
1. From the page that you wish to edit, click "Edit" in the top right corner.
2. Edit the page in markdown. You can also click the "preview changes" tab to see how your page will look before committing your changes.
3. Once you are finished, add a title and a description of your changes. (e.g. title - "editing wiki". description - "removed text about editing a wiki from the 'add content' section, created a new 'edit content' section")
4. Make sure "Commit directly to the `master` branch" is selected.
5. Press the green "Commit changes" button.

### How to add content (after creating a github account)
1. Go to nbmg-unr.github.io
2. Click "Add new post."
3. This will take you to an editor window on github. Add a file name at the top of the post (no spaces, ex. "test_post.md"). All names must end with the "md" description.
4. Type your content in to the box. All of the content needs to be written in (markdown)[https://www.markdownguide.org/getting-started/]. If you already have a word document that you'd like to post, you can use a (word to markdown converter)[https://word2md.com/].
5. Click on the "preview" tab to make sure the content looks how you want it to look.
6. Add a "commit message" - a description of the content that you are posting.
7. Choose the "commit directly to master branch" option, then press "commit new file."
8. To add your new file to the table of contents, you may directly edit the sidebar.html file (https://github.com/NBMG-UNR/NBMG-UNR.github.io/blob/master/_includes/nav/sidebar.html - click on the pencil icon to edit) and add your post under the appropriate section using html. The structure should be as follows:

`<li><a href="{{ '/your_file_name_here.html' | relative_url }}">Your title here</a></li>`

Note that the extension in this link says "html" instead of md.

Alternatively, you can email eodean@unr.edu and ask that a link be added for your file.
