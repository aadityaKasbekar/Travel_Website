[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/J4-IMa8v)

# HTML CSS Assignment 4

Welcome to Assignment 4 of the HTML CSS project! In this assignment, we'll be enhancing the web page created in Assignment 3 by adding a layout as per the provided mock image. Additionally, we'll be converting all CSS to SCSS syntax and organizing it into modular files. The goal is to learn about CSS positioning, Grid layout, Flexbox, and SCSS features like variables, mixins, inheritance, control statements, functions, and operators.

## Installing Sass Package Locally <a href="https://sass-lang.com/install/">(click here!)</a>

Sass can be installed locally in the project directory itself, allowing you to manage dependencies more efficiently and ensuring consistency across different environments.

### Procedure for Installing Sass Locally:

1. **Initialize Node.js project:**
   If you haven't already, navigate to your project directory in the terminal or command prompt and initialize a Node.js project by running the following command:

   ```
   npm init
   ```

   This will create a `package.json` file in your project directory, which is used to manage dependencies.

2. **Install Sass as a Development Dependency:**
   Sass should be installed as a development dependency of your project. Run the following command in the terminal or command prompt to install Sass locally:

   ```
   npm install -save sass
   ```

3. **Verify Sass Installation:**
   After installing Sass, you can verify its installation by checking the `package.json` file or running the following command in the terminal or command prompt:

   ```
   npm list sass
   ```

   This command should display the installed version of Sass in your project directory.

4. **Compile Sass to CSS:**
   Once Sass is installed locally in your project, you can start using it to compile Sass files (`.scss` or `.sass`) into CSS. You can create a script in the `package.json` file to compile Sass files. For example:

   ```json
   "scripts": {
    "sass-dev": "npx sass scss/main.scss dist/main.css --watch",
    "sass-prod": "npx sass scss/main.scss dist/main.css --style compressed",
    "sass": "npx sass scss/main.scss dist/main.css"
   }
   ```

   You can then run the script in the terminal or command prompt using the following command:

   ```
   npm run sass
   ```

   ## Development

   Run `npm run sass-dev` command in the terminal for building the css and the built css will be available under `dist/`. This command also watches the changes and continously rebuilds the css.

   ## Production

   Run `npm run sass-prod` command in the terminal for building the css and the built css will be available under `dist/`. The built css will be minified.

## Hope you were able to install and run SASS package successfully. Now lets talk about assignment below:

## Layout Enhancement

The layout enhancement involves adding a layout structure based on the provided mock image. This includes positioning elements using CSS Grid layout and Flexbox to achieve the desired UI.

## SCSS Conversion

All CSS code from Assignment 3 will be converted to SCSS syntax. The SCSS will be organized into multiple files based on UI features, common elements, and themes. This modular approach will help in maintaining and scaling the CSS codebase efficiently.

### SCSS Features Utilized:

- **Variables**: Used for defining reusable values such as colors, font sizes, etc. Variables are declared in the file present in `scss/_variables.scss`.

- **Mixins**: Employed for reusable blocks of styles that can be included across different selectors. Mixins are declared in the file present in `scss/_mixins.scss`.

- **Inheritance**: Utilized to inherit styles from one selector to another.

- **Control Statements**: Employed for conditional styling based on certain criteria.

- **Functions and Operators**: Used for performing operations and calculations within stylesheets. Functions are declared in the file present in `scss/_functions.scss`.

## Implementation Details

All SCSS code will be organized into modular files as follows:

- Variables: `scss/_variables.scss`
- Mixins: `scss/_mixins.scss`
- Layouts: `scss/_layouts.scss`
- Fonts: `scss/_fonts.scss`
- Functions: `scss/_functions.scss`

The use of these files will ensure a structured and maintainable SCSS codebase, allowing for easy customization and scalability.

- The navbar is fixed on the viewport using CSS positioning.
- JavaScript is not used.
- Table elements will not used for formatting.
- Code documentation is added using SCSS comments for better code understanding and maintainability.

## External Resources <a name="external-resources"></a>

External resources are used to enhance the styling and functionality of the project. Notable resources include:

- **Google Fonts**: Stylish fonts are fetched from Google Fonts to improve text presentation. [Google Fonts](https://fonts.google.com/)

- **Ionicons Library**: Icons used in the project are loaded from the Ionicons library. [Ionicons](https://ionicons.com/)

## Conclusion

By completing this assignment, gained hands-on experience in implementing complex layouts using CSS positioning, Grid layout, and Flexbox. Additionally, became familiar with SCSS features and best practices for organizing and maintaining CSS code.

Thank you for your participation and dedication to learning web development! If you have any questions or need further assistance, feel free to reach out. Happy coding!

## Submitted By
###     Aaditya Kasbekar
