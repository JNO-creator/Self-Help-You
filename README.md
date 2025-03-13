<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Self-Help-You</title>
    <style>
      /* Reset default margin and padding */
      body, html {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
      }

      /* Styling the navigation bar */
      .navbar {
        background-color: #e1705d; /* Red background color */
        overflow: hidden; /* Ensures the content is contained within the navbar */
        text-align: center; /* Centers the links */
      }

      /* Styling each link inside the navbar */
      .navbar a {
        display: inline-block; /* Display links horizontally */
        padding: 14px 20px; /* Padding inside each link */
        text-decoration: none; /* Removes underline from links */
        color: white; /* White text color */
        font-size: 16px; /* Font size for the links */
        transition: background-color 0.3s ease; /* Smooth transition for background color change */
      }

      /* Hover effect for the links */
      .navbar a:hover {
        background-color: #ddd; /* Light background when hovered */
        color: black; /* Change text color when hovered */
      }

      /* Active link styling (when a link is clicked or active) */
      .navbar a.active {
        background-color: #0e194d; /* Blue background for active link */
        color: white; /* Keep text white for active link */
      }

      /* Hamburger menu icon styling */
      .navbar .icon {
        z-index: 2;
        display: none;
        font-size: 30px;
        color: white;
        padding: 14px 20px;
        background-color: #0e194d;
        cursor: pointer;
      }

      /* For small screens (mobile devices) */
      @media screen and (max-width: 768px) {
        .navbar a {
          display: none; /* Hide the links by default */
          width: 100%; /* Make the links take full width */
          text-align: left; /* Align links to the left */
          padding: 14px; /* Adjust padding for the links */
        }

        /* Display the hamburger icon */
        .navbar .icon {
          display: block;
        }

        /* When the hamburger icon is clicked, show the links */
        .navbar.responsive a {
          display: block;
        }

        .navbar.responsive .icon {
          position: absolute;
          right: 0;
          top: 0;
        }
      }

      /* Styling for the header with rolling text effect */
      .header {
        background-color: #0e194d;
        color: white;
        padding: 20px;
        text-align: center;
        position: relative;
        overflow: hidden;
      }

      /* Rolling text effect
