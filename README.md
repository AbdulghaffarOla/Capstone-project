# Capstone-project
# The frontend interface

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TaskMaster</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>TaskMaster</h1>
    </header>
    <main>
        <section id="task-input">
            <h2>Add New Task</h2>
            <form id="task-form">
                <input type="text" id="title" placeholder="Task Title" required />
                <textarea id="description" placeholder="Task Description"></textarea>
                <select id="priority">
                    <option value="low">Low</option>
                    <option value="medium">Medium</option>
                    <option value="high">High</option>
                </select>
                <input type="date" id="deadline" />
                <button type="submit">Add Task</button>
            </form>
        </section>
        <section id="tasks">
            <h2>Your Tasks</h2>
            <input type="text" id="search" placeholder="Search tasks..." />
            <table id="task-table">
                <thead>
                    <tr>
                        <th>Title</th>
                        <th>Description</th>
                        <th>Priority</th>
                        <th>Deadline</th>
                        <th>Actions</th>
                    </tr>
                </thead>
                <tbody></tbody>
            </table>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>
