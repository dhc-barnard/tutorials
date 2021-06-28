# WordPress Basics
*created by Ana Lam*

You can also watch the [video version](https://vimeo.com/478548461) of this guide.

## Introduction to the tool

WordPress is a free and open source content management system. More than 30% of the top 10 million websites use WordPress. Though it started as a simple blog posting site, WordPress now offers various widgets, plugins, and themes for website creation.

## Materials:
- Internet access
- WordPress installation and login information

## This tool is great for:
- Creating a dynamic site with posts and media objects (images, videos, audio, etc.)
- Showcasing course content to a public audience
- Engaging the public in dialogue through post comments

## The tool is not great for:
- Finalized and static digital projects (WordPress sites require maintenance often times)
- Publishing sensitive or private content (there are options to create private password protected WordPress pages)

# Guided Practice
## Step 1: Getting Started

### Log In

Now, to access the content management side of your course website, visit your domain/homepage’s url followed by `/wp-admin.` You will land on this login page. You can login with your username and password. If you are an added user see the section on [Adding Users](#Adding-Users) on obtaining login information.

<img align="center" width="400" src="/images/wordpress/1-login.png" alt="Log In page for WordPress course website">

### Back-End vs. Front-End

After logging in through `/wp-admin`, you will land on the back-end’s administration dashboard which should look similar to this:

<p align="center">
  <img src="/images/wordpress/2-backend.png" width="600" alt="Back-end Admin Dashboard of WordPress">
</p>

<p align="center">
<i>At the info bar across the top you will see your website name (links to site) and your user name (links to profile).</i>
</p>

The back-end page has a dashboard displaying a summary of the activity and content of your website. The sidebar on the left allows you to produce and manage content. Clicking the website title in the upper right corner allows you to switch to the front-end of the website which appears as so:

<p align="center">
  <img src="/images/wordpress/3-frontend.png" width="600" alt="Front-end Admin Dashboard of WordPress">
  </br>
  <i>This is the front end of the website. Here you can see the website display and add content using the “+ New” menu tab on the top bar.</i>
</p>

Many people prefer to work through the front-end of WordPress. Though the back-end of WordPress offers many tools and setting controls, with the front-end you can focus more readily on content creation.

### Adding Users

<img align="right" width="300" src="/images/wordpress/12-adding-users.png" alt="Add New User page on WordPress">


If you are an administrator of your WordPress website, you can add users. To add users to the site, simply navigate to the User's tab in the navigation bar on the back-end of your WordPress website. Here there will be a summary of users and their roles. Add a new user by filling out the information asked by the "Add New User" page. You can decide on the role of each new user. Here is a summary of the privileges that come with each role:

- **Subscriber** - can only manage their profile
- **Contributor** - can write and manage their own posts but cannot publish them
- **Author** - can publish and manage their own posts
- **Editor** - can publish and manage posts including posts by other users
- **Administrator** - has access to all administration features of the site

Invited users can find their login information in the new user invitation. Invited users receive a new user invitation from the WordPress website (e.g. `wordpress@websitename.com`) to their email. After resetting the password, users will be able to login to the course website with their email address and password.

An important feature to note concerning privacy is that on one’s user profile you have the option to establish a pseudonym. Navigating to your “Profile” in the “Users” tab, you can create a nickname and use it as your display name. This display name will be used in your authoring information when you publish posts. Other users will, however, still see your identifying information in the registered username and email address.

<p align="center">
  <img src="/images/wordpress/13-pseudonym.png" width="600" alt="Adding a user with a pseudonym in WordPress">
  </br>
  <i>For this user, when creating posts, the author name will be displayed as ‘hypatia.’</i>
</p>

## Step 2: Creating a Post

One of the most popular functions of WordPress is its posts, which are very similar to blog posts. WordPress posts are organized by most recent posts. You can assign posts to categories and add tags to your posts for organization.

### Creating a New Post

To create a post through the front-end you can simply select the “+ New" menu tab on the top bar. To create a post through the back-end, hover over the “Posts” button on the sidebar and select “Add New.”

<table align="center"><tr>
<td>
  <p align="center" style="padding: 10px">
    <img src="/images/wordpress/4-postsbackend.png" alt="create a post back-end" width="250">
    <br>
    <em>Create a post via Back-end</em>
  </p>
</td>
<td>
  <p align="center">
    <img alt="Routing" src="/images/wordpress/5-postsfrontend.png" alt="create a post front-end" width="315">
    <br>
    <em>Create a post via Front-end</em>
  </p>
</td>
</tr></table>

After initiating a new post, you are taken to WordPress’ block editor. This editor helps you create and manage text and media content. For posts, the block editor consists of sections for your post’s title and content (text, image, video, headers, etc.). You can add content such as text by clicking the “+” sign buttons either in the top navigation bar or in the block editor.


<p align="center">
  <img src="/images/wordpress/6-blockeditor.png" width="600" alt="Display of WordPress visual block editor">
  </br><i>WordPress visual block editor to create a post.</i>
</p>

You can also switch from the visual editor to an HTML editor by clicking the vertical ellipsis symbol on the upper right corner of your display. With the HTML editor you can edit the HTML of the post.

<p align="center">
  <img src="/images/wordpress/7-blockeditor.png" width="600" alt="Display of WordPress code editor">
  </br><i>If you are comfortable writing in HTML, you can further customize your post with the WordPress code editor. The code editor doesn’t render the website style.</i>
</p>

<img align="right" width="200" src="/images/wordpress/11-addmedia.png" alt="Add media tab of WordPress Post Block Editor">

### Adding Media
#### Images

You can add a variety of content with the block editor including images, slideshows, audio, videos, etc.


When adding images you have the option to upload an image, select an image from the media library, or insert an image URL. Images uploaded will automatically be added to the media library. However, when uploading images found from the internet, it is important to note that uploading a copy of an image from the internet disconnects the image from its original context and metadata. In addition, uploading a copy of an image adds to the carbon footprint of the server storing it. When possible, it is a greener practice to simply insert an image URL, which you can find by right clicking or control clicking and copying the link address. Note, however, that if the image is removed from the original site, it will no longer be visible on your site either and the alt text will appear instead.

When adding an image to the site, it is also necessary to add alt text. In the alt text you should describe the function of the image to increase the accessibility of your content. The alt text will appear in the case that the image is not able to load and helps screen-reading tools that describe the image to visually impaired users.

</br>
<p align="center">
  <img src="/images/wordpress/9-alttext.png" width="600" alt="Display of how to add alt text for images">
  </br><i>The alt text can be added through the image settings that pop up as a sidebar when you add an image to your post.</i>
</p>

Your image appears in this content box along with space for a caption. You can choose how to align it in the editing options that appear as a bar hovering over the image. To resize the image, hover your cursor over the blue dots along the edges of the image. Dragging these dots allows you to resize the width and height of your image without warping its proportions.

#### Video & Audio

Inserting video and audio to your post is very similar. Either upload a mp3/mp4 file or insert the URL to the video/audio.

#### Links

Links can easily be inserted in the text of a post by highlighting the words or names that will hold the link and clicking the link symbol that appears on the bar with paragraph editing tools.

<p align="center">
  <img src="/images/wordpress/14-links.png" width="400" alt="Display of how to add links to blog posts">
</p>

### Post Settings

You can toggle the post settings by selecting the gear button at the upper right corner of the display. The following list describes the post settings tabs:

- **Status & Visibility** - Here you can decide the visibility of your post and when it publishes. You can also select an author (automatically assigns your user account).
- **Permalink** - Lists the URL of your post.
- **Categories** - You can select the category for your post to fall under.
- **Tags** - Add and select tags for your post.
- **Featured Image** - Add and select the featured image that appears on your post’s preview.
- **Excerpt** - Text that appears on your post’s preview
- **Discussion** - Edit audience interaction settings such as allowing comments.
- **Post Attribute** - Change post template from default template.

### Categories & Tags

Categories and Tags are useful ways to organize posts. Categories are useful for organizing by broader themes or genres, such as books, films, etc. Tags speak more specifically to a post and are more useful in highlighting keywords and more detailed themes featured in posts, such as drama, horror, etc.

<p align="center">
  <img src="/images/wordpress/10-tags.png" width="600" alt="Display of how to add tags on post">
  </br><i>Tags can be added in the post settings. You can add multiple tags by separating each with a comma or using the Enter key.</i>
</p>

As an author you can create new tags in the document settings sidebar toggled by the gears on the top bar. You can also select which category you want your post to fall under.

## Saving & Publishing your Post

In the same top bar you have the option to save a draft of your post, preview your post, or publish your post. Once you publish your post it will become public based on your document’s visibility settings.

# WordPress Advanced options

## Themes

A WordPress theme is a ready-to-go design for your website. To change your website's theme, navigate to the “Appearance” tab in the navigation bar and select “Themes.” Here you can view installed themes and activate one for your site. In the case that you want to add a new theme, you can add it in this same tab depending on your user role and its permissions. Site administrators can install new themes. When picking a theme, you have the option to filter through available themes based on your site considerations. It is great practice to build sites that prioritize accessibility. You can filter by accessibility ready themes. These themes adhere to accessibility practices such as high color contrast, keyboard navigation for all links and controls, and more. After selecting a theme, go ahead and activate it.

<p align="center">
  <img src="/images/wordpress/15-themes.png" width="600" alt="Display of how to add themes to WordPress site">
  </br><i>You can do minimal customizations on a theme by selecting “Customize” on your active theme.</i>
</p>

## Plugins

One of the most attractive features of WordPress is the thousands of free and open source plugins that can be integrated into your site. A plugin is a bit of packaged code that adds features to your website. You can see currently installed plugins in the "Plugin" tab on the back-end admin area of WordPress. Here you can also activate and deactivate installed plugins. Site administrators can install additional plugins. Simply navigate to "Add New" in the "Plugins" tab to be taken to a WordPress plugin directory. You can search and view details of all free and commercial plugins and install those of interest to you.

When selecting plugins, pay attention to when the plugin was last updated and how many people are using it. Some plugins in the directory may be several years old and may not work with your version of WordPress, or may not be actively maintained.

<p align="center">
  <img src="/images/wordpress/16-plugins.png" width="600" alt="Display of how to add plugins to WordPress site">
  </br><i> You can install additional plugins as site administrator in "Add New"  of the "Plugin" tab via the back-end.</i>
</p>

## Hosting

One of the most attractive features of WordPress is the thousands of free and open source plugins that can be integrated into your site. A plugin is a bit of packaged code that adds features to your website. You can see currently installed plugins in the "Plugin" tab on the back-end admin area of WordPress. Here you can also activate and deactivate installed plugins. Site administrators can install additional plugins. Simply navigate to "Add New" in the "Plugins" tab to be taken to a WordPress plugin directory. You can search and view details of all free and commercial plugins and install those of interest to you.

When selecting plugins, pay attention to when the plugin was last updated and how many people are using it. Some plugins in the directory may be several years old and may not work with your version of WordPress, or may not be actively maintained.

### [EdBlogs](https://edblogs.columbia.edu/)

You can obtain a website for a course using Columbia’s Center for Teaching and Learning EdBlog WordPress system. EdBlogs can only be set up for the purpose of courses. Additionally, EdBlogs comes with preinstalled themes and preinstalled plugins selected with teaching and learning in mind. Though the default for EdBlogs is that the professor is Administrator of the private site with students with UNIs as Authors, EdBlogs can be made public and welcome comments from site visitors.

You can easily and freely request an EdBlog from CTL using the [Get an EdBlog](https://www1.columbia.edu/sec/ccnmtl/remote/edblogs_request/) form.

### [CUIT Blogs](https://blogs.cuit.columbia.edu/)

If you seek to use WordPress for purposes other than course blogs, CUIT establishes administrative, research, or individual use blogs. To create a personal blog, simply log in to [CUIT Blogs](https://cas.columbia.edu/cas/login?service=cuit-blogs&destination=https%3A%2F%2Fblogs.cuit.columbia.edu%2Fwp-login.php%3Fref%3D%252F) using your UNI and password. To create a collaborative website, you will need to send an email to `cu-blogs-admin@columbia.edu` upon requesting a blog from the login prompt. Like with EdBlogs, the themes and plugins you can install are limited.

### Milstein Centers: IMATS & DHC

Barnard IMATS and DHC both provide technical and instructional support for WordPress site needs that can't be met by EdBlogs or CUIT Blogs. Contact an IMATS specialist at imats@barnard.edu or a DHC staff member at digitalhumanities@barnard.edu to learn more.

### [Reclaim Hosting](https://reclaimhosting.com/)

If you would prefer total control over your site, or would like to learn more about hosting your own website, one great hosting option is Reclaim Hosting. Reclaim Hosting values user ownership and control for those interested in web hosting and is low-cost. With Reclaim Hosting you have full control over customizing your domain name (URL), pending its availability, and access to software for website building, such as WordPress, Omeka, Scalar, and Drupal. If you already have a domain, you can migrate it over to Reclaim Hosting.

The Reclaim Hosting platform uses a cPanel Dashboard for user interaction. On the cPanel you can view applications, domains, file management, and more.

To access WordPress through your Reclaim Hosting account, simply select WordPress from the Applications tab in the cPanel. Click “Install this application” to begin setting up a new WordPress site on your domain. You can choose the new site to be the main domain or subdomain by indicating the installation location. Choose a username and password for the site as well as site features. Once WordPress is installed, you can access the WordPress site through the admin link which would appear as `[websitename]/wp-admin/`.

# Reflection

- How does the capacity of posts to hold various media, interaction, and visibility options change the way you think about writing and publishing? Especially when weighing digital accessibility and privacy?

- What new considerations do you have when writing for the web?

# Resources:

Here are comprehensive guides and documentation on using WordPress:
- [WordPress.org Documentation](https://wordpress.org/support/)
- [Harvard Law School WordPress Student User Guide](https://hls.harvard.edu/dept/dos/student-orgs/wordpress-student-user-guide/)
- [Beginner’s Guide for WordPress: How to Add a New Post Guide](https://www.wpbeginner.com/beginners-guide/how-to-add-a-new-post-in-wordpress-and-utilize-all-the-features/)

# Barnard Resources:
- Barnard faculty, staff, and students are free to reach out to the [DHC](https://digitalhumanities.barnard.edu/) for additional help!
