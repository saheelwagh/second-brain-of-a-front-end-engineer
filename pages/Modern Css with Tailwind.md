- ![Modern CSS with Tailwind Flexible Styling Without the Fuss - Second Edition (beta B3.0) (Noel Rappin) (z-lib.org).pdf](../assets/Modern_CSS_with_Tailwind_Flexible_Styling_Without_the_Fuss_-_Second_Edition_(beta_B3.0)_(Noel_Rappin)_(z-lib.org)_1651069946606_0.pdf)
- Many web devs underrate css
  collapsed:: true
	- check out csszengarden.com
	- but it is hard to debug, complicated to write and difficult to control
- Why tailiwnd ?
	- nearly all basic utility classes are thin wrapppers around a single css style settinh
		- m-4 -> margin 1rem
		- code is explicit. Possible to understand the display simply by looking at the HTML markup
		- easy to proto iterate and customize
		- u can add specific modifiers such as hover:bg-blue-500
		- a tailwind app requires less css to be written
			- u spend less time naming css and more time on actual display of your site
- flow of this book
  collapsed:: true
	- typography -> box -> page layout -> sites
- who this book for 
  collapsed:: true
	- basics of css syntax and concepts done
	- able to access tailwind docs
	- why I chose
		- css is easy but hard
			- I find csss syntax easy to grasp but hard to apply
			- tradtitional methods leave in same loop
			- felt like needed a steppping stone and a forcing function in the form of a new paradignm
- Getting started with tailwind
	- tailwind is a
		- set of utility classess
		- tool that generates css files
	- thus we need to first install the framework itself and then patch it into our css processing tool chain
	- The tailwind cli
		- a huge no of classes can be generated through tailwind
		- it uses a HIT to detect and limit shipped css to used css
		- cli is an interface to that engine
		- u provide tailwind with a list of the files in your project that declare css classes.
		  collapsed:: true
			- tailwind scans those files for text patterns that match tailwind classes and then returns a css file having only those classes
		- installation
			- via npm and a tainwindcofig filw
			- u then specufy all files that might used a css class. this is the input for the css generator
			- A standard React app might look like this, where Tailwind is directed to lookat all files in any subdirectory under src that end in html, js, or jsx.
			- ``` 
			  content:["./src/**/*.{html,js,jsx}"]
			  ```
			- install the tailwind vscode plugin
			- finallyy, add tailwind to our css files
			  collapsed:: true
				- put the lines in a css file that is being imported
				- ```
				  @tailwind"tailwindcss/base";
				  @tailwind"tailwindcss/components";
				  @tailwind"tailwindcss/utilities";
				  ```
					- importing tw in 3 layers
						- base -> reser classes
						- component classes
						- layers
						-
	- in each step we were able to incementally change the display by addiing more tw classes
	-