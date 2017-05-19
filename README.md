# mavo.io todo list

[Live Example](https://codepen.io/wgenial/pen/rmqRzW)

```html
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>To-Do List</title>
</head>
<body>
<main mv-app="todo" mv-storage="https://github.com/giovanigenerali/mavotodo/tasks/todo.json">
	<header>
		<h1>My tasks</h1>
		<p><strong>[count(done)]</strong> done out of <strong>[count(task)]</strong> total</p>
	</header>
	<ul>
		<li property="task" mv-multiple>
			<label>
				<input property="done" type="checkbox"/>
				<span property="taskTitle"></span>
			</label>
		</li>
	</ul>
</main>
</body>
```

More info take a look at [http://mavo.io](http://mavo.io)
