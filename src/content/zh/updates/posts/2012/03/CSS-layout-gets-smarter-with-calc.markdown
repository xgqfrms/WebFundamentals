#
[WebFundamentals](https://github.com/google/WebFundamentals/blob/master/src/content/en/updates/posts/2012/03/CSS-layout-gets-smarter-with-calc.markdown)

[WebFundamentals_CN](https://github.com/google/WebFundamentals/blob/master/src/content/zh/updates/posts/2012/03/CSS-layout-gets-smarter-with-calc.markdown)

***
***

### HTML5 CSS3 

# CSS-layout-gets-smarter-with-calc

*[example](http://www.imooc.com/code/4395)

    .container {
			width: 560px; 
			height: -webkit-calc(100vh - 16px); 
			height: calc(100vh - 16px);
			margin-left: auto; margin-right: auto;
			background-color: #fff;
		}
