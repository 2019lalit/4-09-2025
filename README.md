// Step 1: Import dependencies
const root = document.querySelector('#root'); // Select the root div

// Step 2: Create a React element
const element = React.createElement("h1", null, "Hello, React World!");

// Step 3: Render the application
const reactRoot = ReactDOM.createRoot(root);
reactRoot.render(element);
