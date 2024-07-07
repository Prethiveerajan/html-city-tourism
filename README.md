# html-city-tourism
## exercise 01:
```
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
```

## output:
![image](https://github.com/Prethiveerajan/html-city-tourism/assets/94233064/ac8560cb-eb28-4235-924c-f4e81b39a15e)


## Hotels:
## index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>City Tourism</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="images/o1.jpg" alt="City Logo">
        <h1>Welcome to India Tourism</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="heritage.html">Heritage</a></li>
                <li><a href="hotel-booking.html">Hotel Booking</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Discover the Beauty of India</h2>
            <p>India is a diverse and culturally rich country with a myriad of heritage sites, vibrant cultures, and beautiful landscapes. Explore our website to find out more about the must-visit places and make your stay comfortable by booking the best hotels in the country.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 India Tourism</p>
    </footer>
</body>
</html>

```


## gallery.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="images/o1.jpg" alt="City Logo">
        <h1>Gallery of India</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="heritage.html">Heritage</a></li>
                <li><a href="hotel-booking.html">Hotel Booking</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Our Beautiful Country</h2>
            <div class="gallery">
                <img src="images/hotel-1.jpeg" alt="Gallery Image 1">
                <img src="images/hotel-2.jpeg" alt="Gallery Image 2">
                <img src="images/hotel-3.jpeg" alt="Gallery Image 3">
                <img src="images/hotel-4.jpeg" alt="Gallery Image 4">
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 India Tourism</p>
    </footer>
</body>
</html>

```
## hotel-booking.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel Booking</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <img src="images/o1.jpg" alt="City Logo">
        <h1>Book Your Stay in India</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="heritage.html">Heritage</a></li>
                <li><a href="hotel-booking.html">Hotel Booking</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="booking-form-container">
            <h2>Hotel Booking Form</h2>
            <form class="hotel-booking-form" action="submit-booking" method="post">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone Number:</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>
                <div class="form-group">
                    <label for="checkin">Check-in Date:</label>
                    <input type="date" id="checkin" name="checkin" required>
                </div>
                <div class="form-group">
                    <label for="checkout">Check-out Date:</label>
                    <input type="date" id="checkout" name="checkout" required>
                </div>
                <div class="form-group">
                    <label for="room">Room Type:</label>
                    <select id="room" name="room" required>
                        <option value="single">Single</option>
                        <option value="double">Double</option>
                        <option value="suite">Suite</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="special-requests">Special Requests:</label>
                    <textarea id="special-requests" name="special-requests"></textarea>
                </div>
                <div class="form-group">
                    <button type="submit">Book Now</button>
                </div>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 India Tourism</p>
    </footer>
</body>
</html>

```


## output:
![image](https://github.com/Prethiveerajan/html-city-tourism/assets/94233064/2b9a9f53-42c6-418e-ac4a-1aff44de1f97)
![image](https://github.com/Prethiveerajan/html-city-tourism/assets/94233064/3ca963fd-069f-4a61-a349-c2934ae9e1b9)
![image](https://github.com/Prethiveerajan/html-city-tourism/assets/94233064/1d82c8d4-aae6-4dfe-9491-79f0df649420)






