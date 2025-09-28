# UiPath – Web Form Automation Workflow

This repository contains a simple **UiPath workflow** that demonstrates:
- **Opening a web page** in a browser
- **Automatically filling out a contact form** with user data
- **Submitting the form** using UI automation

---

## Project Overview
- Built using **UiPath Studio (Modern Design Experience)**
- Demonstrates usage of **Use Application/Browser**, **Type Into**, and **Click** activities
- A beginner-friendly project to learn **basic web automation** in UiPath

---

## Project Files
- `Main.xaml` → The main automation workflow  
- `project.json` → UiPath project configuration  

---

## Workflow Logic

### 🔹 Use Application/Browser
- Launches the target page:  
  `https://www.selenium.dev/selenium/web/web-form.html`
- Ensures the browser session is managed and closed automatically after the workflow finishes.

### 🔹 Type Into
- Enters sample data:
  - **Name**: `John Doe`
  - **Email**: `john@example.com`
- You can easily replace these hard-coded values with variables or data from Excel.

### 🔹 Click Submit
- Clicks the **Submit** button to send the form.

---

## Example Run
*(Values can be customized as needed)*

| Field | Example Input |
|------|--------------|
| Name | Bala Saravanan K |
| Password | password123 |
| Textarea | Graphic Designer and UI/UX enthusiastic |

---

## Screenshots
<img width="3839" height="2157" alt="Screenshot 2025-09-28 194604" src="https://github.com/user-attachments/assets/42056f3e-ecf1-451c-9221-aaae44b0a24d" />
<img width="3840" height="2160" alt="Screenshot 2025-09-28 194530" src="https://github.com/user-attachments/assets/768d845c-380b-4f8e-ab2a-a670ed8756d5" />
<img width="3840" height="2160" alt="Screenshot 2025-09-28 194628" src="https://github.com/user-attachments/assets/c75be395-c635-4935-8660-87276b12bf8f" />


---
