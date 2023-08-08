Blazor Quickgrid for Comp 4870 Created March 1st 2023

Enhancements to the Blazor-WASM Demo:

1: Changed grid display to QuickGrid, which allows for more customizability -> For example, added resizability to columns

2: Added pagination, which reduces resource usage by only fetching and displaying a section of a database at a time.
    This is particularly useful for very large databases with lots of entries.

3: Added a dropdown menu which allows the user to determine how many students are displayed per page.

4: Added the ability for students to be sorted by studentId, first name, last name, and school.

5: Added the ability for students to be filtered by first name, last name, and school

6: The filter and sort abilities also work with each other.
    For example, you can filter for only Nursing students, and then sort by last name.