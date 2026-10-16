
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Household Chores</title>
</head>
<body>

    <h1>🏡 Household Chores</h1>
    <p>Keep your home organized, one task at a time.</p>

    <hr>

    <h2>Add Chore</h2>

    <form>
        <label for="chore">Chore Name:</label>
        <input
            type="text"
            id="chore"
            name="chore"
            placeholder="What needs to be done?"
            required
        >

        <br><br>

        <label for="assignedTo">Assigned To:</label>
        <input
            type="text"
            id="assignedTo"
            name="assignedTo"
            placeholder="Assigned to"
        >

        <br><br>

        <button type="submit">Add Chore</button>
    </form>

    <hr>

    <h2>Chore Dashboard</h2>

    <table border="1" cellpadding="10">
        <tr>
            <th>Total Chores</th>
            <th>Completed</th>
            <th>Pending</th>
        </tr>
        <tr>
            <td>0</td>
            <td>0</td>
            <td>0</td>
        </tr>
    </table>

    <hr>

    <h2>Chore List</h2>

    <label for="filter">Filter Chores:</label>
    <select id="filter">
        <option value="all">All Chores</option>
        <option value="completed">Completed</option>
        <option value="pending">Pending</option>
    </select>

    <br><br>

    <table border="1" cellpadding="10">
        <thead>
            <tr>
                <th>Chore Name</th>
                <th>Assigned To</th>
                <th>Status</th>
                <th>Actions</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td colspan="4">
                    No chores yet. Add your first one above.
                </td>
            </tr>
        </tbody>
    </table>

</body>
</html>
