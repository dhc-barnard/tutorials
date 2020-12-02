# Scalar II
*created by Taylor Faires, Alicia Peaker, and Miranda Jones-Davidis*

*updated September 29, 2020 by Ana Lam*

<img align="left" width="75" src="/images/scalar/cc.png" alt="Creative Commons license">

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Introduction to the tool

Scalar is a digital publishing platform that allows creators to juxtapose media and text and create multi-linear pathways through their books or projects. Scalar has robust features out-of-the-box, but it also provides advanced features to creators who want to take their projects to the next level. We'll explore a few of those features in this tutorial.

This tutorial assumes that you have already created a Scalar book that includes content, tags, and paths. If your Scalar book does not have these features, please add them before proceeding. You may want to refer back to the Introduction to Scalar I module or review [Scalar's Quickstart Guides](https://scalar.usc.edu/works/guide2/quickstarts?path=index).

### This tool is great for:
* Dipping your toes in CSS, Javascript, and web design customizations
### This tool is not great for:
* Simultaneous editing of the same Scalar book
* Version control of your custom code (use [Git](https://git-scm.com/) or [GitHub](https://github.com/) for this).

## Materials:
- An account at [scalar.usc.edu](https://scalar.me/anvc/) or your own Scalar install.
- Internet access
- Reliable web browser (preferably Chrome or Firefox)


# Page Versions
Each time a page is saved, Scalar creates a new version of that page. Scalar makes a history of versions, available to all authors, along with metadata about each version and the ability to revert to any version. In Scalar:

<img align="right" width="30%" src="/images/scalar/version.gif" alt="comic of student and professor exchanging 'final'.doc" >

- Versions are accessible to authors.
- You can see when a version was published and who published it.
- You can revert to earlier versions of a page.

So go wild! Experiment! You can always reset later!

# Metadata
Metadata is data about data or, to put it differently, information about an object. Scalar uses metadata to generate interactive visualizations, which we will be creating later. To prepare to use those tools, we’ll need to add some metadata to our objects. 

1. In Scalar, navigate to a media object’s page (the [index](https://scalar.usc.edu/works/guide2/reading-in-scalar?path=getting-started) can be helpful here).
2. In the tabs below the media, click on the “Details” tab to show the current metadata associated with this object. Notice the fields that begin with “dcterms:”—these refer to the Dublin Core metadata schema. 
3. To add more metadata, select the edit icon (pencil) at the top of the page. 
4. Select the “Metadata” tab. Then select “Add additional metadata.”
5. Check the boxes next to “dcterms:spatial” and “dcterms:date.”
6. Add latitude and longitude coordinates to the dcterms:spatial field in the format decimal latitude, decimal longitude. (e.g. Barnard College's would be: 40.8090, -73.9638). 
7. Add date in the dcterms:date field in the format month, day, year, hour, minute, second (e.g. 05-27-2020 08:15:45). If you don't have hour, minute, second data, just enter the date. 

Because of Scalar’s flat ontology (see the [Scalar I Tutorial](https://github.com/dhc-barnard/tutorials/blob/master/scalar/Scalar%20I.md) for a refresher), you can add metadata to nearly any Scalar object—not just media files, but also pages, paths, annotations, etc.

# Visualizing Relationships with Widgets

Now that you've added some rich metadata to your media objects, we'll take some time exploring visualization tools that are built-in to Scalar, beginning with widgets. Widgets are mini-tools that usually have a single function. In Scalar, widgets allow you to embed visualizations or other handy features like a media carousel within a page.

## Card and Summary Widgets
Similar to inserting media, you can insert a widget either inline or as a link. Let's add an inline widget. 

<p align="center">
  <img width="60%" src="/images/scalar/inlinewidget.png" alt="Screen grab of the widget selections" >
</p>

1. Navigate to your page editor (pencil icon).
2. Click the puzzle piece with the lines around it. You will encounter a pop-up asking you to select a widget.
3. Click on either Card or Summary and select the pages you would like to add. Then click "continue."
4. Follow Scalar's prompts to order and style your selections.
5. Once you've finished, save and view to see what you've done!

### Bonus: Adding a thumbnail to your widget
By default, Card and Summary widgets primarily display text. To make your widgets more engaging, you can add a thumbnail.
1. Click edit on a page you are using within a widget (NOT the page where the widget is embedded).
2. Near the bottom of the page, select the "Styling" drop-down and then "Thumbnail."
3. Select the image you would like to serve as a thumbnail for this page. 
4. Save and view the page.
5. Finally, return to the page where your widget is embedded. You should now see a thumbnail in your widget.

Card widget | Summary widget
--------- | --------
![card widget](/images/scalar/cardwidget.png) | ![summary widget](/images/scalar/summarywidget.png)
*Example of a Card widget (first card/page in widget has a thumbnail but the second does note* | *Example of a Summary widget (first page in widget box does not have a thumbnail but the second does).

## Carousel Widget
The Carousel widget functions like a gallery for a reader to flip through images or links. The process for adding the Carousel Widget is similar to the Summary or Card widget. The Carousel works best with images so instead of selecting pages when prompted, select media. Try it now, adapting the instructions in the "Card and Summary Widget" section as needed.

## Map Widget
Another way to display information visually with Scalar is to use its Map widget or Map layout. In this section, you'll add a map widget to a page. The Map widget will use the spatial metadata you created earlier in the module.

1. Once you've added spatial metadata to all the content you want to include in your map, create a new page (or edit an existing page).
2. To add a Map widget, click on either the linked or inline widget button in the page editor and then choose “Map” from the widget options.
3. Next, use the content selector to choose an item or selection of items to be plotted on the map. You can choose items individually, or you can choose already-created paths and tags and then tick the box under "Include Children" in the content selector to include all the items in the path or tag. 
4. You can then change formatting options for the map. You can include descriptive text below the widget by choosing "Custom text" under "Caption" and entering text there. 
5. Once you have inserted the widget, save the page, and explore you new map!

## Visualization Widget
It can be difficult to hold all of the relationships you've created in Scalar in your mind. Scalar provides some handy visualization tools that abstract those relationships and allow you to explore your content in new ways.

Let's start by visualizing tags through a force-directed graph (also known as a network graph). 


<img align="right" width="50%" src="/images/scalar/visualization.png" alt="Screen grab of the visualized paths by tags">

1. Create a new page or edit a page where you'd like to embed a visualization. 
2. To add a Visualization widget, click on either the linked or inline widget button in the page editor and then choose “Visualization” from the widget options.
3. Select the first drop-down menu and choose "All tags."
4. In the second drop-down menu, choose "All relationships."
5. In the final drop-down menu, choose "force-directed." 
6. Then select "Continue."
7. You may update the next screen of options as you'd like or leave them as they are.
8. Once you have inserted the widget, select "Save and View" at the bottom of the page.
9. Explore and interact with the visualization (a full screen view might help). Notice the different colors and the legend that explains what they are.

Different kinds of visualizations are useful for different kinds of information and relationships. To visualize your paths, which are more linear than tags, follow the above steps except when inserting the widget select:

1. "All paths" in the first drop-down menu.
2. "All relationships" in the second drop-down menu.
3. And "Tree" for the final drop-down menu.

Take a few moments to continue exploring visualizations! 

# Using Page Layouts

We used the layout tab of the page editor in the [Scalar I tutorial](https://github.com/dhc-barnard/tutorials/blob/master/scalar/Scalar%20I.md) to make a cover for your book, but there are other layouts available. For the purposes of this guided practice, here are a few that we've found most useful.

## Timeline Layout
One way to display media and metadata visually on Scalar is to use its Timeline layout or Timeline widget.  In this section, you'll use the Timeline layout.

1. The Timeline layout will use the metadata you created earlier in the module to display objects chronologically.
2. The Timeline layout will also display the object's description and associated thumbnail. While on an object's page editor (pencil icon):
   - To add a description: enter your text into the description field in the page editor.
   - To add a thumbnail: click on "Styling" and choose "Thumbnail" from the dropdown menu, then select an image from your media library or from an external url and click "save." 
3. Once you've added temporal metadata to all the content you want to include in your timeline, create a new page (or edit an existing page).
4. Select the "Relationships" tab and select either "tag" or "path." We'll use "tag" as our example, but they work the same.
5. Next click "To make this page a tag, choose the items that it tags" and select the items you have added temporal metadata to. 
6. Under the "Layout" tab, set the current page to the Timeline layout via the drop-down menu.

## Media Gallery Layout


<p align="center">
  <img  width="50%" src="/images/scalar/mediagallery.png" alt="Screen grab of the slide show like media gallery">
</p>

If you're working with a particularly media-heavy page and want to showcase that media, try the Media Gallery layout, which puts all media embedded on a page into a carousel at the top of the page. This layout gives you less flexibility than the Carousel widget (which lets you select which media to include and where to place the carousel).

## Visual Path Layout

The Visual Path (originally [developed](http://aliciapeaker.org/?p=445) by our own Alicia Peaker) creates a scrolling, visual version of each page along a path. In the example below, from Taylor's project, the introduction of the book is followed by three sections meant to stand in for a literature review. The "continue" button allows for readers to choose where in the path they want to go next.

1. To use the Visual Path, first make sure your page is a path or create a new page. 
2. Edit the page. 
3. Under the "Layout" tab, set the current page to the Visual path layout via the drop-down menu.
4. The images on the visual path are the key images for each individual page, so if you want images to show up, you need to add those to each page.
   - To add key images, edit each page on your path. Under the "Styling" tab, select "key image," and then select an image. 

<p align="center">
  <img width="80%"  src="/images/scalar/visualpath.png" alt="Screen grab of visual path where key images indicate pages">
</p>

# Design Features

So far, we've been working primarily with arranging and displaying the contents of your Scalar book. We're going to take a  step back and add some design and other elements that will apply to the entire book. 

## Adding a background, book thumbnail, and table of contents

1. Go to your dashboard (wrench icon)
2. Select the "Book Properties" tab.
3. Add a table of contents for your book.
4. Add a background to your book
5. Add a thumbnail to represent your book in Scalar's indexes (also useful for when you are managing multiple books)
6. Save!
7. View your changes by selecting "back to book" in the upper right-hand corner of the page. NOTE: The table of contents is visible when you hover over the hamburger icon (three lines on top of each other) at the top left of the page.

## Creating a book cover

For instruction on how to create a dynamic book cover, see the [Scalar I tutorial](https://github.com/dhc-barnard/tutorials/blob/master/scalar/Scalar%20I.md).

## Making your book a template

You can make your Scalar book a duplicable template. This might be useful if you teach a course regularly and want each course to have its own Scalar book but with some shared features. Or perhaps you want to set a structure and have your students duplicate your book and then elaborate on your template.

To make your book duplicable:

1. Go to your dashboard (wrench icon) if you aren't already there.
2. Select the "Sharing" tab.
3. In the "Duplicability" section, select "Yes" in the drop-down.


<p align="center">
  <img  src="/images/scalar/duplicability.png" alt="Screen grab of duplicability security selection >
</p>

That's it! Now to create a new book from this template:

1. On your dashboard, select the "My Account" tab.
2. Next to "Create a new book" select the checkbox to make this a "Duplicate of another book." 
3. A pop-up will appear with an alphabetical list of all the books on Scalar's server that are duplicable. Scroll to find your book.
4. Select it and give your book a title.
5. Complete the recaptcha security check and click "create."

# Optional: Custom Design

At the beginning of this tutorial, we used a meme of an iceberg to indicate that Scalar has hidden depths. For advanced or adventurous users, Scalar allows authors to add Javascript and CSS (Cascading Style Sheet) at both the global level (i.e. applies to whole book) or page level (i.e. applies only to a single page). This is a wonderful feature for folks who know or would like to learn about web design without having to build an entire application from scratch. 

## CSS Snippets

Scalar has some built-in CSS "snippets" you can add to your book.  Each snippet is a line or more of code that has a specific function. Currently, those snippets include code to: 

- Keep linked media with their source paragraphs
- Show path contents in sidebar
- Don't crop splash images on phones
- Hide path navigation arrow buttons
- Text content area to full width
- Display description below title

To add a snippet to your book:

1. Go to your dashboard (wrench icon) and make sure your book is selected in the top-left drop-down menu.
2. Select the tab "Book Properties"
3. Under the first large text box, click on the drop-down menu to "Insert CSS."
4. Select a snippet of your choice, and click "Insert."
5. Above you will see the style language (i.e. CSS) that will change the appearance of your book. 
   - Look at the syntax of the code that's been added. What makes sense? What can you infer from the code? What remains opaque? Try inserting a few snippets to see what you can learn from them.
6. Click "Save" at the bottom of the page.
7. Explore your book to see the change in action!

## Add your own CSS

In the same section where we added CSS code snippets, you can add your own CSS to change the appearance of your Scalar book. Let's change the color of page titles. 

1. Go to your dashboard (wrench icon) and make sure your book is selected in the top-left drop-down menu.
2. Select the tab "Book Properties"
3. In the CSS text box, copy and paste:
    - `h1[property="dcterms:title"]{ color: #008080;}`
4. Save and view!
5. The ` #008080` is a hex code for the color teal. Try replacing it with another hex color code or with the name of a common color (e.g. `blue`, `purple`, etc.)
6. Then save and view! 
7. Explore and see what else you can change. View [Scalar's guide](https://scalar.usc.edu/works/guide2/customizing-look-and-feel-with-css?path=advanced-topics) for other features you may want to style with CSS.

# Reflection

-  Throughout this module, you explored several methods of visualizing the contents of your Scalar book. How did the visualization tools force you to think differently about the relationships among your content? 
- What limitations and affordances did you encounter or do you imagine in using Scalar for a particular purpose (making an argument, telling a story, or any other purpose you have)? How did you confront the space between your desires for the book and what the tools allowed?

# Resources
##  Examples of succesful projects:
- [Women of the Early Harlem Renaissance](https://scalar.lehigh.edu/harlemwomen/index)
- [Black Quotidian](http://blackquotidian.supdigital.org/bq/index)
- [The Girl The Myth, The Fanfiction](https://taylorfaires.com/scalar/the-girl-the-myth-the-fanfiction)

## Syllabi/Assignments using this tool:
- [Digital Diversity](https://hcommons.org/deposits/item/hc:20443/)
- [Technologies of Literary Production](https://hcommons.org/deposits/item/hc:10329/)

## Other Guides & Tutorials:
- [Customizing Look and Feel With CSS](https://scalar.usc.edu/works/guide2/customizing-look-and-feel-with-css?path=advanced-topics)
- [Working with Widgets](https://scalar.usc.edu/works/guide2/working-with-widgets)
- [Working with Structure](https://scalar.usc.edu/works/guide2/working-with-structure)

## Barnard Resources:
- Barnard faculty, staff, and students are free to reach out to the [DHC](https://digitalhumanities.barnard.edu/) for additional help!                                                           
