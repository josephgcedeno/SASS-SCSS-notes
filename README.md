## SCSS OR SASS HOW TO INSTALL AND HOW TO USE.


- **Ubuntu user installation:** sudo apt install sass 

- **Verify Installation:** sass -v 

- **The source and destination (S:D):** sass src/scss/styles.scss:dist/css/style.css

- **Run/execute file:** sass src/scss/styles.scss:dist/css/style.css

- **Run/excute as file and watch updates every time:** sass --watch src/scss/style.scss:dist/css/style.css

- **Run/excute as folder and watch updates every time:** sass --watch src/scss:dist/css . `Name of the distination file will be base from the src file scss.
eg. src: styles.scss - dist: styles.css `

- **Formating output from scss 3 types:** 
	1. sass --watch src/scss:dist/css --style compact
	2. sass --watch src/scss:dist/css --style compressed
	3. sass --watch src/scss:dist/css --style expanded 

- **Check the example sources at:** src/scss/base/*

- **Check the example output at:** dist/css/*

- Note partialsfiles named as **"_filename.scss"** imported as @import 'filename' dont mind at the extension and even the `"__"`
