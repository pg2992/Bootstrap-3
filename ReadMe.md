##Grid View
- the container has 12 segments or divisions.
- there are 4 diff breakpoints
	- less than 768px is extra small -- mobile devices
	- btw 768 to 991 is small -- tablets
	- btw 992 to 1199 is medium -- laptops
	- greater than 1200 px
- gutter width - 30 px - 15 px on each side
- also we can grid inside grid. Like we have row-fluid inside row-fluid in 2.0
- Push and pull 
	- used for realignment of sections at different breakpoints.
	- eg col-md-push-2 or col-md-pull-4
- normally as we know the parent inherits from child so any class applied to lower breakpoint autimatically gets applied to upper one.
- If you doesn't want that u have to speicificly declare the class to that particular breakpoint.
- Offsets - can be used for giving offesets.
 
##Tables
###Classes for table tag

- add *table* class to table tag
- to apply alternate shades to the table use ***table-striped*** --does not work in IE 8
- to apply all borders use ***table-bordered*** 
- to apply hover on rows use ***table-hover***
- use ***table-condensed*** class to removed extra padding and spacing in table
- to make table responsive for small devices use ***table-responsive*** class
	> **Note:** for firefox you need to add below mentioned quirky code in ur linked css to work properly responsive.
	> @-moz-document url-prefix{
	  fieldset {display:table-cell;}
	 }




===================================================================
###Classes for row tag
- use *active* for get hover color on row permanently to show active row.
- use *danger* class for making red the row to show some danger
- use *success* class for green
- use *warning* class for yellowish color on row
- use *info* class for ligh blueish
> **Note:** Theses all classes can overridden by custom classes in custom css. Do not overwrite the bootstrap actual css.Because it makes life horible. :P


##Modals

