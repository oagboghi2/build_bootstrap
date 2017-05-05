# build_bootstrap

<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Droid+Sans" rel="stylesheet">
<link rel = "stylesheet" href = "css/typography.css">
<link rel = "stylesheet" href = "css/buttons.css">

<title>Shoelace Frame</title>
</head>
<body>
  <div class = 'menu'>a
    <hr>
    <h4 style = 'font-family:cursive;'>shoeLace</h4>
    <hr>
    <ol>
      <li><a href = "#headings">Headings</a></li>
      <li><a href = "#bodyCopy">Body Copy</a></li>
      <li><a href = "#addresses">Address</a></li>
      <li><a href = "#blockQuotes">Blockquotes</a></li>
      <li><a href = "#pagination">Pagination</a></li>
      <li><a href = "#label">Label</a></li>
      <li><a href = "#badges">Badges</a></li>
      <li><a href = "#jumbotron">Jumbotron</a></li>
      <li><a href = "#buttons">Buttons</a></li>
      <li><a href = "#breadcrumbs">Breadcrumbs</a></li>
      <li><a href = "#pageHeader">Page Header</a></li>
      <li><a href = "#thumbnails">Thumbnails</a></li>
      <li><a href = "#alerts">Alerts</a></li>
      <li><a href = "#listGroup">List Group</a></li>
      <li><a href = "#panel">Panels</a></li>
      <li><a href = "#wells">Wells</a></li>



    </ol>


  </div>

<div class = "topHead">
  <h1 id = "mainHead">Shoelace</h1>
</div>




<div class = 'main' >


  <hr>
  <header>
  <h1 id = 'headings'>Headings</h1>
  <h2 class="center">Headings in Shoelace all carry a Droid Sans font-family.<h2>
  </header>

    <section>

        <h1 class = "h1">h1 classes are block level while .h1 are inline</h1>
        <blockquote><xmp><h1 class = "h1">h1 tags are all block level while class
      .h1 are inline</h1></xmp></blockquote>
        <h2 class = "h2">h2 classes are block level while .h2 are inline</h2>
        <blockquote><xmp><h2 class = "h2">h2 tags are all block level while class
      .h2 are inline</h2></xmp></blockquote>
        <h3 class = "h3">h3 classes are block level while .h3 are inline</h3>
        <blockquote><xmp><h3 class = "h3">h3 tags are all block level while class
      .h3 are inline</h3></xmp></blockquote>
        <h4 class = "h4">h4 classes are block level while .h4 are inline</h4>
        <blockquote><xmp><h4 class = "h4">h4 tags are all block level while class
      .h4 are inline</h4></xmp></blockquote>
        <h5 class = "h5">h5 classes are block level while .h5 are inline</h5>
        <blockquote><xmp><h5 class = "h5">h5 tags are all block level while class
      .h5 are inline</h5></xmp></blockquote>
        <h6 class = "h6">h6 classes are block level while .h6 are inline</h6>
        <blockquote><xmp><h6 class = "h6">h6 tags are all block level while class
      .h6 are inline</h6></xmp></blockquote>
</section>
<header>
  <hr>
<h1 id = "bodyCopy">Body Copy</h1>
<h2 class = "center">This is applied to the all paragraph blocks.</h2>
</header>

<section><p class = "p">
Paragraphs in Shoelace. The European languages are members of the same family.
Their separate existence is a myth. For science, music, sport, etc,
 Europe usesthe same vocabulary.</p>
<p class = "p2">These languages only differ in their grammar, their pronunciation and
  their most common words. Everyone realizes why a new common language would be
  desirable: one could refuse to pay expensive translators.</p>
</p>
<h5 class = "h5">Example</h5>
<blockquote><xmp><p class = "p2">These languages only differ in their grammar, their pronunciation and
  their most common words. Everyone realizes why a new common language would be
  desirable: one could refuse to pay expensive translators.</p>
</p></xmp></blockquote>
</section>
<hr>
<header>
<h1 id = "addresses">Address</h1>
<h2 class = 'center'>The address tag defines the contact information for the author/owner
  of a document or an article.</h2>
</header>

  <section>
    <address>
<a href="https://www.learnersguild.org">Learners Guild</a><br>
492 Ninth Street (Garden Level)<br>
Oakland, CA 94607<br>
USA
</address>
</section>
<h5 class = "h5">Example</h5>
<blockquote><xmp>
  <address>
  <strong>Full Name/Title</strong><br>
  <p>St. Address, City, State</p>
  <a href="mailto:#">first.last@example.com</a>
</address>
</xmp></blockquote>


<h1 id = 'blockQuotes'>Blockquotes</h1>
<p>For quoting blocks of content from another source within your document.</p>
<section>
  <blockquote cite="http://www.blindtextgenerator.com/lorem-ipsum">
  Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
  Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque
  penatibus et magnis dis parturient montes, nascetur ridiculus mus.
  Donec quam felis, ultricies nec, pellentesque eu, pretium quis,
  sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel,
  aliquet nec, vulputate eget, arcu.
  </blockquote>

  <h5 class = "h5">Example</h5>
  <blockquote><xmp>
    <blockquote cite="URL">.....</blockquote>
  </xmp></blockquote>
</section>

<h1 id = 'pagination'>Pagination</h1>
<p>f you have a website with lots of pages, you may wish to add
   some sort of pagination to each page:</p>
<section class="center">
<nav>
  <div class="pagination">
    <button style = "background-color:black;"><a href="#">&laquo;</a></button>
    <button style = "background-color:black;"><a href="#">1</a></button>
    <button style = "background-color:black;"><a href="#">2</a></button>
    <button style = "background-color:black;"><a href="#">3</a></button>
    <button style = "background-color:black;"><a href="#">4</a></button>
    <button style = "background-color:black;"><a href="#">5</a></button>
    <button style = "background-color:black;"><a href="#">6</a></button>
    <button style = "background-color:black;"><a href="#">&raquo;</a></button>
  </div>
</nav>
</section>

<h1 id = "label">Label</h1>
<p>The HTML "label" element represents a caption for an item in a user interface.</p>

<section class="center">
<form class = "label" action="/action_page.php">
  <label for="1">Label 1</label>
  <input type="text" id="male" value="male"><br>
  <label for="2">Label 2</label>
  <input type="text" id="female" value="female"><br>
  <label for="3">Label 3</label>
  <input type="text" id="other" value="other"><br><br>
  <input type="submit" value="Submit">
</form>
</section>

<h1 id = "badges">Badges</h1>
<p></p>
<section class="center">
<button class="badge1" data-badge="6">Badge Notification</button><br>
<a href="" class="badge1" data-badge="27">#num</a>
</section>
<header>
<h1 id = "jumbotron">JumboTron</h1>
<h2 class = "center">The big box, to create big attention</h2>
</header>
<section>
<div class="jumbotron">
  <div class="container">
    <h1 id=left >Hello, world!</h1>
  <p>This is a jumbotron div, A jumbotron indicates a big box for calling extra attention to some special content or information.

A jumbotron is displayed as a grey box with rounded corners. It also enlarges the font sizes of the text inside it.
</p>
  <button style = "background-color:black;">Learn more</button>
  </div>
</div>

<blockquote><xmp>
  <div class="jumbotron">
    <div class="container">
      <h1 id=left >Hello, world!</h1>
    <p>This is a jumbotron div, A jumbotron indicates a big box for calling extra attention to some special content or information.

  A jumbotron is displayed as a grey box with rounded corners. It also enlarges the font sizes of the text inside it.
  </p>
    <button style = "background-color:black;">Learn more</button>
    </div>
  </div>
</xmp></blockquote>
</section>
  <header style = 'text-align:center'>
    <hr>
    <h1 id = "buttons">Buttons</h1>
    <h2>Clean CSS For Buttons</h2>
    <hr>
  </header>
<section>
    <h2>The Default Buttons</h2>
    <p>To create a Fresh Button, add the fresh-button classname to a button or input element.</p>


    <button class = "fresh-button">Fresh Button</button>
    <input class = "fresh-button" type ="button" value = "Input"></input>
    <input class = "fresh-button" type ="submit" value = "Submit"></input>
    <div style = "background:#778899">
      <xmp>
        <button class = "fresh-button" role ="button">Fresh Button</button>
        <input class = "fresh-button" type ="button" value = "Input"></input>
        <input class = "fresh-button" type ="submit" value = "Submit"></input>
      </xmp>
    </div>
</section>
<section>
  <h2>The Disabled Buttons</h2>
  <p>To create a Fresh Button, add the fresh-button classname to a button or input element.</p>


  <button class = "fresh-button fresh-button-disabled">Fresh Button</button>
  <input class = "fresh-button fresh-button-disabled" type ="button" value = "Input"></input>
  <input class = "fresh-button fresh-button-disabled" type ="submit" value = "Submit"></input>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button fresh-button-disabled">Fresh Button</button>
      <input class = "fresh-button fresh-button-disabled" type ="button" value = "Input"></input>
      <input class = "fresh-button fresh-button-disabled" type ="submit" value = "Submit"></input>
    </xmp>
  </div>

</section>
<section>
  <h2>The Active Buttons</h2>
  <p>To create an Active Fresh Button, add the fresh-button-active classname to a button or input element.</p>


  <button class = "fresh-button fresh-button-active">Fresh Button</button>
  <input class = "fresh-button fresh-button-active" type ="button" value = "Input"></input>
  <input class = "fresh-button fresh-button-active" type ="submit" value = "Submit"></input>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button fresh-button-active">Fresh Button</button>
      <input class = "fresh-button fresh-button-active" type ="button" value = "Input"></input>
      <input class = "fresh-button fresh-button-active" type ="submit" value = "Submit"></input>

    </xmp>
  </div>
</section>
<section>
  <h2>The Primary Buttons</h2>
  <p>To indicate a Primary Fresh Button, add the fresh-button-primary classname to a button or input element.</p>


  <button class = "fresh-button fresh-button-primary">Fresh Button</button>
  <input class = "fresh-button fresh-button-primary" type ="button" value = "Input"></input>
  <input class = "fresh-button fresh-button-primary" type ="submit" value = "Submit"></input>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button fresh-button-primary">Fresh Button</button>
      <input class = "fresh-button fresh-button-primary" type ="button" value = "Input"></input>
      <input class = "fresh-button fresh-button-primary" type ="submit" value = "Submit"></input>

    </xmp>
  </div>
</section>
<section>
  <h2>Different Size Buttons</h2>
  <p>To indicate a Fresh Button Size , add small, medium or large classname to a button
     or input element, <b>along with the specific button class.</b></p>


  <button class = "fresh-button fresh-button-primary small">Fresh Button</button>
  <input class = "fresh-button fresh-button-primary medium" type ="button" value = "Input"></input>
  <input class = "fresh-button fresh-button-primary large" type ="submit" value = "Submit"></input>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button fresh-button-small">Fresh Button</button>
      <input class = "fresh-button fresh-button-medium" type ="button" value = "Input"></input>
      <input class = "fresh-button fresh-button-large" type ="submit" value = "Submit"></input>

    </xmp>
  </div>
</section>
<section>
  <h2>Different colored buttons</h2>
  <p>To indicate a Fresh Button Color , add red, green or orange classname to a button
     or input element, <b>along with the specific button class.</b></p>


  <button class = "fresh-button green">Fresh Button</button>
  <input class = "fresh-button orange" type ="button" value = "Input"></input>
  <input class = "fresh-button red" type ="submit" value = "Submit"></input>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button green">Fresh Button</button>
      <input class = "fresh-button orange" type ="button" value = "Input"></input>
      <input class = "fresh-button red" type ="submit" value = "Submit"></input>

    </xmp>
  </div>
</section>
<section>
  <h2>Button Groups</h2>
  <p>To create a button group simply add the group classname to a div
     or section element, <b>along with the specific button class.</b></p>

<div class = "group">
  <button class = "fresh-button">Fresh Button 1</button>
  <button class = "fresh-button">Fresh Button 2</button>
  <button class = "fresh-button">Fresh Button 3</button>
</div>
  <div style = "background:#778899">
    <xmp>
      <button class = "fresh-button">Fresh Button 1</button>
      <button class = "fresh-button">Fresh Button 2</button>
      <button class = "fresh-button">Fresh Button 3</button>
    </xmp>
  </div>
</section>
<hr>
<header style = 'text-align:center'>
  <h1 id = "breadcrumbs">Breadcrumbs</h1>
  <h2>Navigate Pages Within Websites Easily</h2>
  <hr>
</header>
<section>
  <h2>Creating Breadcrumb Navigation</h2>
  <p>To create a navigational guide to easily link your site pages, use
     the breadcrumb class.</p>
  <ul class = "breadcrumb">
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Contact</a></li>
    <li><a href="#">Blog</a></li>
  </ul>
  <div style = "background-color:#778899">
    <xmp>
      <button class = "fresh-button" role ="button">Fresh Button</button>
      <ul class = "breadcrumb">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Blog</a></li>
      </ul>
    </xmp>
  </div>
</section>
</ul>
<hr>

<header style = 'text-align:center'>
  <h1 id = "pageHeader">Page Header</h1>
  <h2>A simple style for an h1 to accurately space sections of content on the page.</h2>
  <hr>
</header>
<section>
  <h4>Underneath is a page-header</h4>
  <div class="page-header">
  <h1>Example page header <small>-Subtext for header</small></h1>
</div>
  <div style = "background-color:#778899">
    <xmp>
      <div class="page-header">
        <h1>Example page header <small>-Subtext for header</small></h1>
      </div>
    </xmp>
  </div>
</section>
<hr>


<header style = 'text-align:center'>
  <h1 id = "thumbnails">Thumbnails</h1>
  <h2>Easily display grids of images, videos, text, and more.</h2>
  <hr>
</header>
<section>
  <a href="#">
      <img class ="thumbnail" src="https://oup.useremarkable.com/production/images/uploads/3048/original/sneaky-cat-thumbnail.jpg?1471959757" alt="cat photo">
  </a>
  <a href="#">
      <img class='thumbnail' src="https://lh5.ggpht.com/z-HSdeRxdeE5ExB6VliQiKpi7o5VWQ3xpbXfs_8Q8rFO8O7sF52hGEhLNYTG7un_nw=h310" alt="cat photo 2">
  </a>
  <a href="#">
      <img class='thumbnail' src="https://upload.wikimedia.org/wikipedia/commons/d/db/White_House_Cat.JPG" alt="cat photo 3">
  </a>
  <div style = "background-color:#778899">
    <xmp>
      <a href="#">
          <img class ="thumbnail" src="https://oup.useremarkable.com/production/images/uploads/3048/original/sneaky-cat-thumbnail.jpg?1471959757" alt="cat photo">
      </a>
      <a href="#">
          <img class='thumbnail' src="https://lh5.ggpht.com/z-HSdeRxdeE5ExB6VliQiKpi7o5VWQ3xpbXfs_8Q8rFO8O7sF52hGEhLNYTG7un_nw=h310" alt="cat photo 2">
      </a>
      <a href="#">
          <img class='thumbnail' src="https://upload.wikimedia.org/wikipedia/commons/d/db/White_House_Cat.JPG" alt="cat photo 3">
      </a>
    </xmp>
  </div>
</section>

<header style = 'text-align:center'>
  <hr>
  <h1 id = "alerts">Alerts</h1>
  <h2>Provide contextual feedback messages for typical
      user actions with the handful of available and flexible alert messages.</h2>
  <hr>
</header>
<section>
  <h4>Wrap any text with .alert and one of the four
     contextual classes for basic alert messages.</h4>
  <div class="alert alert-success" role="alert">You have succeeded</div>
  <div class="alert alert-info" role="alert">Heads up, here's some info.</div>
  <div class="alert alert-warning" role="alert">Oh No! Watch Out.</div>
  <div class="alert alert-danger" role="alert">You are now dead.</div>

  <div style = "background-color:#778899">
  <xmp>
    <div class="alert alert-success" role="alert">You have succeeded</div>
    <div class="alert alert-info" role="alert">Heads up, here's some information.</div>
    <div class="alert alert-warning" role="alert">Oh No! Watch Out.</div>
    <div class="alert alert-danger" role="alert">You are now dead.</div>
  </xmp>
  </div>
</section>
<header style = 'text-align:center'>
  <hr>
  <h1 id = "listGroup">List Group</h1>
  <h2>Flexible and powerful component for displaying list of elements</h2>
  <hr>
</header>
<section>
  <h4>The most basic list group is simply an unordered list with list items, and
      the proper classes.</h4>
      <ul class="list-group">
      <li class="list-group-item">Apples</li>
      <li class="list-group-item">Oranges</li>
      <li class="list-group-item">Grapes</li>
      <li class="list-group-item">Kiwis</li>
      <li class="list-group-item">Celery</li>
    </ul>

  <div style = "background-color:#778899">
  <xmp>
    <ul class="list-group">
      <li class="list-group-item">Apples</li>
      <li class="list-group-item">Oranges</li>
      <li class="list-group-item">Grapes</li>
      <li class="list-group-item">Kiwis</li>
      <li class="list-group-item">Celery</li>
    </ul>
  </xmp>
  </div>
</section>


<header style = 'text-align:center'>
  <hr>
  <h1 id = "panel">Panels</h1>
  <h2>Sometimes you need to put your content in a box. For those situations, try the panel.</h2>
  <hr>
</header>
<section>
  <h4>By default, all the .panel does is add basic border and padding to contain content.</h4>
  <h3>Basic Panel Example Below</h3>
  <div class="panel panel-default">
    <div class="panel-body">
      Basic panel example.
    </div>
  </div>
  <div style="background-color:#778899;">
  <xmp>
    <div class="panel panel-default">
      <div class="panel-body">
        Basic panel example.
      </div>
    </div>
  </xmp>
  </div>
  <h3>Panel with heading</h3>
  <h4>Easily add a heading container to your panel with .panel-heading. Also,
      h1-h6 elements can be used but are overridden by .panel-heading.
      For correct link coloring, be sure to place links in headings within .panel-title.
  </h4>
  <div class="panel panel-default">
  <div class="panel-heading">Panel heading without title</div>
  <div class="panel-body">
    Panel content
  </div>
</div>

<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Panel title</h3>
  </div>
  <div class="panel-body">
    Panel content
  </div>
</div>

  <div style = "background-color:#778899">
  <xmp>
    <div class="panel panel-default">
      <div class="panel-heading">Panel heading without title</div>
      <div class="panel-body">Panel content</div>
    </div>

    <div class="panel panel-default">
      <div class="panel-heading">
        <h3 class="panel-title">Panel title</h3>
      </div>
      <div class="panel-body">
        Panel content
      </div>
    </div>
  </xmp>
  </div>
</section>
<hr>
<header style = 'text-align:center'>
  <h1 id = "wells">Wells</h1>
  <h2>Basic effect on an element to give it an inset feel.</h2>
  <hr>
</header>
<section>
  <div class="well">Look at how deep this well is.</div>
  <div style = "background-color:#778899">
    <xmp>
      <div class="well">Look at how deep this well is.</div>
    </xmp>
  </div>
</section>

</div>

  </body>

</html>
