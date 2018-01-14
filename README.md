
### Credits to Udemy Course ["Getting Started With VueJS"](https://www.udemy.com/getting-started-with-vue-js/learn/v4/overview)

### Google Doc Notes link [here](https://docs.google.com/document/d/1tfcJSZgpkZox7Bwo6Xlnuls_ABAc7iKtwhp92kGYmXM/edit?usp=sharing)

2.2 Start - End
---------
### Using in-line templates.
(isn't recommended to be used a lot)
```javascript
Vue.component('login-dialog-component', {
    //code here.
})
```
In HTML
```javascript
<login-dialogue-component inline-template>
    <!--HTML code here-->
<login-dialogue-component>
```
2.3 Start - End
---------
### Using X-Templates.
```javascript
<script type="text/x-template" id="login-dialogue-component">
<script>
```
2.4 Start - End
---------
### Using Render Functions.
