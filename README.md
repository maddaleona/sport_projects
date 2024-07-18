# WORK IN PROGRESS!!!

### Sport Projects
### Author: Maddalena Torricelli
--- Turning sports data into insightful and awesome visualizations ---

---

### Python Notebooks
#### a. Examples of using *plotly* package
1. [World cup 2010 final match: Spain vs Netherlands](https://htmlpreview.github.io/?https://github.com/maddaleona/sport_projects/blob/main/data/world_cup_2010_viz.html)
2. [test](<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toggle Figures</title>
    <script>
        function showFigure(figureId) {
            var figure1 = document.getElementById('figure1');
            var figure2 = document.getElementById('figure2');
            if (figureId === 'figure1') {
                figure1.style.display = 'block';
                figure2.style.display = 'none';
            } else if (figureId === 'figure2') {
                figure1.style.display = 'none';
                figure2.style.display = 'block';
            }
        }
    </script>
</head>
<body>
    <h2>Toggle Figures</h2>
    <button onclick="showFigure('figure1')">Show Figure 1</button>
    <button onclick="showFigure('figure2')">Show Figure 2</button>
    
    <div id="figure1" style="display:none;">
        <!-- Embed figure1.html here -->
        <!-- Example content, replace with actual content or use iframe for external HTML -->
        <iframe src="figure1.html" width="100%" height="500px" frameborder="0"></iframe>
    </div>
    
    <div id="figure2" style="display:none;">
        <!-- Embed figure2.html here -->
        <!-- Example content, replace with actual content or use iframe for external HTML -->
        <iframe src="figure2.html" width="100%" height="500px" frameborder="0"></iframe>
    </div>
</body>
</html>
)
