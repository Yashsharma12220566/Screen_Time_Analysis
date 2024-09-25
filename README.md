<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Behavior Insights - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>

<h1>User Behavior Insights</h1>

<h2>Overview</h2>
<p>This project analyzes user behavior and engagement metrics from an app, utilizing R for data visualization and exploration. It focuses on user demographics, screen usage patterns, enrollment status, and premium feature usage.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#data-description">Data Description</a></li>
    <li><a href="#visualizations">Visualizations</a></li>
    <li><a href="#libraries-used">Libraries Used</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="installation">Installation</h2>
<p>To run this project, you'll need to have R installed along with the required packages. You can install the necessary packages using the following commands in your R console:</p>
<pre><code>install.packages("ggplot2")
install.packages("dplyr")
install.packages("gridExtra")</code></pre>

<h2 id="usage">Usage</h2>
<ol>
    <li>Load the required libraries:
        <pre><code>library(ggplot2)
library(dplyr)
library(gridExtra)</code></pre>
    </li>
    <li>Load the dataset and run the analysis:
        <ul>
            <li>You can modify the dataset as per your needs in the script provided.</li>
            <li>The script contains visualizations for age distribution, enrollment status, and more.</li>
        </ul>
    </li>
    <li>Execute the script to view the arranged plots.</li>
</ol>

<h2 id="data-description">Data Description</h2>
<p>The dataset includes the following columns:</p>
<ul>
    <li><strong>user</strong>: Unique user ID.</li>
    <li><strong>first_open</strong>: Time of first app open.</li>
    <li><strong>dayofweek</strong>: Day of the week (0 = Sunday, 6 = Saturday).</li>
    <li><strong>hour</strong>: Time of activity in HH:MM:SS format.</li>
    <li><strong>age</strong>: Age of the user.</li>
    <li><strong>screen_list</strong>: Sequence of screens accessed by the user.</li>
    <li><strong>numscreens</strong>: Number of screens accessed.</li>
    <li><strong>minigame</strong>: Indicates if a mini-game was played (1 = Yes, 0 = No).</li>
    <li><strong>used_premium_feature</strong>: Indicates if a premium feature was used (1 = Yes, 0 = No).</li>
    <li><strong>enrolled</strong>: Indicates if the user is enrolled in a program (1 = Yes, 0 = No).</li>
    <li><strong>liked</strong>: Indicates if the user liked the app (1 = Yes, 0 = No).</li>
</ul>

<h2 id="visualizations">Visualizations</h2>
<p>The project generates several visualizations to analyze user behavior:</p>
<ul>
    <li><strong>Age Distribution</strong>: Histogram of user ages.</li>
    <li><strong>Enrollment Status</strong>: Bar chart showing enrolled vs. not enrolled users.</li>
    <li><strong>Liked vs. Not Liked</strong>: Bar chart depicting users' feedback on the app.</li>
    <li><strong>Day of the Week Distribution</strong>: Frequency of app usage by day.</li>
    <li><strong>Hourly Distribution</strong>: Histogram of usage by hour.</li>
    <li><strong>Premium Feature Usage</strong>: Pie chart illustrating usage of premium features.</li>
    <li><strong>Age vs. Number of Screens</strong>: Line, bar, and scatter plots to analyze the relationship between age and the number of screens accessed.</li>
</ul>

<h2 id="libraries-used">Libraries Used</h2>
<ul>
    <li><strong>ggplot2</strong>: For creating visualizations.</li>
    <li><strong>dplyr</strong>: For data manipulation.</li>
    <li><strong>gridExtra</strong>: For arranging multiple plots.</li>
</ul>

<h2 id="license">License</h2>
<p>This project is licensed under the MIT License. Feel free to modify and distribute the code as per your needs.</p>

<h3>For any questions or suggestions, please feel free to reach out!</h3>

</body>
</html>
