- **As the old proverb from the balkans says: Budala pamti, pametan piše. The fool remembers, the clever one writes.**
- [[May 9th, 2022]]
  collapsed:: true
	- Morning half
		- rank skills by value. In order to focus on the 20%
			- case  study : why you might be better off learning webflow
			- [[functional programming]] learn in depth ??
			  collapsed:: true
				- When you think of code as a series of transformations, your life will be easier.Small discrete steps, rather than large objects and codebases.
			- [[state management in react]]
		- known hard  tasks cause 10x less stress  as unknown easy tasks
		- Inheritance tax
		  collapsed:: true
			- by default dont use
				- share code -> try [[mixin]] or [[traits]]
				- build types -> try [[interfaces]]
				-
		- dont share state
		  collapsed:: true
			-
			-
			-
		- blog -> post one soln daily . When asked -> post link. drive more traffic
		-
		-
- [[May 10th, 2022]]
  collapsed:: true
	- Evening half
		- [[The Planning fallacy]]
		- [[The mere urgency effect]]
		- [[Present Bias]]
		- [[The rule of two]]
		-
		-
		-
- [[May 24th, 2022]]
  collapsed:: true
	- Start by solving the smallest subset -> ask why this is happening -> can't fix then approach from another angle
	- [[How to learn react]]
	- learning time -> separate from working time -> separate from high level design time -> listen to instinct to understand which role to play
	  collapsed:: true
		- roles to play for profession -> blog post on each
		  collapsed:: true
			- coder
				- architect
				- learner
				- builder
				- review nd writer
				- teacher
			- writer
				- reader and note taker
				- reviewer and synthesizer
				- writer as builder
			- designer
				- collector
				- learner
				- clean up organiser
				- synthesizer
				- communicator and educator
		-
	- sometimes sticking with one resource helps. Don't jump to next before solidifying currently learnt concept and knowing what to seek next
	-
	-
- [[May 31st, 2022]]
  collapsed:: true
	- go through tailwind classes -> make note of underlying css properties
		- learn what is reqd in depth
	- react query -> buy if teaching caching etc
	- design bootcamp -> create moodboard and sample layouts for all using udemy course
	- convert questions js to firebase based
	-
- [[Jun 20th, 2022]]
  collapsed:: true
	- delegation lessons
		- maintain a flywheel instead of batching tasks
		- set up small testable feedback loops that ideally result into launching a feature in two days
	- solana -> huge benefits of diving deep
	- try this [bundle](https://www.humblebundle.com/books/software-development-books-oreilly-media-books?hmb_source=&hmb_medium=product_tile&hmb_campaign=mosaic_section_1_layout_index_1_layout_type_threes_tile_index_1_c_softwaredevelopmentbooksoreillymedia_bookbundle)
	- [[Blockchain developer Hub]]
		- how to init a solidity blockchain project ?
			- same for sol
		- constructor no longer needed
		- visibility options in solidity
		- Solana basics
			- An app **interacts with a Solana cluster** by **sending it transactions** with one or more **instructions.**
			- The Solana runtime passes those instructions to programs deployed by app developers beforehand.
			- If any instruction is invalid, all account changes in the transaction are discarded.
			-
- [[Jun 23rd, 2022]]
  collapsed:: true
	- half hearted working takes up more time than breaks
	- track not just distractions but also
- [[Aug 18th, 2022]]
  collapsed:: true
	- session 1 : 10 am -
		- [gap in traching software](https://attilavago.medium.com/the-dangerous-gap-in-how-we-teach-software-development-e094c30b8636?utm_source=pocket_mylist)
		  collapsed:: true
			- Moving into the online, seeing friends of mine pick up software and web development courses, listening to their questions, and trying to answer them to the best of my abilities, I realised something — most web development courses skip foundational knowledge without even realising.
				- what funds to blockchain courses skip ? how do I cover this in my email course ?
			- *Have you ever asked yourself why jQuery became so popular? One of the reasons is that to this day, it has one of the most readable and reliable documentation additionally to the already simplified syntax
			- Staring at someone code something only works when your foundational knowledge is already set in stone.
			- I reached the conclusion that practically everything out there, meant to kick-start someone’s software development career, is fundamentally flawed. The bootcamps don’t really teach, but hammer information into students, most online courses assume far too much technical background, and official docs are mostly written by engineers who don’t know how to go down to absolute noob levels.
			-
		- some rules to 10x life
		  collapsed:: true
			- no more band aid solutions
				- quick fixes -> trojan horses
				- get to the roots
			- either hell yes or fuck no
			- small achievements, big celebrations
			-
		- [if u cant deal with bugs get out of software dev](https://medium.com/gitconnected/if-you-cant-deal-with-the-bugs-get-out-now-dae4ef45e80c?source=explore---------27-2--------------------3340ae20_2cd6_4baf_876c_73a958d500b2-------15&utm_source=pocket_mylist)
			- good parts are oversold
			- I’m not suggesting you’ll get fired, but more like despite all the benefits, you’ll want out
			- It took me years to grow into the software engineer that I am today.
			- one thing that I feel I have grown more in than perhaps many, and that is dealing with bugs.
			- Believe it or not, bugs taught me at least as much as feature development…
			-
			- Taking on a bug or a series of bugs in a codebase can often mean you’re exposed to projects you have little or no context on. This could very well mean you’re finding yourself dealing with a new language, a new library or framework and everything associated to that from setting up your machine to run the project locally, to finding the fix, writing tests and deploying the fix.
			-
- [[Sep 13th, 2022]]
  collapsed:: true
	- session 1 -> 9:15 -> 9:30
		- each work sess (90) shd have a clear outcome regardless of quality
		- each pomo can then be paced to give input towards it
		- outcome aim : moodboard inspired design
	-
- [[Sep 14th, 2022]]
  collapsed:: true
	- time waster biggest -> slow burner grind
	- better to learn editor shortcuts same day
		- email course on shortcut a day
			- focused on vscode
	- better to keep logging offline so u can break without hesistation
	-
- [[Sep 16th, 2022]]
  collapsed:: true
	- 12-1
		- [How to think in react](https://triplebyte.com/blog/how-to-think-in-react?utm_source=pocket_mylist)
			- Or if you're a front-end developer tasked with a React project for the first time, the library has the potential to make you question everything you've ever known.
			- Building with React requires a different kind of mindset. The freedom it allows means you're not propped up by structure or architecture. There's no fallback of an entire framework to keep you out of spaghetti code trouble.
			- 4 key concepts of thinking in react
				- Start with single resp componments
					- The one thing about React that often hits non-React developers is the need to drill down your UI into components. It is a process of abstracting your UI into little lego-like parts.
					- But the question then becomes – how small do these components need to be?
						- The easiest way to determine this is to apply a **single responsibility rule**.
							- What this means is that a component should only do one thing. Any time a component grows larger than a single responsibility, it should be refactored and decomposed into a collection of smaller components.
							- One efficient method is to match your component to the data you're given via JSON. **This is because your dynamic app is most likely connected to a data source in some form.**
							-
				- START WITH THE STATIC VERSIONS
					- When building your UI, it can be tempting to code each individual component as separate parts and put them all together. This can be a logistic issue, especially on the CSS front, when it comes to getting things to sit in the right places for different view ratios.
					- This is why it's good to start with a static version that renders the entire view first. A static version just consumes the data and presents it on the screen. It doesn't matter in which order you begin constructing your UI. Your main focus here is to fit all the pieces together at the visual level.
					- For smaller projects and UIs, it's easier to go from the top of the hierarchy. For larger projects, it's easier to work from the bottom of the hierarchy and move your way up and out. A bottom-up approach is also easier to write tests against as you build your UI.
					- When you focus on the static version, you're not distracted by state management and the task of coordinating the building of each component out of context.
					-
				- minimal repr of state
					- This concept is an idea that's not often talked about when we learn React. What most of us encounter is that we need to represent our UI state in some form. There is no emphasis on a minimum representation.
					- It is when a developer is able to capture wholly the minimum required states for your entire application. This means that you're not repeating yourself in another component. If you find yourself typing the same code (or something similar), it means that you are creating duplicates and not applying DRY on your code. The idea of DRY is simple: Don't repeat yourself. And this is essentially what minimum representation of states is.
					- But how can you tell if something is not a state? Here are some questions I've developed to help me figure out if something is a state or not.
						- Is it passed in from a parent via props?
						  Does it remain unchanged over time?
						  Can you compute it based on any other state or props in your component?
							- yes to any => not state
						-
				- find a home for the state
					- React uses one-way data flow down the hierarchy. This means that children can only consume the data and are unable to enact any changes. Figuring out where a state should live is a process of determining what component is the parent in the hierarchy.
					- How ?
					  collapsed:: true
						- Identify every component that renders something based on that state
						- Find a common owner component or a single component that exists above all the components that need the state in the hierarchy – i.e. the parent. This is the component that should own the state.
						- If there is no component that makes sense for owning the state. Create a new component just for holding the state and keep it separate until a logical component comes into existence that sits above the common components.
						-
			- Thinking in React is a process of making everything that happens in your app happen explicitly. While this seems simple enough, the task of structuring this can entrap a new React developer.
			- The thing with React is that there is no outline or enforced guideline to make you code a certain way. You can ignore all the suggestions above and your app will still work. However, methods of thinking as described in this piece can help structure your app for the long-term by giving it a foundation that conforms to a more logical, manageable, and scalable method of construction.
			-
	- 4-5
	  collapsed:: true
		- took a break between 2 and 4. Brain was anyway not in frame of deep work.
			- schedule it for scatter mode
- [[Sep 19th, 2022]]
  collapsed:: true
	- urgency can be circumevnted by breaking down tasks
	- what previously thought was possible in a day was actually hindering progress and leading to burnout
	- [usememo tutorial for quick warmup](https://refine.hashnode.dev/react-usememo-guide-with-examples)
	- [[conept maps]]
	- [take init,gain influence](https://rkursem.medium.com/how-to-gain-influence-by-taking-initiative-in-day-to-day-situations-350616da1dfa)
		-
		- In his seminal book The 7 habits of highly effective people, Stephen R. Covey introduces Habit 1 — be proactive and writes about the difference between the reactive and the proactive person. Covey introduces the circle of influence and circle of concern as a mental model of how the two personalities interact with their surroundings. In short, the reactive person has a small circle of influence as outer circumstances set his agenda. In contrast, the proactive person constantly seeks to expand her circle of influence while not violating the win-win mindset defined as Covey’s fourth habit (think win-win).
		- Fortunately, Covey also spend some time thinking about this and in his follow-up book The 8th habit from 2004 he introduces a little gem called [[the level-of-initiative model]] .
		  collapsed:: true
			- The model has seven levels ranging from fully passive/reactive to fully autonomous/proactive. It is a so-called situational model, which means your actual level differs from situation to situation. Hence, you sometimes just have to accept the circumstances while in other situations you are fully autonomous.
			- Do. This level is covering activities you don’t need to ask permission to do. It is for routine activities and tasks that need no oversight or input from other stakeholders.
			- The circle of influence model and the level-of-initiative models can be combined by realizing that the “I intend to …” level corresponds to the boundary between the circle of influence and the circle of concern.
			-
		- First, it can be used to assess your own and other people’s influence and power. To do this, notice the actions and words you and other people use in a given situation.
		- Second, it can be used to increase your circle of influence. To do this, assess your own level of initiative and try to use the wording of the level above. As trust builds between you and the other person, you may seek to step another level up the model. To build trust, you need to think win-win and attempt to over-perform a bit to ensure the other stakeholders that you can handle the situation with confidence.
		- Third, it can be used to expand other people’s circle of influence in case you have a role as team lead or manager. This can be done by encouraging questions, asking for suggestions, asking for how your peer intended to handle the situation, or finally by delegating the decision to the other person. You may be wondering why you would do this as it sounds a bit like letting go of control. Yes, that is the case, but empowerment of the other person will strengthen the trust between you and free your resources for other tasks — you liberate yourself by liberating other!
		-
- [[Sep 20th, 2022]]
  collapsed:: true
	- nextjs provides zero config supprt for ts. Just cxreate empty tsconfig file and run dev. Next will configure everything for you
	- [the 8th  habit](https://fourminutebooks.com/the-8th-habit-summary/?utm_source=pocket_mylist)
	  collapsed:: true
		- 1-Sentence-Summary: The 8th Habit is about finding your voice and helping others discover their own, in order to thrive at work in the Information Age, where interdependence is more important than independence.
		-
		- Back in the Industrial Age, when work was mostly physical, differences in individual people’s productivity were marginal, as no one man could cut 100x logs more per day than another. But now that we live in the Information Age, where knowledge is our main skill, a great programmer can indeed be 1000x more valuable than an average one.
		- 3 key takeways
			- ur greatest gift -> freedom to choose
				- You are free to choose how you react to any and every situation in life.
			- Build trust by being friendly, knowing when to say sorry and following through on your promises.
			- Empower others by giving up control and handing them responsibility.
		-
- Midweek Review
  collapsed:: true
	- logging in logseq is a fine way to trakc productivity
	- day started with reading rarely goes well
	- monday is too late for planning
	- there is a tendency to avoid short term pain while planning
	- no progress on [[ethindia 2022]] easy to ignore when in learning phase hence introduce some kind of action
	-
- [[Sep 22nd, 2022]]
  collapsed:: true
	- as a freelancer I gave up on weekly time blocks [[drafts]]
	  collapsed:: true
		- there is no workaround , you have to ask what needs to get done today and set acordingly
		- missing rigid will cause unnecesaary stress
		- build up from ades -> konkani unit of time to day and week. dont force anything
			- easier to build
			-
		- what is time block?
		- my initial stategies
	- 12.35-1
		- imp to show up and chisel away even if not making grand gestures. this eliminates the cold start problem
		-
	- 1- 1:30
	- 1:30-1:45
	-
- [[Oct 3rd, 2022]]
  collapsed:: true
	- only what is visible gets ACTED UPON. oNly what is tracked should stay in att. rest shd be offloaded to second brain
	- learning for the sake of it is boring. learning something new is challenging, on the other hand
- [[Oct 21st, 2022]]
  collapsed:: true
	- webflow provided major setback by not asccepting card for plan
	- have to build by hand now
	- blog in strapi
	- animations ?  to be seen
	- best to scaffold in tw fast
	- aligns with dev goals anyway
	- worth it to spend hour struggling as later will be recovered.
	- scaffold sections first. then fill in content. bg color helps in identifying section dimensions
- [[Oct 27th, 2022]]
  collapsed:: true
	- 200 req per month via sheety
	- some articles of updating fetched state
		- https://articles.wesionary.team/why-useeffect-is-a-bad-place-to-make-api-calls-98a606735c1c
		- https://blog.bitsrc.io/things-you-should-know-when-fetching-data-for-react-components-39d61602feda
		- https://beta.reactjs.org/learn/updating-objects-in-state
			- go through the beta docs
		- https://bobbyhadz.com/blog/react-rendered-more-hooks-than-during-previous-render
		-
- [[Oct 30th, 2022]]
  collapsed:: true
	- Pragmatic Programmer is a book everyone should read at the start of their
	  career. The earlier the better.
	- fav lessons from prag prog via [[The senior Mindset]]
		- DRY
			- The beginner thinks DRY and bends over backwards to avoid duplicating her
			  code.
			- The expert thinks DRY and copy pastes code to avoid duplicating the architec-
			  ture.
			- **Duplicate your code, not your intent. Just because it looks the same doesn’t
			  mean it is the same.**
		- engineering daybooks
			- Keep a notebook. Write down your thoughts and ideas. When you get dis-
			  tracted, you can look it up. When you come back to some code 2 weeks later,
			  you can look it up.
			- As the old proverb from the balkans says: Budala pamti, pametan piše. The fool
			  remembers, the clever one writes.
		- **dont outrun ur headlights**
			- Build only as much as you can test. Run your code early, run it often.
			  Don’t code for 2 hours then see if it works. You’ll ﬁnd it’s hard to tell which
			  change broke your program.
			- Test your code after every signiﬁcant change.
			  What’s signiﬁcant depends on many factors. When you’re new to a codebase
			  you’ll make smaller steps than when it all ﬁts in your head.
		- **programming as transforms**
			- When you think of code as a series of transformations, your life will be easier.
			  Small discrete steps, rather than large objects and codebases.
			- Spend an afternoon learning about functional programming.
		- inhertiance tax
			- Are you using inheritance to share code? Try mixins or traits.
			  Are you using inheritance to build types? The real world never ﬁts a clean
			  taxonomy. Try interfaces instead.
			  “Can do X” trumps “Is a X”.
		- shared state is incorrect state
			- Modern computing is full of concurrency and parallelism. Anything you build
			  has to deal with this reality.
			  Shared state is your enemy.
			  Immutable shared state and mutable local state are your friends. Avoid relying
			  on state others may have changed.
		- verify why code works till u r certain
		- delight your users
			- “Your users are not particularly motivated by code. They have
			  a business problem that needs solving within the context of
			  their objectives and budget.”
			- The biggest danger to a software team is a client that limits their ask based
			  on perceived software limitations. Encourage clients to ask for their wildest
			  dream. Work together to ﬁnd a solution.
			- **Their goal is not the tool, their goal is what your tool enables them to do.**
			- **
- [[Nov 8th, 2022]]
  collapsed:: true
	- logbook is only good for retro and planning, not reading
	- clear focused tasks are better
	- leo ought to be done by tomorrow afternoon if hackathon tonight
	- then fitness factory designs mail by tom evening and then meet post movie for lunch
	-
- [[Nov 10th, 2022]]
  collapsed:: true
	- inactivity is the biggest prod killer especially paired with phone
	-
- [[Nov 17th, 2022]]
  collapsed:: true
	- small att span can lead to creativity
		- but imperious that u know what highlight is
		- probably better of learning scheduling from others
		-
- [[Dec 27th, 2022]]
  collapsed:: true
	- [[How to track your coding]]
	-
- [[Jan 8th, 2023]]
  collapsed:: true
	- generic to specific url
- [[Jan 9th, 2023]]
  collapsed:: true
	- warmup -> 1-2 hours
	- first distraction : 1-1.30 => ideal time to help
		- schedule app blockers for then
	- yotube cast is nice feature
- [[Mar 15th, 2023]]
  collapsed:: true
	- Morning session
		- deep work logged -> 90 minutes
		- Essential to calm down mind through workout and journaling in order to focus on the task at hand
		- warmup rituals help but shd be limited to 15 mins and non strenous
		- define target beforehand, u will fail at it but 90 minutes proper shot cant be excused
		- better to leave mental processing and planning tasks post the fist deep work session
		- site will take shape only when content in input. dont wait for client always.
			- sturcture -> apply story (store inspirations ) -> test
				- is the cycle
			- one sprint at end of day to add resources to site, so that reDY to work the next day.
			- Start learning only when stuck. dont chicken out by starting with it.
- [[Mar 18th, 2023]]
  collapsed:: true
	- another morning wasted to ambiguity
	- not pumped at night -> noy waking up with energy
		- keep ph away and build inspiration at night
- [[Mar 27th, 2023]]
  collapsed:: true
	- design requires a clear head
	- focusing on one context
	- design by curiosity and then apply rules
	- Products page needs to lead back to our work
- [[Mar 28th, 2023]]
  collapsed:: true
	- be sure about tools you use -> figma fiasco
	- future of design -> ai + low code -> webflow and framer
	- move away physically time to time. to speed up design
- [[Apr 4th, 2023]]
  collapsed:: true
	- eaqrly morning
		- first time logging early morning shift
		- great for deep work and pre planned task -> ban mobile internet and feelings
		- for notion dashboard make it easy to id which project the task belongs to
		- https://www.superlist.com/ copy for leo
		- fitnessgpt
	- afternoon
		- start time -> 12.15 pm => shd be 10.15
		- sleep when sleepy but do get clarity until then
		- best strat -> instant deep work or instant workout
		- good pace when focused on one project but need more physical breaks in between for smoth context switch. Dont fall prey to shallow work during liminal moments
		-
- [[Apr 10th, 2023]]
  collapsed:: true
	- coworking cafe hunter goa -> review page
	- price tier list ?
	- better if had worked in lib
	- old grumpy couple
	- tie spacekayak content writer to agency long term goal
		- cover story on huddle01
	- 15th star party not possiblw -> try 22nd
	- deliverables on saturday 4pm
		- fitness factory site
		- leo site
		- tql design options (can start on sat) -> what can be prepped till sat ?
		- newsletter
		- one app
		- break down sites into deliverable checkpoints (highlight for tomorrow)
		- thursday and friday -> hackathons => do aadhar on wednesday => whole day wed outside ?
		- sagar bday ?
		- recall roadblocks -> HMW ?
- [[Apr 22nd, 2023]]
	- morning half wasted -> need one proper small task to complete and then something to learn
	- paralysis by analysis
	- how about tying everything to writing ?
	- afternoon sprint (1-3)
		- freelancer plan webflow -> 4k
		- will only be able to justify if stargazing site
		- tql focus ->
		-