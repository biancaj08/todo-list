# React + Vite


This application is a Todo List app

Setup

Fork and clone locally: Fork the CTD repository to your GitHub account, then clone your fork to your local machine
Install dependencies: Run npm install to install all required packages

Start the development server with the command: npm run dev
Open a browser and navigate to http://localhost:5173.
Delete the contents of App.css but keep the file.
Delete the contents of index.css but keep the file.

Clean up App.jsx's code:
Delete the line containing const [count, setCount] = useState(0)
Remove all imports except for App.css
Replace everything in the return statement with a div containing an h1 containing your app's title.

In App.jsx:

Inside the App component, above the return statement, create an array named todoList containing 3 empty objects.
Populate each object with a todo using the following object keys: id and title.

Create an unordered list using html tags below the heading (h1).
Place an empty code block between the list's opening and closing tags. eg:<ul>{}</ul>
Inside the code block, map over the todoList to wrap each todo title in a list item tag.
Add the key prop to the list item and pass it the todo's id.

