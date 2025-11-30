<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>English Scroll</title>

<!-- Calligraphy Font -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">

<style>
    body {
        background: #f2e6c9;
        margin: 0;
        padding: 0;
        font-family: Georgia, serif;
        display: flex;
        justify-content: center;
    }

    /* Scroll borders on left and right */
    .side-scroll {
        width: 150px;
        background-image: url('https://www.pngall.com/wp-content/uploads/2016/07/Scroll-PNG-Clipart.png');
        background-size: cover;
        background-position: center;
    }

    /* Main content area */
    .page {
        max-width: 900px;
        background: #fff8e7;
        padding: 20px 40px;
        border-left: 4px solid #b58b4c;
        border-right: 4px solid #b58b4c;
        box-shadow: 0px 4px 10px rgba(0,0,0,0.3);
    }

    /* Header scroll banner */
    .scroll-banner {
        width: 100%;
        padding: 60px 20px;
        text-align: center;
        background-image: url('https://www.pngall.com/wp-content/uploads/2016/07/Scroll-PNG-Clipart.png');
        background-size: cover;
        background-position: center;
        border-top: 5px solid #8b5a2b;
        border-bottom: 5px solid #8b5a2b;
        margin-bottom: 20px;
    }

    .scroll-banner h1 {
        font-family: 'Great Vibes', cursive;
        font-size: 90px;
        color: #4b2e0f;
        margin: 0;
        text-shadow: 3px 3px 6px #e8d7b4;
        letter-spacing: 3px;
    }

    h2 {
        text-align: center;
        color: #4b2e0f;
        font-size: 32px;
    }

    ul {
        font-size: 20px;
        line-height: 1.7;
    }

    a {
        color: #7a4a1f;
        text-decoration: none;
        font-weight: bold;
    }

    a:hover {
        text-decoration: underline;
    }
</style>

</head>
<body>

<!-- Left scroll border -->
<div class="side-scroll"></div>

<!-- Center page content -->
<div class="page">

    <div class="scroll-banner">
        <h1>English Scroll</h1>
    </div>

    <h2>English Grammar for College Students</h2>

    <p>Welcome! This site provides clear explanations and helpful links to master English grammar at the college level.</p>

    <p>Use the links below to navigate the main topics:</p>

    <ul>
        <li><a href="parts-of-speech.md">Parts of Speech</a></li>
        <li><a href="sentence-structure.md">Sentence Structure</a></li>
        <li><a href="punctuation.md">Punctuation</a></li>
        <li><a href="academic-grammar.md">Academic Grammar</a></li>
        <li><a href="common-errors.md">Common Errors</a></li>
        <li><a href="practice.md">Practice Exercises</a></li>
        <li><a href="readings.md">Readings</a></li>
    </ul>

</div>

<!-- Right scroll border -->
<div class="side-scroll"></div>

</body>
</html>
