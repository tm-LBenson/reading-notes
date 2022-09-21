HTML Forms
[Your first Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)[How To Structure A Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

Why are forms so important in web development?
>Forms are how the server can gather inputs from a user. It can create a more personalized user experience. 


When designing a form, what are some key things to keep in mind when it comes to user experience?
> Labels on each form can make it easier to understand inputs. if the type attribute is set to password, it can protect a users privacy with passwords.
> If a form is submitted with error you should not allow the brower to reload the page preventing form data from resetting



List 5 form elements and explain their importance.  
```<form>``` tags are required when setting up any form to link all the forms to the submit  
```<button>``` is used at the end of a form to submit the form to the server  
```<input>``` is used to create multiple types of input fields such as password, button, text, even a color picker.  
```<label>``` labels are tied to each part of the form to improve the user experience. When correctly linked you can click a label to select a form.  
```<textarea>``` a dynamiclly sizable text field that allows larger messages to be typed and viewed.  

Learn JS
[Introduction To Events.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

How would you describe events to a non-technical friend?  
>events are anything a users does on a webpage, such as type, click, mouse-over, and even any keypress can be an event. 


When using the addEventListener() method, what 2 arguments will you need to provide?  
>when the addEventListener is called, you must provide the type of event thats being listened for(such as click), and a callback function that decides how the click will be handled.  


Describe the event object. Why is the target within the event object useful?  
>the event object is an object that contains all the different types of events that can be listened for. If you need to listen for a specific key press, the object can be viewed to see which key is pressed because they are listed by the key code.  


What is the difference between event bubbling and event capturing?  
>event bubbling will have nested elements with multiple events causing the nested event to trigger a parent element's event listener is triggered. A way to control which order the events are fired in is event capturing. Event capturing is controlling the event capturing. 



## Things I want to know more about
