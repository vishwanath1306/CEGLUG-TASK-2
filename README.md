<h1>Hello All</h1>

<h2>Second Task of LUG Projects</h2>

Given in this repository are 4 files, regarding the data of different fruits:<br>

<ol>
<li> <b>number.csv</b> contains the details of the ID of 100 fruits.</li><br> 
<li> <b>fruits.csv</b> contains the details of the Name of 100 fruits.</li><br>
<li> <b>price.csv</b> contains the details of the Price of 100 fruits.</li><br>
<li> <b>rotten.csv</b> has the data if that particular fruit is rotten or not.</li><br>
</ol>

<h4>In all the files, first entry is of first fruit, second entry of second fruit and so on.

<h3>Your task, if you choose to take it is:</h3><br>
<ol>
<li> Due to improper validations done by the developer, a lot of IDs are missing. Make a not of those IDs, 
if they're odd then replace them, else delete the entire product</li><br>
<li>Some names of the fruits are missing. If the ID of that fruit is missing,
then delete it. If ID has been found, replace it with 10th fruit name to its left.</li><br>
<li>Most of the prices are in float, where as some are missing or in int. Conver the price from int to float.
If the fruit is rotten, declare price as 0.00</li><br>
<li>As the entry was made by multiple people, they've used 1 or t for marking "true" and 0 or f for marking false.
Convert it to <b>t for true, f for false</b>.</li>
</ol>

<h4>Once cleaned the data must be neatly organised in a file data.csv. It must be organised
in the format ID,Name,Price,Rotten</h4>

<h5>BONUS: Try to plot a line graph between price of fruit and ID of the fruit using MatPlotLib library</h5>
