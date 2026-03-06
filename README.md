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
- Explanatory Screencast: https://www.loom.com/share/f0ab4ab727f4434d9e9eeb2dd2452a67

## Code Structure and Libraries
index.html - comprises all our application logic  

main.css - outlines our custom styling for our website

Vega - used to generate the quantile dot plot  

PicoCSS - offers basic layout and form styling

## References
Bhatia, A., Katz, J., Sanger-Katz, M., & Jacoby, S. (2026, March 5). How Much Snow Will Fall Where You Live? The Upshot Newsletter. https://www.nytimes.com/interactive/2026/upshot/snow-forecast-totals-lookup.html  

Carroll, C. (2019, December 19). Quantile Dot Plots—Showcase. Matplotlib. https://discourse.matplotlib.org/t/quantile-dot-plots/20775  

Ibrekk, H., & Morgan, M. G. (1987). Graphical Communication of Uncertain Quantities to Nontechnical People. An Official Publication of the Society for Risk Analysis, 7(4). https://doi.org/10.1111/j.1539-6924.1987.tb00488.x  

Kay, M., Kola, T., Hullman, J. R., & Munson, S. A. (2016). When (ish) is My Bus?: User-centered Visualizations of Uncertainty in Everyday, Mobile Predictive Systems. ACM Conferences, 5093–5103. https://doi.org/10.1145/2858036.2858558  

McKenna, S., & Harrison, L. (n.d.). Designing Visualizations. Retrieved March 5, 2026, from https://canvas.wpi.edu/courses/80901/files?preview=8245390  

National Centers for Environmental Information. (n.d.). Climate Data Online Search. National Oceanic and Atmospheric Administration. Retrieved March 5, 2026, from https://www.ncdc.noaa.gov/cdo-web/search  

Quantile Dot Plot Example. (n.d.). Vega. Retrieved March 5, 2026, from https://vega.github.io/vega/examples/quantile-dot-plot/
