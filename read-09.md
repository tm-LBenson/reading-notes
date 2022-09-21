A web application can be made interactive for the user through forms and event listeners. For example, users can input data into the application's form to make a better user experience, and the user can provide input through events, such as clicking buttons to make things change on the webpage. 

HTML Forms
[Your first Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)[How To Structure A Web Form.](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

Why are forms so important in web development?
>Forms are how the server can gather inputs from a user. As a result, it can create a more personalized user experience. 


When designing a form, what are some key things to keep in mind when it comes to user experience?
> Labels on each form can make it easier to understand inputs. If the type attribute is set to password, it can protect a user's privacy with passwords.
> If a form is submitted with error, you should not allow the browser to reload the page, preventing form data from resetting



List 5 form elements and explain their importance.  
```<form>``` tags are required when setting up any form to link all the forms to the submit  
```<button>``` is used at the end of a form to submit the form to the server  
```<input>``` is used to create multiple types of input fields such as password, button, text, and even a color picker.  
```<label>``` labels are tied to each form part to improve the user experience. When correctly linked, you can click a label to select a form.  
```<textarea>``` a dynamically sizable text field that allows longer messages to be typed and viewed.  

Learn JS
[Introduction To Events.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

How would you describe events to a non-technical friend?  
>events are anything a user does on a webpage, such as a type, click, mouse-over, and even any keypress can represent an event. 


When using the addEventListener() method, what two arguments will you need to provide?  
>when the addEventListener is called, you must provide the type of event that's being listened for(such as click) and a callback function that decides how the click will be handled.  


Describe the event object. Why is the target within the event object useful?  
>the event object is an object that contains all the different types of events that can be listened to. For example, If you need to listen for a specific key press, the object can be viewed to see which key is pressed because the key code lists them.  


What is the difference between event bubbling and event capturing?  
>event bubbling will have nested elements with multiple events causing the nested event to trigger a parent element's event listener is triggered. Event capturing is a way to control which order the events are fired. Therefore, Event capturing is controlling the event capturing. 



## Things I want to know more about
