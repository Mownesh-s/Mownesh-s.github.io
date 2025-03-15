<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
        }
        .projects-title {
            text-align: center;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        .project-card:hover {
            transform: scale(1.05);
        }
        .project-title {
            font-size: 1.3em;
            font-weight: bold;
        }
        .project-description {
            margin: 10px 0;
        }
        .project-links {
            margin-top: 10px;
        }
        .btn {
            display: inline-block;
            padding: 8px 12px;
            margin-right: 10px;
            text-decoration: none;
            color: white;
            border-radius: 5px;
            font-size: 0.9em;
        }
        .repo-btn {
            background-color: #007bff;
        }
        .live-btn {
            background-color: #28a745;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2 class="projects-title">🚀 My Projects</h2>
        <div class="projects-grid">
            
            <!-- Multiclass Classification -->
            <div class="project-card">
                <div class="project-title">Multiclass Classification</div>
                <p class="project-description">Performed classification on diabetes data using Random Forest, LightGBM, and XGBoost.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
            
            <!-- Multi-Output Regression Analysis -->
            <div class="project-card">
                <div class="project-title">Multi-Output Regression Analysis</div>
                <p class="project-description">Built a Multi-Output Regression model to predict life expectancy and BMI using ensemble learning.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
            
            <!-- Sentiment Analysis with Deep Learning -->
            <div class="project-card">
                <div class="project-title">Sentiment Analysis with Deep Learning</div>
                <p class="project-description">Built an end-to-end deep learning model for sentiment classification on IMDB Reviews dataset.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
            
            <!-- Exploratory Data Analysis on Used Cars Dataset -->
            <div class="project-card">
                <div class="project-title">EDA on Used Cars Dataset</div>
                <p class="project-description">Performed extensive Exploratory Data Analysis on a used cars dataset to uncover insights and trends.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
            
            <!-- Walmart Sales Data Analysis using PostgreSQL -->
            <div class="project-card">
                <div class="project-title">Walmart Sales Data Analysis</div>
                <p class="project-description">Analyzed Walmart sales data using PostgreSQL to generate key insights and trends.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
            
            <!-- IPL Dashboard - Power BI Project -->
            <div class="project-card">
                <div class="project-title">IPL Dashboard - Power BI Project</div>
                <p class="project-description">Designed an interactive IPL performance dashboard using Power BI for real-time insights.</p>
                <div class="project-links">
                    <a href="#" class="btn repo-btn">Repo</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
