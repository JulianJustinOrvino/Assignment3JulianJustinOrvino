# Assignment6

## Difference between asychronous programming with synchronous programming.

Synchronus: Single thread that assigned by its applications to process a request and finish a task, a long process like database query will block other threads because its activities at one time

Asynchronus: one of the technique that allow our software to make a work that could take a while to complete it while also being able to respond other feature without having to wait the task is done

## When Implementing Javascript and AJAX, there is an application in paradigms for Event Driven Programming, Describe the reasoning for those paradigms and state some examples of its application.

In an event-driven programming paradigm, entities for example service, objects to communicate with one another by passing messages through a proxy. Normally, the messages that held in a queue before being processed by the consumers. Event-driven programming are the dominant paradigm used in GUIs and other applications. Especially on  performing certain actions in response to user input. For example the "Create Task" button.

## Describe the implementation of asynchronous programming in AJAX.

1. Use <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script> inside of base.html or header html.
2. Add <script> inside html file to implement javascript.
3. Write AJAX syntax using JQuert in your script.
4. AJAX listen to every request and response.
5. Each response or data will be processed asynchronously.
6. Allowing the page to show data without having it to resfresh.

## Explain how you would implement the checklist above.

1. Create a new function into the views that allows it to return the data in json.
2. Add a new path for show_json
3. Make a function to get the task to todolist.html
4. Create a new create-task function for AJAX
5. Add new path for create_task_ajax
6. Write a function in javascript language so it can connects the modal to create path and automatically allows to be processed asynchronously