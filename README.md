# Laserfiche-ENGG1420-Final-Project
## Created a file processing and sorting system for Laserfiche, a California based Tech Company
### Project Description:
 Construct a file-processing software that filters through various processing elements based on the input parameters.
 The program accepts a JSON file as input and outputs the file based on what meets the criteria.

 File Processing Elements include:
 - ContentFilter
 - CountFilter
 - LengthFilter
 - List
 - NameFilter
 - Print
 - (Various others)

<html>
</head>
<style>
    table {
      border-collapse: collapse;
      width: 100%;
    }
    th, td {
      border: 1px solid #dddddd;
      text-align: left;
      padding: 12px; /* Increase padding for more space */
    }
    th {
      background-color: #f2f2f2;
    }
  </style>
<body>

<table>
  <tr>
    <th>Element</th>
    <th>Description</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td>Name Filter</td>
    <td>Filters entries based on the presence of a given string in their name.</td>
    <td>List of entries, String Key</td>
    <td>Sub-list of entries with the given string Key in their name</td>
  </tr>
  <tr>
    <td>Length Filter</td>
    <td>Filters files based on their length and a specified condition.</td>
    <td>List of entries, Long Length, String Operator</td>
    <td>Sub-list of entries satisfying the given length condition</td>
  </tr>
  <tr>
    <td>Content Filter</td>
    <td>Filters files based on the presence of a given string in their content.</td>
    <td>List of entries, String Key</td>
    <td>Sub-list of entries with the given string Key in their content</td>
  </tr>
  <tr>
    <td>Count Filter</td>
    <td>Filters files based on the count of a given string in their content.</td>
    <td>List of entries, String Key, Integer Min</td>
    <td>Sub-list of entries with at least Min occurrences of the given string Key</td>
  </tr>
  <tr>
    <td>Split Processing Element</td>
    <td>Splits files into smaller parts based on the specified number of lines.</td>
    <td>List of entries, Integer Lines</td>
    <td>List of created entries resulted from splitting the input</td>
  </tr>
  <tr>
    <td>List Processing Element</td>
    <td>Selects a list of entries from directories based on a specified maximum count.</td>
    <td>List of entries, Integer Max</td>
    <td>List of entries selected from the directories</td>
  </tr>
  <tr>
    <td>Rename Processing Element</td>
    <td>Appends a given suffix to the name of each entry in the input list.</td>
    <td>List of entries, String Suffix</td>
    <td>List of entries with updated names</td>
  </tr>
  <tr>
    <td>Print Processing Element</td>
    <td>Prints information about each entry, including name, length, and absolute path.</td>
    <td>List of entries</td>
    <td>No change to the list of entries</td>
  </tr>
</table>

</body>
</html>

