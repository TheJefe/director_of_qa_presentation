# Quality Assurance Strategy

This is a presentation I gave about a general Quality Assurance Strategy as part of an interview for a Director of Quality Assurance Position.

#### [View Slides](https://thejefe.github.io/director_of_qa_presentation/)

## Presentation Frameworks is [Reveal.js](https://github.com/hakimel/reveal.js)

### SETUP

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

1. Clone the repository
   ```sh
   $ git clone https://github.com/TheJefe/director_of_qa_presentation.git
   ```

1. Navigate to the picture_this folder
   ```sh
   $ cd director_of_qa_presentation
   ```

1. Install dependencies
   ```sh
   $ npm install
   ```

1. Serve the presentation and monitor source files for changes
   ```sh
   $ npm start
   ```

1. Open <http://localhost:8000> to view your presentation

   You can change the port by using `npm start -- --port 8001`.
   
### Driving the presentation from another device

1. Start the server with
   ```sh
   $ node plugin/notes-server
   ```

   Open the slides at http://localhost:1947
