# My Node.js Website

A simple Node.js web application built using Node.js built-in HTTP and File System modules.

## Description

This is a basic website that demonstrates fundamental Node.js concepts using only built-in modules without external dependencies. The application serves static HTML pages and provides a foundation for learning Node.js web development.

## Features

- Static HTML page serving
- Built with Node.js built-in modules (http, fs)
- Simple navigation between pages
- Lightweight and dependency-free

## Prerequisites

- Node.js (version 12.0 or higher recommended)
- npm (comes with Node.js)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/adnanaiman000/nodejs-app.git
cd nodejs-app
```

2. No additional dependencies to install - uses only Node.js built-in modules!

## Usage

1. Start the server:
```bash
node server.js
```

2. Open your browser and navigate to:
```
http://localhost:3000
```

3. You should see the homepage with navigation to other pages.

## Project Structure

```
├── index.html          # Main homepage
├── another-page.html   # Additional page
├── server.js           # Node.js server file
└── README.md          # This file
```

## How It Works

The application uses:
- **HTTP module**: Creates a web server to handle requests
- **File System (fs) module**: Reads and serves HTML files
- **Path module**: Handles file path operations

## Development

To make changes:
1. Edit the HTML files for content changes
2. Modify `server.js` for server-side logic
3. Restart the server to see changes

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/xyz`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/xyz`)
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Feel free to reach out if you have any questions or suggestions!