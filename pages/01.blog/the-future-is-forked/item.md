---
title: 'The Future is Forked'
media_order: shane-aldendorff-503944-unsplash.jpg
date: '17:37 07-07-2018'
taxonomy:
    tag:
        - git
hide_git_sync_repo_link: false
hero_classes: 'text-light overlay-dark hero-fullscreen'
hero_image: shane-aldendorff-503944-unsplash.jpg
header_image_credit: 'Photo by Shane Aldendorff on Unsplash'
header_image_creditlink: 'https://unsplash.com/photos/Qd5A9W42L18'
blog_url: /blog
show_sidebar: false
show_breadcrumbs: true
show_pagination: true
hide_from_post_list: false
published: false
---

It's been a while since David Wiley first talked about the reusability paradox which basically posits that the more detailed and localized a particular resource is, the harder it will be for others to use it. And the more a particular resource is designed to be shared, the less useful it will be.
===
The paradox was particularly potent when repositories were filled with copyrighted materials that couldn't be edited. Wiley's solution to the reusability paradox is creative commons licensing which allows every potential user to revise the materials and use them in their own context.

Now, as more people are applying CC licenses to their work, there is a growing awareness that CC materials can be copied, revised, and reused in local contexts. Unfortunately, these materials are too often shared in formats that are next to impossible to revise.

A good example is a PDF. The material may be CC licensed, but since they are displayed in a proprietary format, if someone wants to remix the material, they need to copypasta into their own document before they can make any changes. This may not seem to be onerous as it's just a few taps of the trackpad to make it happen. But what usually happens is that if you copy from pdf and paste into Werd, all of the line breaks from the PDF will be preserved meaning that the user will have to engage in significant formatting work before they can make changes. And if there are fonts that the user doesn't have on their computer, they will be replaced, resulting in further formatting irregularities.

The process gets a little easier if the original file is a Werd file, as that can be edited directly and saved as a copy. But that brings up another difficulty. The second version is completely disconnected from the original. Someone reading the second version will have no idea what the original said, unless the two files are presented together.

It gets more difficult again if the user wants to remix a file but it is in a format that they can't edit at all. Think of a file that might be created in Adobe InDesign or MS Publisher. Since fewer people have access to that software, the materials are even less accessible.

#### A Better Way

Fortunately, we have access to a tool built specifically for sharing and collaborating. The tool uses the simplest kind of word-processing file, a text file. Contrary to Werd and PDF documents, text files don't store any formatting information, there aren't any line breaks or page breaks. Users don't need access to MS Werd to open and edit them, they only need a simple text editor like Notepad or TextEdit. Once the files are in the simplest possible format, anyone can edit them.

But the real brilliance is pairing these simple files with software that allows changes and copies to be tracked. Tracking changes is known as version control, and you may be familiar with it in the context of Google Docs. The Google mothership will keep track of all of your changes and even let multiple people edit a single document and still see all the changes in real time. It's pretty slick and super handy for collaborating.

But what GDocs doesn't do is keep track of *copies* of files. If I copy a file into my own drive, the original and the child are completely cut off from each other. Changes in one file are not merged with the other. And this is where Git comes in.

Git is software that not only tracks changes in individual files, but also tacks changes across different versions of files. So the changes that I make to the file on my computer and the changes that you make to the copy on your computer can be merged into one cohesive file. Not only that, but each of our individual contributions to the final file will be tracked and maintained.

Git tracks changes across different 'branches' of a particular repository of files, and creating one of these branches is called 'forking'. Forking a repository is often a simple as one single tap of a button on a website. This creates a full and complete copy of the repository in your own account of whatever git software you are using (I use GitHub), that always retains its connection to the original repository.

Since Git uses simple text files, forking is super easy, and changes are tracked across versions of a single document as well as across branches, git technology is an ideal vector for OERs to be created and released to the commons for others to exercise their 5R rights (retain, revise, reuse, remix, redistribute).

Happy forking!

<a style="background-color:black;color:white;text-decoration:none;padding:4px 6px;font-family:-apple-system, BlinkMacSystemFont, &quot;San Francisco&quot;, &quot;Helvetica Neue&quot;, Helvetica, Ubuntu, Roboto, Noto, &quot;Segoe UI&quot;, Arial, sans-serif;font-size:12px;font-weight:bold;line-height:1.2;display:inline-block;border-radius:3px" href="https://unsplash.com/@pluyar?utm_medium=referral&amp;utm_campaign=photographer-credit&amp;utm_content=creditBadge" target="_blank" rel="noopener noreferrer" title="Download free do whatever you want high-resolution photos from Shane Aldendorff"><span style="display:inline-block;padding:2px 3px"><svg xmlns="http://www.w3.org/2000/svg" style="height:12px;width:auto;position:relative;vertical-align:middle;top:-1px;fill:white" viewBox="0 0 32 32"><title>unsplash-logo</title><path d="M20.8 18.1c0 2.7-2.2 4.8-4.8 4.8s-4.8-2.1-4.8-4.8c0-2.7 2.2-4.8 4.8-4.8 2.7.1 4.8 2.2 4.8 4.8zm11.2-7.4v14.9c0 2.3-1.9 4.3-4.3 4.3h-23.4c-2.4 0-4.3-1.9-4.3-4.3v-15c0-2.3 1.9-4.3 4.3-4.3h3.7l.8-2.3c.4-1.1 1.7-2 2.9-2h8.6c1.2 0 2.5.9 2.9 2l.8 2.4h3.7c2.4 0 4.3 1.9 4.3 4.3zm-8.6 7.5c0-4.1-3.3-7.5-7.5-7.5-4.1 0-7.5 3.4-7.5 7.5s3.3 7.5 7.5 7.5c4.2-.1 7.5-3.4 7.5-7.5z"></path></svg></span><span style="display:inline-block;padding:2px 3px">Shane Aldendorff</span></a>
