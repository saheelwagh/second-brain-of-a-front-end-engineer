- react
  collapsed:: true
	- intro to react
		- What made JSX different was it combined the power and expressiveness of JavaScript with the readability and accessibility of HTML. If you were already comfortable with both JavaScript and HTML (which you probably were, if you were building web apps), then you could get up to speed with JSX in a matter of minutes.
		- Yes it was weird and different and most people hated it at first, but once you used it in an actual app, it became clear that React was onto something with their interpretation of the Separation of Concerns principle.
		- Not only that, but by embracing both JSX and React's component based API, all of a sudden what used to require imperative, operational like code, could be abstracted behind a declarative API. This not only enabled a better developer experience, but also a vibrant ecosystem of third party components.
		- you're creating a SPA where nothing happens until the browser loads that beefy bundle. Next, by the nature of a component based API, whenever you had state that was needed in multiple components, you either had to raise that state up to the nearest parent component, use React's context feature, or in some cases, reach for a library like Redux. Finally, again by the nature of a component based API, since most components were in charge of the data they needed to render, which included fetching that data if needed, loading states were a prominent part of the React app experience.
		- The solution, ironically, was to treat React as more of a UI primitive than an application platform. The project that pioneered this was Next.js.
		- Next.js is a framework built on top of React. This allows Next.js to give you all of the benefits of React, while also providing some valuable features like support for SSG and SSR, smart bundling, route pre-fetching, and much more.
		  Remix is another example. By building on top of React, Remix lets React do what it's good at - rendering UI - while outsourcing what React isn't great at like "global" state management and data fetching to distributed "edge" servers. This gets you the benefits of React, without most of the tradeoffs.
		- Regardless of how you feel about React, there's no denying that it fundamentally changed how we build web application. And based on everything I'm seeing, it shows no signs of slowing down.
- hooks
-