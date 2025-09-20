React + Vite Jokes App 🎭

This is a React application built with Vite that fetches and displays jokes using an external Jokes API (with API key authentication).
It demonstrates how to integrate APIs in a modern React environment with Hot Module Replacement (HMR) and ESLint rules for cleaner code.

🚀 Features

Built with React + Vite for fast development.

Fetches random jokes from an API using an API key.

Supports HMR for instant updates.

Includes ESLint configuration for maintaining code quality.

Responsive and minimal UI.

🛠️ Tech Stack

React (Frontend)

Vite (Bundler + Dev server)

Axios / Fetch API (for API calls)

ESLint (code linting rules)

CSS / Tailwind / Styled Components (for styling, based on preference)

📦 Installation

Clone the repository:

git clone https://github.com/your-username/jokes-app.git
cd jokes-app


Install dependencies:

npm install


Run the development server:

npm run dev

🔑 API Key Setup

Register at the jokes API provider’s website.

Get your API key.

Create a .env file in the root directory:

VITE_API_KEY=your_api_key_here


Restart the dev server after adding the key.

⚙️ ESLint & Plugins

Currently, two official plugins are available:

@vitejs/plugin-react → uses Babel for Fast Refresh.

@vitejs/plugin-react-swc → uses SWC for Fast Refresh.

Expanding ESLint configuration

For production apps, it’s recommended to use TypeScript with type-aware lint rules.
Check out the Vite + React + TS template
 for details on integrating typescript-eslint.

📚 Future Enhancements

Add joke categories (Programming, Dad jokes, etc.).

Save favorite jokes to local storage.

Share jokes on social media platforms.

🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch (feature-xyz)

Commit your changes

Submit a pull request
