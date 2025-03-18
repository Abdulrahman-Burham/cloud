# Static Site Server

This project is a simple static site server that serves HTML, CSS, and JavaScript files. It is built using TypeScript and Express.

## Project Structure

```
static-site-server
├── public
│   ├── index.html        # Main HTML document for the static site
│   ├── styles.css       # CSS styles for the static site
│   └── scripts.js       # JavaScript code for interactivity
├── src
│   └── server.ts        # Entry point for the server application
├── package.json         # npm configuration file
├── tsconfig.json        # TypeScript configuration file
└── README.md            # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd static-site-server
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Compile TypeScript:**
   ```
   npm run build
   ```

4. **Run the server:**
   ```
   npm start
   ```

## Usage

Once the server is running, you can access the static site by navigating to `http://localhost:3000` in your web browser. The server will serve the files located in the `public` directory.

## License

This project is licensed under the MIT License.