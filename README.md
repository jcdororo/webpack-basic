# webpack 설치
`$ npm init -y`      
package.json 파일 생성   
`$ npm i -D webpack webpack-cli`   

# webpack loader
웹팩이 웹 애플리케이션을 해석할 때 자바스크립트 파일이 아닌 웹 자원(HTML, CSS, Images, 폰트 등) 들을 변환할 수 있도록 도와주는 속성.   
`$ npm i -D css-loader style-loader sass sass-loader`

# HTML Webpack Plugin
HtmlWebPackPlugin 은 웹팩이 html 파일을 읽어서 html 파일을 빌드할 수 있게 해 준다.   
`$ npm i -D html-webpack-plugin`   

# Webpack Caching
웹팩(Webpack) 컴파일로 생성된 파일에서 변경된 내용이 없다면 브라우저는 캐시 상태를 유지하고 그대로 사용하게 된다.   
여기서 브라우저가 변경사항을 확인하는 방법 중 하나는 파일 이름이며 그렇기 때문에 파일을 생성 할 때 해쉬값을 줄 수 있다.   

# Babel Loader
ES6이상의 자바스크립트 코드는 인터넷 익스플로러 혹은 구버전 브라우저에서 지원이 안되는 경우가 있는데   
그렇기 때문에 이러한 구버전 브라우저에서도 최신 자바스크립트 코드로 이루어진 앱을 이용할 수 있게 ES5 이하의 코드로 프랜스파일링 하도록 하는 기능이 바벨.   
그리고 웹팩으로 파일을 번들링(bundling)할 때도 바벨을 사용할 수 있게 해주는 것이 babel-loader   
`$ npm install -D babel-loader @babel/core @babel/preset-env`