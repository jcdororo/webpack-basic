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
