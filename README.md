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
| Name | Mohan R |
| Password | gcep6579 |
| Textarea | Graphic Designer and UI/UX enthusiastic |

---

## Screenshots

<img width="1870" height="933" alt="Screenshot 2025-11-22 183716" src="https://github.com/user-attachments/assets/2ba19b22-856f-478c-8712-6d7c8d220374" />
<img width="1898" height="1039" alt="image" src="https://github.com/user-attachments/assets/49cb256b-3b39-4660-801b-15ed675bc077" />
<img width="1874" height="989" alt="Screenshot 2025-11-23 115827" src="https://github.com/user-attachments/assets/5998dc3a-3f31-4cde-a14d-20413e789a65" />




---
