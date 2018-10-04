# REACT

Components -> self-sustaining, independent micro-entities that describe a part of UI.
Props -> Inputs to a function.read only
State ->  object that is owned by the component where it is declared

props -> Component -> DOM


- Stateful Components

Stateful components have a state that gets initialized in the constructor. 

constructor(props) {
  super(props);
  this.state = { count: 0 };
  
- Stateless Components
 
 const Hello = ({ name }) => (<div>Hello, {name}!</div>);
 
 
Class components should always call the base constructor with props.

 PureComponent-> Given an input and state the output remains constant always.
 
 
 Pass credentials from the app add credentials:'include' in your rest calls
 
Steps to create a react-project

npm 
sudo npm install -g create-react-app
create-react-app projectName
cd projectName
npm start

npm run build -> Creating prod build



https://www.kirupa.com/react/setting_up_react_environment.htm
