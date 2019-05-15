# Form

## TO create a form:
```
<form action="process.php" method="POST">
			<div>
				<label>First Name</label>
				<input type="text" name="firstName" placeholder="Enter first name"> 
			</div>
```

---

* Here, **action** attribute has a path of a php file that has all the functions of the form.

* method attribute tell how to send the form data into the server which can be either GET or POST.

* `<label>` tag is used for providing label to the inputs in the form

* `<input>` tag is used for specifying inputs to the form

	* **type** attributes can have different forms of inputs like text, email, date, etc.

	* **name** attr for giving an id to the input tag

	* **placeholder** attr is used for desplaying text in the text box which omits when clicked.

* `<div>` tag is used for aligning an inline commands in column.