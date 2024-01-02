# Task points

*Created at: January 2nd, 2024.*

Different ways to assign points to tasks.

## Model A:

|          | Description | Examples |
|--------- | ----------- | -------- |
| 1 pt.    | Update just one file OR create a small file.    | e.g. Change the label from a Button element OR add a new .env file |
| 2 pts.   | Update multiple files.                          | e.g. Apply a new font color on each project's component .sass file |
| 3 pts.   | Create multiple files (into the same context).  | e.g. Create a new Button component (button.jsx, button.sass and button.test.js files might be created) |
| 5 pts.   | Create and update multiple files.               | e.g. Create a new Form container and fill the fields using data from a GET request at the store |
| 8 pts.   | Updated files from different contexts.          | e.g. Set both Button component and Chip component labels by a value from the global state |
| 13 pts.  | Create AND update files from different contexts | e.g. Add a GET text and a GET label request into the same store, than set the Page content and set Button label |

### p.s.
- **8 pts.** and **13 pts.** tasks can be divided into different tasks, however, to avoid code rework and conflicts, the issues can be solved in only one.
