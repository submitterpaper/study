# Training – Visualization and Text

Sometimes you will see both the visualization and the text, in the "Visualization and Text" condition. In the sidebar, you can see some sample questions. Try to answer them. If you are unsure, click "Check Answer" to get help.

<h1 style="text-align: center;">Dataset: Movie Genres</h1>

<!DOCTYPE html>
<html>
<head>
    <style>
        .container {
            display: flex;
            gap: 20px;
        }
        .column {
            padding: 10px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="column">
        <img style="width: 460px;" src="./assets/T3.png" alt="Description of Image">
    </div>
    <div class="column">
        <h2>Dataset Introduction</h2>
        This UpSet plot shows movies and their genres. A movie can have multiple genres. The sets are movie genres. The items are movies. The intersections show how many movies have exactly the same genres.
        <h2>Dataset Properties</h2>
        <p>The dataset contains 17 sets and 6303 elements, of which 8 sets are shown in the plot.</p>
        <h2>Set Properties</h2>
        <p>The set sizes are diverging a lot, ranging from 106 to 1603. The largest set is Drama with 1603 elements, followed by Comedy with 1200, Action with 503, Thriller with 492, Romance with 471, Horror with 343, SciFi with 276, and Mystery with 106.</p>
        <h2>Intersection Properties</h2>
        <p>The plot is sorted by size in descending order. There are 83 non-empty intersections, all of which are shown in the plot. The largest 5 intersections are Just Drama (993), Just Comedy (670), the empty intersection (367), Just Horror (182), and Drama, and Comedy (178).</p>
        <h2>Statistical Information</h2>
        <p>The average intersection size is 46, and the median is 4. The 90th percentile is 134, and the 10th percentile is 1. The largest set, Drama, is present in 32.5% of all non-empty intersections. The smallest set, Mystery, is present in 27.7% of all non-empty intersections.</p>
        <h2>Trend Analysis</h2>
        <p>The intersection sizes peak at a value of 993 and then drastically flatten down to 1. The empty intersection is present with a size of 367. An all set intersection is not present. The individual set intersections are in largest and large intersections. The low degree set intersections lie in small and large and medium sized intersections. The medium degree set intersections can be seen among small sized intersections. Among the small sized intersections, the high order set intersections are significantly present.</p>
    </div>
</div>

</body>
</html>
