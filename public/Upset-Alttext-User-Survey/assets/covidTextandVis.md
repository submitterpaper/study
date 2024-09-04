<h1 style="text-align: center;">Dataset: Covid Symptoms</h1>

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
        <img style="width: 500px;" src="./assets/VO1.png" alt="Description of Image">
    </div>
    <div class="column">
        <h2>UpSet Introduction</h2>
        This UpSet plot shows covid cases and their symptoms. A covid case can have multiple symptoms. The sets are covid symptoms. The items are covid cases. The intersections show how many covid cases have exactly the same symptomps.
        <h2>Dataset Properties</h2>
        <p>The dataset contains 6 sets and 4340 elements, of which 6 sets are shown in the plot.</p>
        <h2>Set Properties</h2>
        <p>The set sizes are diverging a lot, ranging from 148 to 1531. The largest set is Fatigue with 1531 elements, followed by Anosmia with 1051, Cough with 897, Fever with 363, Diarrhea with 350, and Shortness of Breath with 148.</p>
        <h2>Intersection Properties</h2>
        <p>The plot is sorted by size in descending order. There are 32 non-empty intersections, all of which are shown in the plot. The largest 5 intersections are Anosmia, and Fatigue (281), Cough, Anosmia, and Fatigue (259), Just Fatigue (198), Cough, and Fatigue (179), and Just Anosmia (140).</p>
        <h2>Statistical Information</h2>
        <p>The average intersection size is 55, and the median is 24. The 90th percentile is 179, and the 10th percentile is 7. The largest set, Fatigue, is present in 78.1% of all non-empty intersections. The smallest set, Shortness of Breath, is present in 34.4% of all non-empty intersections.</p>
        <h2>Trend Analysis</h2>
        <p>The intersection sizes peak at a value of 281 and then drastically flatten down to 1. An all set intersection is present with a size of 23. The individual set intersections are large in size. The low degree set intersections lie in largest sized intersections. The medium degree set intersections can be seen among small and medium and large sized intersections. Among the medium sized intersections, the high order set intersections are significantly present.</p>
    </div>
</div>

</body>
</html>
