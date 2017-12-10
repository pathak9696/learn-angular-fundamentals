step 1: 
Create index.html

step 2: 
In index.html add 'demo-app' element.
<demo-app></demo-app>

step 3: 
Now create demo-app component using angular 

1. create a file called demo-app.component.ts (ts stands for typescript)
2. export class DemoAppComponent
3. You need a component to register the tag demo-app. Use @Component({}) syntax
4. ... 
5 ...

step 4: 
Create appModule and register demo-app into appModule

1. Create a file called app.module.ts
2. import DempAppComponent
3. export AppModule
3. register 

step 5: 

1. Create a main.ts file and register AppModule
2. use @angular/platform-browser-dynamic

step 6: 

1. npm install systemjs
2. Import script into index.html
3. create systemjs.config.js 
4. import systemjs.config.js to index.html
5. System.import('app').catch(function(err) {console.error(err)})

Creating systemjs.config.js

(function(global){
 System.config({}) // this object accepts three properties paths, map and packages
})(this)


