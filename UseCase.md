## 🧩 Use Case

**Title:** [Descriptive name]

**Actor(s):** [User roles or systems involved]

**Goal:** [What the actor wants to achieve]

**Preconditions:**
- [System state or required setup]

**Main Flow:**
1. [Step-by-step interaction]
2. [System response]
3. [Next user/system action]

**Alternate Flows:**
- [Condition]: [Alternate steps or error handling]

**Postconditions:**
- [Expected system state after completion]

**Notes:**
- [Technical or business constraints]

## Example

**Title:** Create New Task

**Actor:** End User

**Goal:** Add a task to the personal to-do list

**Preconditions:**
- User is logged in (if authentication is required)
- To-do list interface is visible

**Main Flow:**
1. User types task name into input field
2. User optionally selects a due date
3. User clicks “Add” button
4. System validates input
5. System creates task object
6. System updates task list view
7. System stores task in local storage or backend

**Alternate Flows:**
- If task name is empty, system shows error message
- If due date is invalid, system prompts for correction

**Postconditions:**
- Task is visible in the list
- Task is stored for future retrieval

**Notes:**
- Consider debounce or throttling for rapid input
- Ensure accessibility for keyboard and screen reader users