<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Hairstyle Booking</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  header {
    background-color: #f36666;
    padding: 20px;
    text-align: center;
    color: white;
  }
  h1 {
    margin: 0;
  }
  .gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 20px;
  }
  .style {
    margin: 10px;
    border: 1px solid #ddd;
    padding: 10px;
    width: 200px;
    text-align: center;
  }
  .style img {
    width: 100%;
    height: auto;
  }
  .booking-form {
    max-width: 500px;
    margin: 40px auto;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
  }
  .booking-form h2 {
    text-align: center;
  }
  .booking-form label {
    display: block;
    margin-top: 10px;
  }
  .booking-form input, select {
    width: 100%;
    padding: 8px;
    margin-top: 5px;
    box-sizing: border-box;
  }
  .booking-form button {
    margin-top: 15px;
    width: 100%;
    padding: 10px;
    background-color: #f36666;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  footer {
    text-align: center;
    padding: 20px;
    background-color: #f36666;
    color: white;
    margin-top: 40px;
  }
</style>
</head>
<body>

<header>
  <h1>Beauty Hair Studio</h1>
  <p>Book Your Hairstyle Appointment Today!</p>
</header>

<!-- Gallery of styles -->
<section class="gallery">
  <div class="style">
    <img src="https://via.placeholder.com/200x150?text=Style+1" alt="Style 1" />
    <p>Elegant Updo</p>
  </div>
  <div class="style">
    <img src="https://via.placeholder.com/200x150?text=Style+2" alt="Style 2" />
    <p>Beach Waves</p>
  </div>
  <div class="style">
    <img src="https://via.placeholder.com/200x150?text=Style+3" alt="Style 3" />
    <p>Classic Bob</p>
  </div>
</section>

<!-- Booking Form -->
<section class="booking-form">
  <h2>Book an Appointment</h2>
  <form id="bookingForm">
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required />

    <label for="hairstyle">Choose Hairstyle:</label>
    <select id="hairstyle" name="hairstyle" required>
      <option value="">Select a style</option>
      <option value="Elegant Updo">Elegant Updo</option>
      <option value="Beach Waves">Beach Waves</option>
      <option value="Classic Bob">Classic Bob</option>
    </select>

    <label for="date">Select Date:</label>
    <input type="date" id="date" name="date" required />

    <label for="time">Select Time:</label>
    <input type="time" id="time" name="time" required />

    <button type="submit">Book Now</button>
  </form>
</section>

<!-- Footer -->
<footer>
  <p>Contact us: (123) 456-7890 | info@beautyhairstudio.com</p>
  <p>123 Main Street, City, State</p>
</footer>

<script>
  document.getElementById('bookingForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you! Your appointment has been booked.');
    this.reset();
  });
</script>

</body>
</html>
