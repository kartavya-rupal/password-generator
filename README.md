# Password Generator
A powerful and customizable Password Generator application built using React.js, Vite, and Tailwind CSS. Generate strong, secure passwords effortlessly to enhance your online security.

## Features

- **Customizable Password Length**: Adjust the length of the password to suit your needs.
- **Options for Characters**:
  - Include **numbers**.
  - Include **special characters** (e.g., `@`, `#`, `$`).
  - Use **uppercase** and/or **lowercase** letters.
- **Copy-to-Clipboard Functionality**: Quickly copy the generated password to your clipboard.
- **Real-Time Updates**: See the password update dynamically as you modify settings.
- Responsive and modern UI built with **Tailwind CSS**.

## Built With

- [React.js](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [Vite](https://vitejs.dev/) - A fast development build tool for modern web projects.
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.

## Project Structure 
```
├── public/            # Static files
├── src/               # Main application code
│   ├── components/    # Reusable React components
│   ├── App.jsx        # Main app component
│   ├── index.css      # Tailwind CSS imports
│   └── main.jsx       # React entry point
├── package.json       # Project dependencies and scripts
├── postcss.config.js  # Tailwind CSS PostCSS configuration
├── tailwind.config.js # Tailwind CSS configuration
└── vite.config.js     # Vite configuration
```
## Usage
1. Open the application in your browser.
2. Adjust the password length using the slider or input box.
3. Toggle options for numbers, special characters, or uppercase letters.
4. Click the Generate Password button to create a new password.
5. Use the Copy button to copy the password to your clipboard.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
