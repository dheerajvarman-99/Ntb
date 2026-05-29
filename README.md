# To-Do List Application

A modern, feature-rich to-do list application with local storage functionality. This app helps you stay organized and productive by managing your daily tasks efficiently.

## Features

✨ **Core Features:**
- ➕ Add new tasks with a simple input field
- ✅ Mark tasks as completed
- ✏️ Edit existing tasks
- 🗑️ Delete individual tasks
- 💾 Persistent storage using Local Storage (data saved automatically)

🎯 **Smart Filtering:**
- View all tasks
- Filter by active (incomplete) tasks
- Filter by completed tasks

📊 **Statistics Dashboard:**
- Total number of tasks
- Number of active tasks
- Number of completed tasks

🧹 **Bulk Actions:**
- Clear all completed tasks
- Delete all tasks

🎨 **User Experience:**
- Beautiful gradient background
- Smooth animations and transitions
- Responsive design (works on mobile and desktop)
- Intuitive interface with visual feedback
- Enter key support for adding tasks

## How to Use

1. **Open the Application:**
   - Open `index.html` in your web browser

2. **Add a Task:**
   - Type your task in the input field
   - Click "Add Task" button or press Enter

3. **Manage Tasks:**
   - Check the checkbox to mark a task as completed
   - Click "Edit" to modify a task
   - Click "Delete" to remove a task

4. **Filter Tasks:**
   - Click "All" to see all tasks
   - Click "Active" to see only incomplete tasks
   - Click "Completed" to see only completed tasks

5. **Bulk Operations:**
   - Click "Clear Completed" to remove all completed tasks
   - Click "Delete All" to remove all tasks

## Local Storage

This application uses browser's Local Storage to persist your data:
- All tasks are automatically saved to Local Storage when you add, edit, or delete them
- Your tasks will remain even after closing and reopening the browser
- Data is stored locally on your device (not on any server)
- To clear all data, use "Delete All" button or clear browser's Local Storage

## Technical Details

**Technologies Used:**
- HTML5 for structure
- CSS3 for styling (with gradients, animations, and flexbox)
- Vanilla JavaScript (ES6+) for functionality
- Browser Local Storage API for data persistence

**File Structure:**
```
├── index.html    # Main HTML structure
├── styles.css    # Styling and responsive design
├── script.js     # JavaScript functionality
└── README.md     # This file
```

## Browser Compatibility

- Chrome/Chromium (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers

## Storage Information

- **Storage Type:** LocalStorage
- **Key:** `todos`
- **Format:** JSON array of todo objects
- **Capacity:** ~5-10 MB (depends on browser)

## Future Enhancements

- 🔄 Drag and drop to reorder tasks
- 🏷️ Add tags/categories
- 📅 Set due dates
- ⏰ Set reminders
- 🌙 Dark mode
- 📱 Progressive Web App (PWA)
- ☁️ Cloud sync capability

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to fork this repository and submit pull requests with improvements!
