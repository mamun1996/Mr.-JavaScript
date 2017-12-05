# test
<a href="https://www.google.com">test</a>
<hr />

- test
  - 1
  - 2
    * 3
    
```
//<Common.js>
var Common = function(){
this.login = function(uname,password){
    //All your code that you want to call from the test spec
    element(by.id('txtUserName')).sendKeys(login);
    element(by.id('txtPassword')).sendKeys(password);
    element(by.xpath('//input[@id="btnLogin"]')).click();

};
};
```
