# A gist into React
## React elements: 
React.createElement(type,props,children)
React.createElement(h1,null,"hello world")

JSX helps to generate above code with below syntax.
'const element = = <h1>Hello world</h1>;'


## Lifecycle of a component:

Mounting – 
componentWillMount() – Only called once. Constructor can be used instead. Can be used to clear interval
	   render()
componentDidMount() – Runs after component output has been rendered to DOM
(used to setup timer, etc.)

Updation - componentWillReceiveProps() called when props receive something
	   setState()
	   shouldComponentUpdate()
	   componentWillUpdate()
	   componentDidUpdate()

Unmounting - componentWillUnmount()

	     
## React hooks:

Only call hooks at the top level
Call hooks only from react functional components or other hooks

useState()
useEffect()
