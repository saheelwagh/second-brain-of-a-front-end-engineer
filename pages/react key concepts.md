- Udemy course
	- goal -> good arch decison and lead react projects
	- Why was react created
	  collapsed:: true
		- initially just static or server side
		- jquery -> solved browser compatability issues
			- also provided a uniform easy api
		- then devs strarted building bigger apps
			- backbone js -> organise thses js files -> birth of [[Single page Apps]]
			- angular -> mvc -> divide js by roles
				- dynamic locations increased -> hard to debug
			- fb devs -> fb ads app grew bigger with ppl working and features
				- software arch
					- how to org code
					- how to store data
					- how to make that data flow
				- react -> copied by angular -> ppl moved due to complete rewrite
				-
	- declerative
	  collapsed:: true
		- state => data -> update the dom as per -> js object of how page should look like
		- dom manip was big bottleneck
		  collapsed:: true
			- repaint
			- reflow
	- component archite
	  collapsed:: true
		- ind pieces that form the app
		- handoff component levels within team
			- tailwind component library ?
		- plain js fns
	- unidirectional dataflow
	  collapsed:: true
		- virtual dom -> js obj to update the app
		- state change -> app update
			- info is trickled down
			- data can never move down
	- react is only focused on ui library
	  collapsed:: true
		- LATER what other libraries are needed to create a modern app ?
	- How to become a great react developer
	  collapsed:: true
		- 1. Decide the components
		  2. Decide the state and where it lives
		  3. What changes when state changes
	- code reading of monster rolodex
	  collapsed:: true
		- card ->Takes in Monster object as prop -> exports monster card from this and robohash -> similar to question obj
		- card-list -> imports card -> takes in an array of monster objects -> similare to questions objects
- Component based architecture
  collapsed:: true
	- At its core , a component is a javascript function
	  collapsed:: true
		- this function takes in data as input and outputs a markup
			- in react's case, this data describes how the component should  appear and the output markup is in jsx format
			- the supplied data is called props (short for properties)
		- ```
		  function Welcome(props) {
		  	return <h1> Hello, {props} </h1>
		  }
		  // assignment 1 -> convert the above component to an annonymous function
		  // 2 -> what is the role of {} ? what happens if you remove it ?
		  
		  ```
		- assignment for later : convert into a class component
		-
	- benefits of component based architecture
		- helps you reason about the project better. Instead of tackling whole project at once you can create break it down into components and build it up from there.
		- laying out css for smaller components (say one button) is easier than responsive layout of each page. Thus you can hand off the responsive part to a specialised dev while  you focus on the functionality
		- code can be resued.
		- user defined to fit custom needs. Unlike html elements
	- components can refer to child components within them.
	- props are defined as parameters -> fn Comp(propName)
		- they are then supplied while laying out the components
		- <Comp propName={}/>
		- react docs recommends naming props from component's own point of view -> as the component does not know or care where it is being loaded (that is the concern of one component above)
	- when component ? when either is true
		- can this element be reused ?
		- is this component so complex that it will require separate focus ?
	- strict rule : all components must act like [[pure functions]]
	-
	-
- state and unidirectional data flow
  collapsed:: true
	- state -> pvt and fully controlled by the component
	- state modification is async and might be batched
	- shallow merging  by setState
	- data only flows down
		- a component may pass its state down as props to its child component
		-
- jsx
	- created to keep mockup + data + js in same place
	- {expressions are embedded in between these}