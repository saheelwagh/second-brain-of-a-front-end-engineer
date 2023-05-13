- Decoding confusion while reading code
	- possible scenarios for confusion in  coding
		- new ideas or paradigms
		- purpose behind existing code
		- new terms and jargon in business
		- Lack of knowledge
			- not knowing syntax #card
			-
			- **not enough relevant facts are present in your Long term memory**
		- lack of info
		  collapsed:: true
			- about inner working (u can understand purpose from name)
				- might require going through docs
				- and this info is not readily available in the code but needs to be found somewhere else
				- can be improved by faster nav
			- **Challenge for short term memory**
		- lack of processing power
		  collapsed:: true
			- hard to hold intermediate values
			- **overloading working memory**
			- tools like paper pen can help here or whiteboard
	- Processes in prog
		- LTM and programming
			- Your  LTM  stores  several  types  of  relevant  programming  information.  It  can,  for example,  store  memories  of  when  you  successfully  applied  a  certain  technique,  the meaning of keywords in Java, the meaning of words in English, or the fact that maxint in Java is 2147483647.
				- js or ts equivalent ?
				-
			- comparable to hard drive
			- very hard to read code if you cannot retrieve from memory while knowing it makes it trivial
			- therefore you need some sort of daily practice to enrich your ltm
				- syntax kjnowledge
		- STM in programming
			- briefly holds info
			- limited size
			- used to store variables and data structures
			  collapsed:: true
				- apply to js array methods
				-
			- emptied after use
			- like RAM
			- quick logging is good
		- Working memory in programming
			- [[code tracing]]
				- when tracing u feel like noting values outside
					- indicates that working memory is fulll
					-
	- All process work together
		- info => filter -> STM -> working or LTM -> working
		-
	-
- Speed reading for code
	- approx 60% of programmer's working life is spent in understanding code, not writing
	- when we start learning coding the focus is on producing code
	  collapsed:: true
		- LATER  course on reading code for beginner programmers
		-
	- chunks improve your  stm
	  collapsed:: true
		- Adrian de Groot chess expt
		- grouping like 'scissilian opening'
		- chunking in code
			- expert coders can remember code better than beginners
			  collapsed:: true
				- i/o buffer -> stores infrom rom peri devices
					- similarly sensory mem stores sight hearing taste smell touch
						- as coders let's focus on sight -> iconic mem
						-
			- all coe u read is stored in iconic mem but not all of it can be processed by STM
			  collapsed:: true
				- What is the structure of the code?–   I
					- is the code nested deeply or it is flat?–
					- Are there any lines that stand out
					- How is whitespace used to structure the code?–
						- Are there gaps in the code?–
						- Are there large blobs of code?
	- beginners emphaises on meaning (true is real) experts emphasize place of usage and toghetherness (if then else)
	- how to write chunkable code
	  collapsed:: true
		- short answer : use design patterns
		- comment well
		  collapsed:: true
			- only when explaining a chunk
			-
		- leave beacons
			- right comments, var names . fields, right usage of strings
	- LATER do exercise from ch 2 of prog brain
	-
- how to read complex code
	- stm -> remember
	- working mem -> process
	- sort loc by intrinsic and extraneus load
	- tech to reduce load
	  collapsed:: true
		- refactoring
		- use ternary, lambda etc only when you know them well enough
			- use flashcards to remeber such constructs
			-
		-
	- memory aids for working mem
		- 2 ways a complicated structure can overload the working mem
		  collapsed:: true
			- you may not know exactly which part of the code u need toread. thus reading more
			- second, u might need to go to location of defn to go and understand it and also make sense of the current location
			-
		- **creating a dependency graph**
		  collapsed:: true
			- 1. Circle all the variables
			  2. link sim vars with lines
			  3. circle all method calls
			  4. link them to their defns
			  5. cirlcle classes 
			  6. link with their instances
		- **using a state table**
			- when cause of confusion is not the code structure but the calculations that it performs
			- 1. List all vars
			  2. table -< each car its own col
			  3. row per distinct execution step
			  4.  note
			- LATER  article on using state table for react code
			- LATER check out pythontutor
			-
			-
		-