## ECMAScript 2015 Presentation

### How to start this presentation

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/) (1.0.0 or later)

1. Clone this repository
   ```
   git clone https://github.com/marcinru/es2015.git
   ```

1. Navigate to the folder where you cloned the repo
   ```
   cd es2015
   ```

1. Install dependencies
   ```
   npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```
   npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.