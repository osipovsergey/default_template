# Default Template
Webpack 5 + Vue 3 + Less + JEST + PostCSS

### Install
  1) **Clone repository:**<br/>
     - HTTPS: ```git clone https://github.com/osipovsergey/default_template.git name_your_folder```<br/>
     - SSH: ```git clone git@github.com:osipovsergey/default_template.git name_your_folder```
  2) **Go to project folder:**<br/>
     - ```cd name_your_folder```
  3) **Install npm-packages:**<br/>
     - ```npm i```

### Run project
  1) **Dev mode**:
     - ```npm run dev```<br/>
     *PORT: 8080*<br/>
  2) **Production mode**
     - ```npm run build```

### Test
  Framework "JEST" is used to test .vue and .js, .json files.<br/>
  1) **Run test:**<br/>
     - NPM: ```npm run test```
  2) **Test generate coverage reports in "coverage" folder.**

### Mixins for LESS and Vue <style>
  - **mixins.less** -- main file for import file with mixins;
  - **colors.less** -- mixins for colors<br/>
  - **fonts.less** -- mixins for fonts<br/>
  - **media_queries.less** -- mixins for media-queries;<br/>

### Webpack Bundle Analyzer
  1) **Create folder stats:** ```mkdir stats```<br/>
  2) **Generate stats file for Webpack Bundle Analyzer:** ```npm run genstats```<br/>
  3) **Watch stats bundles:** ```npm run watchstats```<br/>

  or<br/>

  **When building a project:** ```npm run build``` and automatically open page with stats.<br/>

### Note
  This project is open source.<br/>
  Feedback and suggestions write to the [issue](https://github.com/osipovsergey/default_template/issues).

  P.S. This [repository](https://github.com/taniarascia/webpack-boilerplate) helped me in setting up the webpack. Thanks!

### Author:
  - [Sergey Osipov](https://github.com/osipovsergey)
