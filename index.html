<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My To-Do App</title>

<style>
body {
  font-family: Arial, sans-serif;
  background: #f1f5f9;
  padding: 20px;
}

.container {
  max-width: 450px;
  margin: auto;
  background: white;
  padding: 20px;
  border-radius: 15px;
}

h2 {
  text-align: center;
  color: #2563eb;
}

input {
  width: 65%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 8px;
}

button {
  padding: 12px;
  border: none;
  border-radius: 8px;
  background: #2563eb;
  color: white;
  cursor: pointer;
}

li {
  background: #f1f5f9;
  padding: 12px;
  margin-top: 10px;
  border-radius: 8px;
  display: flex;
  justify-content: space-between;
  gap: 8px;
  overflow-wrap: anywhere;
}

.done {
  text-decoration: line-through;
  color: gray;
}

.delete {
  background: #ef4444;
}
</style>
</head>

<body>

<div class="container">
  <h2>📝 আমার To-Do List</h2>

  <input id="taskInput"
    type="text"
    placeholder="নতুন কাজ লিখুন">

  <button onclick="addTask()">যোগ করুন</button>

  <ul id="taskList"></ul>
</div>

<script>
let tasks = JSON.parse(
  localStorage.getItem("tasks") || "[]"
);

function saveTasks() {
  localStorage.setItem(
    "tasks",
    JSON.stringify(tasks)
  );
}

function showTasks() {
  let list = document.getElementById("taskList");
  list.innerHTML = "";

  tasks.forEach((task, index) => {
    let li = document.createElement("li");

    let span = document.createElement("span");
    span.textContent = task.text;

    if (task.done) {
      span.className = "done";
    }

    span.onclick = () => {
      tasks[index].done = !tasks[index].done;
      saveTasks();
      showTasks();
    };

    let btn = document.createElement("button");
    btn.textContent = "মুছুন";
    btn.className = "delete";

    btn.onclick = () => {
      tasks.splice(index, 1);
      saveTasks();
      showTasks();
    };

    li.append(span, btn);
    list.appendChild(li);
  });
}

function addTask() {
  let input = document.getElementById("taskInput");
  let text = input.value.trim();

  if (text === "") {
    alert("একটি কাজ লিখুন!");
    return;
  }

  tasks.push({
    text: text,
    done: false
  });

  input.value = "";
  saveTasks();
  showTasks();
}

showTasks();
</script>

</body>
</html>