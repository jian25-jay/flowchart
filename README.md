# Event Reservation System - Flowchart

A comprehensive visual flowchart of the Event Reservation System application, showing the complete user journey from login through reservation management.

## 📋 Overview

This project provides an interactive flowchart diagram that illustrates the entire workflow of an event reservation system. It demonstrates:

- **User Authentication**: Login and registration flows
- **Session Management**: User login state handling
- **Reservation Operations**: Create, view, update, and delete reservations
- **Error Handling**: Validation checks and error messages throughout the system

## 🎨 Features

- **Interactive Mermaid Flowchart**: Clean, professional diagram using Mermaid.js
- **Color-Coded Sections**: Different colors represent different types of operations:
  - 🔵 Entry points (light blue)
  - 🟢 Home page (green)
  - 🟡 Authentication (yellow)
  - 🟠 Reservation operations (orange)
  - 🔴 Update/Delete operations (red)
  - 🟣 Logout (purple)
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional styling with gradient backgrounds
- **Legend**: Color-coded legend for easy reference

## 🚀 Quick Start

### Option 1: View Online
Simply open `index.html` in any modern web browser. The flowchart will render automatically.

### Option 2: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Set Source to `main` branch
4. Your flowchart will be live at `https://yourusername.github.io/flowchart`

## 📂 Project Structure

```
.
├── index.html          # Main flowchart visualization
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── LICENSE            # License file
```

## 🔄 System Flow Breakdown

### 1. **Entry & Authentication**
   - User visits the application
   - Check if user is logged in
   - Redirect to login page if not authenticated

### 2. **Login/Registration**
   - **Login**: Enter credentials and validate
   - **Register**: Create new account with validation
   - Both flows lead to session creation and home page redirect

### 3. **Home Page**
   - Central hub for all user actions
   - Options to make reservations, view existing ones, or logout

### 4. **Reservation Management**
   - **Create**: Fill form, validate data, save to database
   - **View**: Display all reservations with action options
   - **Update**: Modify reservation details
   - **Delete**: Remove reservation with confirmation

### 5. **Logout**
   - Clear user session
   - Return to entry point

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling and responsive design
- **Mermaid.js**: Flowchart diagram rendering
- **Responsive Design**: Mobile-first approach

## 📱 Browser Support

- Chrome/Edge (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Android)

## 🔧 Customization

### Edit the Flowchart
1. Open `index.html` in a text editor
2. Find the `<div class="mermaid">` section
3. Modify the graph syntax (Mermaid Diagram Syntax)
4. Update colors in the `style` declarations at the bottom of the graph

### Change Colors
Modify the CSS color values in the `<style>` section:
- Update `background` gradient colors in `body`
- Modify `fill` colors in the flowchart `style` directives

## 📚 Resources

- [Mermaid Documentation](https://mermaid-js.github.io/)
- [Mermaid Flowchart Guide](https://mermaid-js.github.io/syntax/flowchart.html)
- [GitHub Pages Documentation](https://pages.github.com/)

## 🤝 Contributing

Feel free to fork this project and submit pull requests with improvements or variations of the flowchart.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

Created as a reference flowchart for Event Reservation System development.

## 📞 Support

If you have questions or suggestions about this flowchart, please feel free to open an issue on GitHub.

---

**Note**: This flowchart represents a typical event reservation system architecture. You can adapt it to match your specific implementation or requirements.
