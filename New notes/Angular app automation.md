**Angular app automation**



We need to use ng-webdriver to automate Angular-based applications. Since Angular or Angular-based applications will use Protactor to automate the test, but we can also do using Java Selenium using this ng-webdriver library.

Protractor is based on Javascript and TypeScript

AngularJS application is used generally for single-page application, where the data is very dynamic, where the HTML content is dynamic, and it is used with Angular framework. So Angular is a JavaScript framework. JavaScript technology, UI developers, they are using Angular provided by Google, and people are using that. Now after Angular 2, we don't call AngularJS, we call only Angular.



But in Angular application, guys, what happens? If you talk about Angular application, in Angular application, there are some different types of contents that are available. So we have, let's see, if you've seen ng-binding is there. Then we have ng-model is there. Then we have ng-something like this. Options are available. So these are the different HTML tags that are available. So wherever you see that, OK, something like this, ng-model, ng-binding, ng-receptor, or ng-repeater, or ng-options, or ng-modeling, something like this, OK, it means that is an Angular-based application.



Can I use WebDriver Java? Yes, we can do that without any problem. So, for such application, what you can do that is, you can simply use that. You can create your own XPath and everything. You can do that for these applications. Like, let's see, XPath and the rate ngBind is equal to something like this. Or, simply you can do that. Or, as a selector, you can do that. With the proper custom wait mechanism, you can use a proper explicitly wait, or custom wait, or fluent wait, you can use that. Proper synchronization, custom synchronization, you can write, and then you can do that. But sometimes, what happens is, your custom JavaScript code, sorry, custom WebDriver wait also is not working, or explicitly wait is also not working, your synchronization is not happening properly, and then you start getting some failure cases, and all those things, and then, today it's working, tomorrow it's not working, with a typical normal WebDriver Java and Python. That is a problem. We have seen that for Angular-based applications I'm talking about. Right, I'm not talking about the normal application, I'm talking about Angular or AngularJS-based applications.



First of all, why it's difficult to automate AngularJS applications with WebDriver and Java? Because what happens is that Angular renders dynamic content. Whenever any action is performed on the web page, like you're clicking on a button or you're clicking on a link or something like this, what happens is that an action is rendered behind the scene, in the backend. So, let's see if there is an AngularJS application, and you simply fill this particular form, and there is a button is there, one submit button is there. The moment you click on this particular submit button, what happens is that you're clicking on this particular button, some backend process will render, and one request will be sent to the server, this is my backend server, and then you get the response or let's say you're doing a POST call or GET call or whatever you are doing it, and then, by the time everything is happening in the backend, and then you have to write a custom JavaScript code over there, as a UI developer, that this JavaScript will find what is the state of this particular request that we have sent, and once we get the response from the server, then only the result will be displayed on the UI. So this is a typical mechanism of JavaScript AngularJS engine. So, with this situation, our normal WebDriver Java synchronization won't work. That is the first problem. Sometimes.



And the second problem is that the different locators that, okay, different, you know, HTML tags and, okay, locators that Angular applications they are using, we don't have any support for in Java and Ruby and Python because we have By.id, class name, name, tag name, xpath, CSS selectors, link text, and partial link text. We don't have any ngBind or let's say py.ngbinding or py.model or py.options. We don't have those things. So that's why we have to use Protector for that.



