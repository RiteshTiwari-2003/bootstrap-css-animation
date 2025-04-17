# Bootstrap 

introducton:
bootstrap is the css based frontend framework, which was made by twitter company 
some importent point in bootstrap

> Layout
> Typography
> navigation Menu
> form Layout
> Buttons
> Paggination
> Icons Font
> Responsiveness

when i put all this functionality into a css file and use that file that file calle as css framework like bootstrap is a css framework.

a css framework is the pre-prepared library that provides the ready to use style ,layouts, and components for web design , It simplifies the process of building and designing responsive, visually appealing, and consistent websites or web applications.

# advantage of using bootstrap
1. Saves lot of time
2. responsive feature
3. consistent design 
4. easy to use 
5. compatible with browser
6. open source

# bootstrap css feature 
> multi column layout 
> form layout 
> button group 
> button drop down 
> iput groups 
> Navs, navbar, dropdown, Breadcrumbs
> Paggination, labels, badges, jumbotron , page header 
> thumbnails, alerts, progress bars , list groups, panels, media object 
> responsive embed , wells, glyphicons
# bootstrap js components

> modal box
. drop down 
> scrollspy
> tab 
> tooltips, popover, alert, collapse, carousel, affix

bootstrap 4 new feature
> flexbox layout
> new components 
> faster , more Responsiveness
support all major browser and platform , enternet explorer9 and down not supported 

prior knowledge before learning bootstrap :
html , css , jquery , css media query , css flexbox

css media query :
type of css media query 
1. all 
2. print
3. screen 
4. speech

# how to write media query code in css 
@media screen and (max-width: 900px){
    .container{
        width:50%;
    }
}
like wityh the @media tag you must do two condition with logical operation and means when width of screen make equal or less than 900px then in that webpage 
container name class follow the css property which indicate in media query in .container block 

# css flex 
for using in css flex we need to add this line in style.css property like 
display : flex;
flex-direction : row/column;
justify-content; center;
align-items: center;
text-align: center;

css flex properties

flex direction , flex, flex-wrap, justify-content, flex-flow, align-content, flex-grow, align-items, flex-shrinks, align-self, flex-basis, order

# flex-direction:
value of flex-direction:
row, row-reverse, column, column-reverse


# flex-wrap and flex-flow
flex-wrap three default value;
nowrap, wrap, wrap-reverse
# flex-flow : 
 when i want to use flex direction property and flex-wrap property in one line in one attribute in property then we can mention both thing in the key of flex-flow.

# css flex box justify content:

justify content value:

justify content use for horizental alignment .
> flex start , flex end, center, space-around, space-between , space-evenly

align-item values:
flex-start,flex-end,center,stretch , baseline

# box -sizing property in css

box-sizing : border-box;
> the width and hieght include the content, padding , and border
> this makes it easier to control the overall size 

# box-sizing: content-box

> the widthand hieght only include the content.
> padding and border are not included in the dimensions but are added outside the content box.
bootsrap includes html and css based design template for typography , forms ,button, tables 
bootstrap also give ability to easily create responsive design for responsive web pages 
responsive web design is about to creating websites which automatically adjust themselves to look good on all device '
from small phone to large desktop .
create first page using bootstrap 
<meta name="viewport" content="width=device-width,initial-scale=1">
2. container :
bootstrap also require a containing element to wrap site content:
there are two container class to choose from:
the .container class provide a responsive fixed width container 
the .container-fluid class provide a full width container spanning the entire width of the viewport.
first page suning bootstrap :
<!DOCTYPE html>
<html lang="en">
<head>
<title>BootStrap Example</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
</head>
<body>
<div class="container">
<h1> My First bootstrap page</h1>
<p> this issome text</p>
</div>
</body>
</html>
#### bootstrap grid system :
it is used for creating page layout through a series of row and column 
bootstrap's grid system allow up tio 12 column across the page .
bootstrap grid system is respnsive ,and column will arrange itself automatically depending upon the screen size.
if you dont want to use all the 12 column individually then you can group the column together to create the wider column .
the bootstrap grid system has four class ;
1. xs : xs is used for phone screen screen less than 768px wide.
2. sm: screen equal to or greater than 768px size.for tablets
3. md: screen equal to or greater than 992px wide. for small laptos .
4. lg for laptop or desktop: screen equal to or greater than 1200 px wide.
basic structure of grid system :
<div class="row">
<div class="col">..</div>
<div class="col">..</div>
</div>
<div class="row">
<div class="col">...</div>
<div class="col">...</div>
</div>
<html>
<head>
<meta name="viewport" content="width=device-width,initial-scale=1">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<style>
    div{
        border:solid;
    }
</style>
</head>
<body>
<div class="container">
<div class="row">
<div class="col-sm-6 col-md-4">Div 1</div>
<div class="col-sm-3 col-md-4">Div 2</div>
<div class="col-sm-3 col-md-4">Div 3</div>
</div>
</div>
</body>
</html>
#### bootstrap supported class 
Typography:
we look at the html element that will be styled a little bit differntly by bootstrap that browser default 
the classes for text color:
.text-muted, .text-primary, .text-success, .text-info, .text-warning , and .text-danger
the classes for background color:
.bg-success,.bg-primary, .bg-info, .bg-warning, .bg-danger
the classes for text content are => .text-left, .text-center, .text-right, .text-justify, .text-lowercase , .text-uppercase, .text-capitalize

#### bootstrap table :
the.table class add basic styling to a table , the basic bootstrap table has a light padding and only horizental devider ,
the .table-striped class adds zebra stripes to a table , the .table-bordered class adds borders on all side of the table and cells ,
.table-hover class adds a hover effect , and .table-condensed class makes a tabe more compacted by cutting cell padding in half

<table border=2 class="table table-striped table-hover table-bordered table-condensed">
<tr><td>First TD</td><td>Second TD</td><td>Third TD</td></tr>
<tr><td>Fourth TD</td><td>Fifth TD</td><td>Sixth TD</td></tr>
<tr><td>Seventh TD</td><td>Eight TD</td><td>ninth TD</td></tr>
</table>
#### list and list group:
to create a basic list group use an <ul> element with class .list-group and <li> element with class .list-group-item 
<ul class="list-group">
<li class="list-group-item list-group-item-success">Intellipaat</li>
<li class="list-group-item list-group-item-info">SkillLearners</li>
<li class="list-group-item list-group-item-warning">Physics Wallah</li>
</ul>

#### bootstrap form :
to achive the different background color for button , bootstrap has the following classes:
.btn
.btn-default
.btn-primary
.btn-success
.btn-info
.btn-warning 
.btn-danger
.btn-link
bootstrap provide different button sizes , the classes that defined the different sizes :
.btn-lg
.btn-md
.btn-sm
.btn-xs
<body>
<div class="container">
<input type="text" value="Click Me" class="btn btn-success btn-lg"/>
<input type="text" value="Click Me" class="btn btn-primary btn-lg"/>
<input type="text" value="Click Me" class="btn btn-info btn-lg"/>
</div>
a block level button spans the entire width of parent element <button type="button" class="btn btn-primary btn-block" >Button 1</button>
a button can be set to an active (appear pressed) or disabled (unclickable state) , the class .active makes a button appear pressed and the class .disabled makes it disable <button type="button" class="btn btn-primary disabled" >Button 1</button>
<button type="button" class="btn btn-primary active" >Button 1</button>

bootstrap provide three type of form layout :
vertical form (by default)
horizental form 
inline form 

### rules for bootstrap form :
standard rule for three form layout:
wrap labels and form controls in <div class="form-group">(needed for optimaum space)

add class .form-control to all textual <input>, ,<textarea> and select element .
alltextual <input>, <textarea> and <select> eement with class .form-control have a width of 100%
<form >
<div  class="form-group">
<label>User input</label>
<input type="text" value="username" class="form-control"/></div></form>

#### now lets discuss about inline form :
inline form :
in an inine form , all of the element are inline , left aligned and label are alongside 
this only applies to forms within viewpoet that are atleast 768px value ,
additional value for inline form :
add class .form-inline to the form element 