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