# Skeleton Framework
A simple responsive framework for mobile friendly development. 
Skeleton Framework takes its roots from [dhg/Skeleton](https://github.com/dhg/Skeleton), and builds upon the same basic principles.

## Development
Skeleton Framework is developed with [node.js](https://nodejs.org), [gulp](http://gulpjs.com/), and [postcss](https://github.com/postcss/postcss).

### Install Development Dependencies
`npm install --global gulp` 
This is optional, as npm can build Skeleton Framework for you.

In the project root folder run `npm install` to install the local dependencies.

#### Develop with gulp:
* `gulp dev` - Creates a development build of Skeleton Framework.
* `gulp watch` - Watches the source files and runs `gulp dev` on file change.
* `gulp prod` - Creates the production ready, minified and non-minified versions of Skeleton Framework.

#### Develop with npm:
* `npm run dev` - Creates a development build of Skeleton Framework.
* `npm run watch` - Watches the source files and uses local copy of gulp to run `gulp dev` on file change.
* `npm run prod` - Creates the production ready, minified and non-minified versions of Skeleton Framework.

### Project Structure
```
.editorconfig         // Defines Code Syntax (please follow these guidelines if your editor does not support .editorconfig)
.gitignore            // Defines Git Ignores
gulpfile.js           // Defines Gulp Build Tasks
LICENSE               // MIT License File
package.json          // node.js Package File
README.md             // Skeleton Framework README
src                   // Source folder
 |-test.html          // Test File
 |-skeleton.css       // Main CSS File
 |-css                // Styles Folder
    |-base.css        // Default Base Styles
    |-code.css        // Default Code Block Styles
    |-grid.css        // Default Grid System
    |-root.css        // Default Root Document Variables
    |-tables.css      // Default Table Styles
    |-utils.css       // Default Utility Styles
    |-buttons.css     // Default Button Styles
    |-forms.css       // Default Form Styles
    |-lists.css       // Default List Styles
    |-spacing.css     // Default Spacing
    |-typography.css  // Default Typography
images                // Images Folder
 |-favicon.png        // Default Favicon (generated by gulp, remembered by git)
dist                  // Distributed Folder
 |-skeleton.css       // Unminified Stylesheet
 |-skeleton.min.css   // Minified Stylesheet
dev                   // Development Folder (generated by gulp, ignored by git)
 |-test.html          // Test File Copy
 |-css                // CSS Folder
    |-skeleton.css    // Unminified Stylesheet
```

## Usage
Install the sources into your node app via `npm install --save-dev skeletonframework`.

Install the compiled version into your frontend via `bower install skeletonframework`.