# html-city-tourism
## exercise 01:
<!DOCTYPE html>
<html>
<head>
<title>My Day</title>
<style>
  body {
    margin: 0; /* Remove default margins for full-page view */
    font-family: Arial, sans-serif;
  }

  .center {
    text-align: center;
  }

  .highlight {
    background-color: #ffff99;
  }

  table {
    border-collapse: collapse;
    width: 70%; /* Reduce table width to 70% */
    margin: 0 auto; /* Center the table horizontally */
  }

  th {
    border: 1px solid black;
    padding: 10px;
  }

  td {
    border: 1px solid black;
    padding: 10px;
  }

  td:first-child {
    width: 50%; /* Set width for activity description column */
  }

  td:last-child img {
    width: 100%; /* Images stretch to fill remaining space */
  }

  ol {
    margin-left: 20px; /* Indent list for readability */
  }

  ul {
    margin-left: 20px; /* Indent sub-list for readability */
    list-style-type: disc; /* Change to desired list style (e.g., circle) */
  }

  li {
    margin-bottom: 5px; /* Add space between list items */
  }
</style>
</head>
<body>
<table cellpadding="0" cellspacing="0"> <tr>
    <th colspan="2" class="center"><mark>My Day</mark></th>
  </tr>
  <tr>
    <td>
      <ol>
        <li>Wake up early
          <ul>
            <li>5 AM</li>
            <li>Walk</li>
            <li>Jog</li>
          </ul>
        </li>
        <li>Breakfast
          <ul>
            <li>8 AM</li>
            <li>Eggs</li>
            <li>Coffee</li>
          </ul>
        </li>
        <li>Go to Saveetha
          <ul>
            <li>8 AM</li>
            <li>Attend classes</li>
            <li>To be continued...</li>
          </ul>
        </li>
      </ol>
    </td>
    <td>
      <table>
        <tr>
          <th colspan="2" class="center highlight">Things to watch</th>
        </tr>
        <tr>
          <td><img src="./img/o4.jpg" alt="Alarm Clock"></td>
          <td><img src="./img/o1.jpg" alt="Shoes"></td>
        </tr>
        <tr>
          <td><img src="./img/o1.jpg" alt="Eggs"></td>
          <td><img src="./img/o2.jpg" alt="Coffee"></td>
        </tr>
        <tr>
          
          <td><img src="./img/o3.jpg" alt="School"></td>
            <td><img src="./img/o2.jpg" alt="Coffee"></td>
        </tr>
      </table>
    </td>
  </tr>
</table>
</body>
</html>


## output:
![image](https://github.com/Prethiveerajan/html-city-tourism/assets/94233064/ac8560cb-eb28-4235-924c-f4e81b39a15e)





