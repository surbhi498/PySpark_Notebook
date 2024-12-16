# SEAS8515 Homework 4

### Instructions
Please use the data provided in the file `SEAS8515_HW4.json` to complete the following tasks. Submit one notebook containing all solutions, with Markdown cells to explain each step. Ensure all code cells are executed and outputs are visible to receive credit. Thank you.

---

## Question 1: Load the JSON File into a DataFrame
- Load the data from `SEAS8515_HW4.json` into a DataFrame.
- Display the DataFrame.
- Perform a data profile on the DataFrame.

---

## Question 2: Save the DataFrame as a Delta Table
- Save the loaded DataFrame as a Delta table.

---

## Question 3: Reload the Saved Table and Append Data
- Reload the saved Delta table.
- Append some data to the table.
- Use the `versionAsOf` API to:
  - Read the current version of the table.
  - Read the prior version of the table.
- Display both versions of the table.

---

## Question 4: Read Different Versions Using `readChangeData`
- Attempt to read the different versions of the Delta table using the `readChangeData` option.
- Reflect on why this method did not work.

---

## Question 5: Enable Change Data Capture (CDC) and Analyze Changes
- Enable Change Data Capture (CDC) on the Delta table.
- Perform some changes to the table.
- Read the change data between the last two versions.
- Adjust the configuration to read changes between version 0 and any other version.
- Reflect on why this approach worked or did not work.

---

### Submission Requirements
- Include all code and outputs in your notebook.
- Use Markdown cells to explain each question and its solution.
- Ensure your notebook is organized and formatted for readability.
