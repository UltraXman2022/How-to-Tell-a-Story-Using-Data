<h1>Project description</h1>
You’ve decided to open a small robot-run cafe in Los Angeles. The project is promising but expensive, so you and your partners decide to try to attract investors. They’re interested in the current market conditions—will you be able to maintain your success when the novelty of robot waiters wears off?
You’re an analytics guru, so your partners have asked you to prepare some market research. You have open-source data on restaurants in LA.
<h2>Instructions for completing the project</h2>
Step 1. Download the data and prepare it for analysis<br><br>
Download the data on restaurants in LA. Make sure that the data type for each column is correct and that there are no missing values or duplicates. Process them if necessary.
File path: /datasets/rest_data_us.csv. Download dataset<br>
<br>Step 2. Data analysis<br><br>
Investigate the proportions of the various types of establishments. Plot a graph.<br><br>
Investigate the proportions of chain and nonchain establishments. Plot a graph.<br><br>
Which type of establishment is typically a chain?<br><br>
What characterizes chains: many establishments with a small number of seats or a few establishments with a lot of seats?<br><br>
Determine the average number of seats for each type of restaurant. On average, which type of restaurant has the greatest number of seats? Plot graphs.<br><br>
Put the data on street names from the address column in a separate column.<br><br>
Plot a graph of the top ten streets by number of restaurants.<br><br>
Find the number of streets that only have one restaurant.<br><br>
For streets with a lot of restaurants, look at the distribution of the number of seats. What trends can you see?<br><br>
Draw an overall conclusion and provide recommendations on restaurant type and number of seats. Comment on the possibility of developing a chain.<br><br>
Step 3. Preparing a presentation<br><br>
Make a presentation of your research to share with investors.<br><br> You can use any tool you’d like (for example Google Slides or MS PowerPoint) to create it, but you must convert your presentation to PDF format for assessment. <br><br>Include a link to the presentation in a markdown cell in the following format:<br><br>
Presentation: <link to cloud storage> <br><br>
Follow the formatting guidelines from the “Preparing Presentations” chapter.<br><br>
Format: Complete the task in a Jupyter notebook. <br>Enter the code in code cells and text explanations in markdown cells. <br>Apply formatting and headings.<br><br>
Data description
<ul><li>rest_data table:
<li>object_name — establishment name</li>
<li>chain — chain establishment (TRUE/FALSE)</li></li>
<li>object_type — establishment type</li>
<li>address — address</li>
<li>number — number of seats</li></ul>      
