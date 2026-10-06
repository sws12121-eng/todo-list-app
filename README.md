# To-Do List Application

A simple, elegant to-do list web application with local storage functionality.

## Features

✅ **Add Tasks** - Type and add new tasks to your list  
✅ **Mark Complete** - Check off completed tasks with a visual indicator  
✅ **Delete Tasks** - Remove individual tasks  
✅ **Clear Completed** - Remove all completed tasks at once  
✅ **Persistent Storage** - Your tasks are saved in browser localStorage  
✅ **Responsive Design** - Works perfectly on desktop and mobile devices  
✅ **Task Counter** - See how many tasks remain incomplete  
✅ **Keyboard Support** - Press Enter to add tasks quickly  

## Usage

1. Open `index.html` in your web browser
2. Type a task in the input field
3. Click "Add" or press Enter
4. Check the checkbox to mark tasks complete
5. Click "Delete" to remove a task
6. Click "Clear completed" to remove all finished tasks

Your tasks are automatically saved to your browser's localStorage and will persist even after closing the browser.

## Technical Details

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and gradients
- **Vanilla JavaScript** - No dependencies
- **LocalStorage API** - Client-side persistent storage

## Browser Support

Works on all modern browsers that support:
- ES6 JavaScript
- CSS Grid and Flexbox
- Local Storage API

## File Structure

```
todo-list-app/
├── index.html      # Complete single-file application
└── README.md       # This file
```

## Customization

You can customize the color scheme by modifying the CSS variables at the top of the `<style>` section:

```css
:root {
  --primary: #4f46e5;      /* Main color */
  --primary-dark: #3730a3; /* Hover color */
  --done: #10b981;         /* Completed color */
  /* ...and more */
}
```

## License

Free to use and modify.