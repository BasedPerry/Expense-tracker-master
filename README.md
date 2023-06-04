## Overview
The Expense Tracker is a React.js project designed to help users track their income and expenses. It provides a simple and intuitive interface for managing financial transactions and gaining insights into one's financial activities. With this application, users can easily add, view, and delete transactions, while also seeing their current balance, total income, and total expenses.

![Expense Tracker Screenshot](./screenshot.png)

## My Process
During the development of this Expense Tracker React.js project, I followed a structured workflow to ensure efficiency and maintainability. Here are the key aspects of my process:

### Project Structure
The project has a well-organized structure, separating components, styles, and the context API. The components are grouped in the `components` folder, while the context and global state management reside in the `context` folder. This structure promotes modularity and scalability, allowing for easy addition or modification of components.

### Key Components
- **Header**: Renders the title of the Expense Tracker application.
- **Balance**: Displays the current balance by summing up the amounts of all transactions.
- **IncomeExpenses**: Shows the total income and expenses. It calculates the income by summing up the positive amounts and calculates the expenses by summing up the negative amounts.
- **TransactionList**: Renders a list of transactions by mapping over the transactions array and rendering individual Transaction components.
- **Transaction**: Represents a single transaction item, displaying the transaction text, amount, and a delete button.
- **AddTransaction**: Provides a form for users to add new transactions. It captures the text and amount inputted by the user and adds the transaction using the addTransaction function from the context API.

### State Management
The state management of this Expense Tracker app is achieved using the React Context API. The `GlobalProvider` component wraps the entire application, providing access to the `transactions` state and the `addTransaction` function throughout the components. This approach ensures consistent data flow and simplifies the management of shared state.

### Styling
For styling the components, I used CSS stylesheets and the CSS-in-JS approach with the help of the `App.css` file. The CSS classes are applied to the respective elements in the components, allowing for consistent and visually appealing styling across the application.

### Testing
Testing for this project was not mentioned, but it is recommended to include tests for critical functionalities using testing libraries such as Jest and React Testing Library. Writing tests ensures the reliability and stability of the application, especially when making future modifications.

## What I Learned
During the development of this Expense Tracker React.js project, I gained valuable insights and knowledge in the following areas:
- Implementing state management using the React Context API to share data across components.
- Working with functional components and utilizing hooks like useState and useContext for state management.
- Creating reusable components with clear responsibilities and separation of concerns.
- Applying CSS styles using traditional stylesheets and the CSS-in-JS approach.
- Using mapping and iteration techniques to render dynamic lists of components based on data.
- Developing an intuitive user interface for managing financial transactions.

## Continued Development
While the Expense Tracker app provides essential functionality for tracking income and expenses, there are several areas for future enhancement and continued development:
- Implementing data persistence: Storing transactions in a backend server or a database for data persistence across sessions.
- Adding authentication: Incorporating user authentication and user-specific transaction management for personalized experiences.
- Filtering and sorting: Enhancing the transaction list with features like filtering by date, category, or type, and sorting based on different criteria.
- Data visualization: Incorporating charts and graphs to visualize spending patterns and trends.
- Enhancing the user interface: Improving the overall design and user experience with a more polished and responsive UI.

## Useful Resources
During the development of this Expense Tracker React.js project, I found the following resources helpful:
- [React Documentation](https://reactjs.org/): Official documentation for React.js, providing comprehensive guidance on component-based development and React concepts.
- [React Context API Documentation](https://reactjs.org/docs/context.html): Detailed documentation on the React Context API, explaining its usage, patterns, and best practices.
- [CSS Tricks](https://css-tricks.com/): An extensive collection of CSS-related articles, tutorials, and tips for styling web applications.
- [Styled Components Documentation](https://styled-components.com/docs): Documentation for Styled Components, a CSS-in-JS library for creating styled React components.

## Author
This Expense Tracker React.js project was developed by Brandon Perry. Connect with me on [LinkedIn](https://www.linkedin.com/) and check out my [portfolio website](https://brandonperry.dev) for more projects and work samples.

## Acknowledgments
I would like to acknowledge the team at OpenAI for developing the powerful GPT-3.5 language model, which assisted in generating the content and structure of this README file.
