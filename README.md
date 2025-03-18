# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia Webpage</title>
</head>
<body>

    <!-- Header Section -->
    <h1>Welcome to Our Multimedia Webpage</h1>
    <p>Enjoy music, videos, and interactive elements!</p>

    <!-- Embedding an Image -->
    <h2>Featured Image</h2>
    <img src="https://source.unsplash.com/600x300/?nature,landscape" alt="Nature Image" width="600">

    <!-- Embedding Audio -->
    <h2>Listen to Music 🎵</h2>
    <audio controls>
        <source src="https://samplelib.com/lib/preview/mp3/sample-15s.mp3" type="audio/mp3">
        Your browser does not support the audio element.
    </audio>

    <!-- Embedding a Video -->
    <h2>Watch This Video 📹</h2>
    <video controls width="600">
        <source src="https://samplelib.com/lib/preview/mp4/sample-5s.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <!-- Embedding a YouTube Video -->
    <h2>Watch on YouTube 🎬</h2>
    <iframe width="560" height="315" 
        src="https://www.youtube.com/embed/IUN664s7N-c" 
        title="YouTube Video" frameborder="0" 
        allow="autoplay; encrypted-media" allowfullscreen>
    </iframe>

    <!-- Registration Form with Validation -->
    <h2>Sign Up Form 📝</h2>
    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required placeholder="Enter your name"><br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required><br><br>

        <label for="gender">Gender:</label>
        <select id="gender" name="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select><br><br>

        <input type="submit" value="Register">
    </form>

    <!-- Creating a Table -->
    <h2>Event Schedule 📅</h2>
    <table border="1">
        <tr>
            <th>Day</th>
            <th>Event</th>
            <th>Time</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Web Development Workshop</td>
            <td>10:00 AM - 12:00 PM</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Multimedia Showcase</td>
            <td>2:00 PM - 4:00 PM</td>
        </tr>
    </table>

    <!-- Creating a List -->
    <h2>Things to Explore 🔎</h2>
    <ul>
        <li>Interactive Web Forms</li>
        <li>HTML5 Audio and Video</li>
        <li>Responsive Web Design</li>
    </ul>

</body>
</html>

            <td>95</td>
        </tr>
        <tr>
            <td>Ann M</td>
            <td>Science</td>
            <td>89</td>
        </tr>
    </table>

    <!-- Creating a List -->
    <h2>My Favorite Fruits 🍎</h2>
    <ul>
        <li>Apple</li>
        <li>Banana</li>
        <li>Orange</li>
    </ul>

</body>
</html>

