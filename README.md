# Frontend Interview Task - Table Component in React

## Task Overview:

The goal of this task is to implement a React table component that fetches data from a provided API and allows for **global search**, **sortable columns**, and **pagination**.

### API Endpoint:

You will be fetching employee data from the following API:
[Mock API](https://raw.githubusercontent.com/akhil-ln/frontend-interview-tasks/refs/heads/main/MOCK_DATA.json)

## Requirements:

### 1. Fetch and Display Data:

* Fetch employee records from the provided API and display them in a table.
* The fields to display in the table are:

  * `no`, `name`, `team`, `gender`, `age`, `email`, `phone`, `location`

### 2. Global Search:

* Add a search input field to filter the table by any of the displayed fields.
* The search should be **case-insensitive** and allow for partial matches.

### 3. Sortable Columns:

* Implement sorting functionality for each column.
* Clicking on a column header should sort the column in **ascending** or **descending** order.
* You can toggle the sort order by clicking the header again.

### 4. Pagination:

* Display only 10 records per page.
* Include **Previous** / **Next** controls for pagination.
* Display page numbers and allow users to navigate between pages.

### 5. Bonus (Optional):

* While CSS and styling are **not required**, feel free to apply basic styles or use a CSS framework for better UI presentation.

---

## Instructions:

1. **Fork this repository** to your GitHub account.
2. **Clone** the forked repository to your local machine.
3. **Create a new branch** (e.g., `feature/table-component`).
4. Implement the table component following the requirements.
5. **Submit a pull request** with your implementation to this repository.
6. 
---

### Notes:

* **No CSS styling** is required, but you can apply any styles if you feel it improves the UX.
* If you face any issues with the API, feel free to reach out via GitHub Issues.
