- course strucutyr
  collapsed:: true
	- sol -> erc20 -> build our own -> stable coin -> dcent casino
- https://github.com/soliditylabs/ZTM-Solidity-Code-Repository
- Blockchain 101
  collapsed:: true
	- problem with digital money
	  collapsed:: true
		- cd anal -> cop protection concerns
			- mechnsims such as drm
			- thus we need to make money printing difficult
	- creating a digital currency
	  collapsed:: true
		- u need a way to : transfer, store and create
		- central way of store and transfer -> banks
			- has to be strictly ordered wrt timestamps
			- here u have to trust the bank
				- examples of freezing of money
			- "trust is good. control is better"
			- rupay system and chinese system contexts
		- byzentine genrals consensus
		  collapsed:: true
			- 9 armies surounding city commanded by general. how to cooordinate to attack at same time ?
			- if single mal relayes yes and no to opposing then 4 will attack and 4 wont
		- shirley : the woman with 16 personalities
		  collapsed:: true
			- Shirley Mason
			- devlpd 16 personalities during treatment
			- 100 paintings locked in her room, signed by her and personalities
			- how to verify that each general is sending only one vote ?
		- mining
		  collapsed:: true
			- halved reward coins per year
			- need a specific kind of computing power
			- 51% will cost billions
			- puzzle -> hash fn
			- hash fn
				- irrev
				- unpredictble
				- produces fingerprint(hash) that verifies what trhe og input was
				- but cant find out input via hash
				- none => no of zeros at beg via this input
			-
	- blockchain
		- block -> coll of trans -> each block conn to one puzzle min
		- forks -> disagreements over blocks
			- the longest chain always wins
		- thus u have to wait a few blocks to verify trans
		-
- ethereum dev overview
  collapsed:: true
	- architecture of a dapp
	  collapsed:: true
		- technically u onoly need to use a smart contract to called a dapp
		- almost same to fe and be but a connection to blockchain
			- backend comms with smart contract
			- smart sol contracts => truffle or hardhad to compile into evm opcode -> deploy to blockchain address
			- browser -> metamask -> give access to user's key -> site sends req to mm to sign on behalf of user
			- web3js also ethers js -> front end connection to blockchain
			- on backend u need replacment of metamask
			- infura
				- comm with blockchain -> we need to run a node on chain, run trans, and be available -> provides this service
				-
	- uniswap
	  collapsed:: true
		- swap currencies
		- erc20 tokens -> coins on eth
		- metamask sends confirmation popup
	- etherscan
	  collapsed:: true
		- for tacking eth trans
		-
	- what one needs  to be a web3 dev
	  collapsed:: true
		- front end dev to build the interface to the apis
			- connecting to meta
			- how to confirm transactions etc
		- solidity
			- compile deploy unit test local test
				- truffle and hardhat
				- ganache for local chain
					- use cli for test
				- open zeppelin refernence smart contracts
		- typescript , packagemanager, node
		-
	- some hot contracts
		- tokens
			- nfts
			- erc
		- dao
			- set of smart contr that allow roles and have decsion by voting
		- defi
			- dex
			- lending and borrow
			- decen insurance
			-
- sol
  collapsed:: true
	- strongly typed
	  collapsed:: true
		- LATER prepare table of sol types
		-
	- solc compiler
	- view and sate fns
	  collapsed:: true
		- view do not change the data
			- fn name () publicj view retunrs (type1,type2) {}
			- pure fn -> does not even read
		- state
			- payable -> can send ether with transaction
				- msg.value msg.sender
			-
		-
	- public and private
	  collapsed:: true
		- private -> only in contract  _fnname
		- external -> only from outside
	- reverting a transaction
	  collapsed:: true
		- revert()
		- requirer(myNum ==9, "number is not 9")
	- numbers
	  collapsed:: true
		- uint defaults to 256
		-
	- magic storage
	  collapsed:: true
		- declare state vars at top
		- private only within contract
		- public autogens getter and setter
		- constants and immutable
			- caps
		-
	-
	-
- erc and eip
  collapsed:: true
	- eth imp protocol
		- anything u think can imrove mech
	- eth req for comments
	- why we need these standards ?
		- token -0> sc to manage currency
			- rules to use the token
			-
- time estimate and skills at end of session
  collapsed:: true
	- erc token
	  collapsed:: true
		- types and storage -> 15 mins
		- development setup and compiling a contract -> 15 mins
		- address,mem, mapping, default values -> 30 mins
		- transfers 15 mins
		- tersting 20 mins
		- deployment hour
	- defi and stable coin
	  collapsed:: true
		- creating our own token -> 20 mins
		- arthmetic, burning and oracle -> 30 mins
		- deposit and withdrawal -> 30 mins
		- state data, libs, mathm erroes, testing -> 1hour
		-
	- dcasino
		- randomness 10 min
		- build 10 mins
		- enums and fallback fns 5 mins
		- arrays 10 mins
	-
- erc29
	- fungibl -> replacable with same kind token
	- bl -> replacable with same kind token
	- nec fns
	  collapsed:: true
		- totalsupply
		- blof
		- transfer
	-