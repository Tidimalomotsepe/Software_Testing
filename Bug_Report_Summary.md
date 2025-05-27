# 🐞 Bug Report Summary

## 🧾 Student Details

**Name**: Tidimalo Motsepe
**Cohort**: feb 2025  
**Date**: 27 May 2025

---

## ✅ Expected Behaviors

List 3 things you expect the To-Do app to do correctly.

1.Tasks should not be added if the input is empty.

2.yping "clear all" should clear all tasks without adding it to the list.

3.Clicking a task should toggle a strike-through to indicate completion.

---

## 🐛 Reported Bugs

### 🐞 BUG-001

**Title**"Clear all" command appears in the task list before tasks are cleared
**GitHub Link**:  https://github.com/Tidimalomotsepe/Software_Testing/issues/1
**Requirement Affected**: Input Command Handling
**Severity**: Medium
**Summary**:
When the user types "clear all", the text is first added as a task item and only then are the tasks cleared. This results in a flicker where the "clear all" command appears briefly before deletion.

---

### 🐞 BUG-002

**Title**: Tasks do not persist after page reload
**GitHub Link**:https://github.com/Tidimalomotsepe/Software_Testing/issues/2
**Requirement Affected**: Data Persistence
**Severity**: High  
**Summary**:  
The application does not use localStorage or any method to persist tasks. All tasks are lost when the user reloads the page, which impacts usability.

---

## 💭 Reflection

To test the app, I interacted with the interface manually by entering tasks, triggering special commands like "clear all", and refreshing the page to check persistence. I also clicked on tasks to verify completion toggling.

I found it easy to identify bugs related to UI interaction and logic flaws. However, detecting missing features like data persistence required thinking from a user-expectation perspective. I'm becoming more confident in finding and reporting bugs, especially using structured templates like this.
