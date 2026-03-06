# CS4804 Final Project - Visualizing Snowfall Prediction
Authors: Aditya Patel, Karinne Aiello, Victor Radina

## Project Overview
This project is an interactive web visualization that helps users better interpret probabilistic snowfall forecasts. Viewers can input their own predicted probabilities by visiting a website like [this one] to find a bar chart of the likelihood of various levels of snowfall in their area. The interface will then convert this information into two visualization formats:
- Quantile Dot Plot
- Original Bar Chart

The quantile dot plot represents the data as hypothetical discrete storms, making snowfall predictions easier to understand. Each dot--or snowflake, in our case--reflects one of 20 possible storms. More details are available in the Process Book.

## Important Links
- Live Website with Interactive Visualizations: https://vradina.github.io/final/
- Process Book: https://github.com/vradina/final/blob/main/Process%20Book.pdf
- Explanatory Screencast:

## Code Structure and Libraries
index.html - comprises all our application logic

main.css - outlines our custom styling for our website

Vega - used to generate the quantile dot plot

PicoCSS - offers basic layout and form styling
