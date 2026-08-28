# Health & Welfare Enrollment Helper

A simple, interactive web tool that guides employees through the health and welfare enrollment process by asking a few questions and providing personalized forms checklists.

## Live Demo

👉 **[Try it here](https://lstile92.github.io/health-welfare-enrollment-helper/)**

## Features

✅ **Interactive Questionnaire** - Simple yes/no questions guide employees to the right forms  
✅ **Personalized Results** - Shows exactly which forms each employee needs to complete  
✅ **New vs Returning Employees** - Different workflows for new and returning staff  
✅ **Easy to Customize** - Just edit the settings section in the HTML, no coding required  
✅ **Responsive Design** - Works great on desktop, tablet, and mobile  
✅ **No Backend Needed** - Pure client-side HTML/CSS/JavaScript  

## How It Works

1. Employee opens the form
2. Answers if they're a new or returning employee
3. Answers questions specific to their situation (e.g., keeping same plan, changing plans, waiving insurance)
4. Gets a personalized checklist of forms to complete

## Customization

The tool is designed to be **super easy to customize**. You only need to edit the `SETTINGS` object in the HTML file:

```javascript
const SETTINGS = {
  title: "Your Company Name - Enrollment Helper",
  subtitle: "Custom subtitle here...",
  
  newEmployee: { ... },
  returningEmployee: { ... }
}
```

Edit questions, button text, form names, and notes directly in the HTML—no technical knowledge needed!

## Files

- `Health_Welfare_Enrollment_Helper_EASY_EDIT.html` - The main application file (everything in one file for easy deployment)

## Deployment

Simply upload `Health_Welfare_Enrollment_Helper_EASY_EDIT.html` to any web server or GitHub Pages, and it's ready to use!

## License

MIT License - Feel free to use and modify for your organization.
