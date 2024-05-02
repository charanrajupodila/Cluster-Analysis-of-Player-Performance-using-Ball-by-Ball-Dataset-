# Cluster Analysis of Player Performance using Ball-by-Ball Dataset
## Problem Statement:
Now that this year's IPL auction is over, let's not curb our cricket love and start analyzing the whole of IPL with this latest and complete Indian Premier League dataset. It contains the ball by ball dataset. So, stop thinking and start analyzing.

Create clusters of IPL batsmen based on their strengths in order to show some of the best IPL batsmen of all time.

## Data Description
- **id**: Unique Match ID as per ESPNCricinfo.
- **inning**: Inning Number.
- **over**: Over Number.
- **ball**: Ball Number.
- **batsman**: Batsman on strike.
- **non_striker**: Batsman at non-striker end.
- **bowler**: Bowler.
- **batsman_runs**: Runs scored off bat.
- **extra_runs**: Extra runs conceded.
- **total_runs**: Total runs scored in the ball.
- **non_boundary**: Indicates if runs were scored through boundaries.
- **is_wicket**: Indicates if the delivery resulted in a wicket.
- **dismissal_kind**: Type of dismissal.
- **player_dismissed**: Player who got dismissed.
- **fielder**: Fielder involved in the dismissal.
- **extras_type**: Type of extras.
- **batting_team**: Batting team.
- **bowling_team**: Bowling team.

  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <head>
  <h1>IPL Batsmen Clustering - Tasks/Activities</h1>
  <body>
  <p>This analysis will involve the following steps:</p>
  <ol>
    <li><strong>Data Acquisition:</strong> Read and import the IPL dataset containing ball-by-ball information.</li>
    <li><strong>Exploratory Data Analysis (EDA):</strong>
      <ul>
        <li>Assess data quality by checking for missing values, inconsistencies, etc.</li>
        <li>Preprocess the data by handling missing values and outliers (if necessary).</li>
      </ul>
    </li>
    <li><strong>Data Analysis:</strong> Derive insights from the data by calculating relevant features for batsmen, such as:</li>
      <ul>
        <li>Total runs scored</li>
        <li>Strike rate</li>
        <li>Other batting metrics (e.g., average, fours, sixes)</li>
      </ul>
    <li><strong>Clustering:</strong> Apply various clustering algorithms to group batsmen based on their similarities:</li>
      <ul>
        <li>K-means clustering</li>
        <li>DBSCAN clustering</li>
        <li>Hierarchical clustering</li>
      </ul>
    <li><strong>Evaluation:</strong> Employ a performance metric to assess the effectiveness of the clustering algorithms in identifying distinct batsman groups.</li>
    <li><strong>Visualization:</strong> Create visualizations (scatter plots, etc.) to represent the clustered data and gain insights into batsman performance patterns.</li>
  </ol>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>IPL Batsmen Clustering - Success Metrics</h1>
  <p>The following criteria will be used to evaluate the success of this IPL batsmen clustering analysis:</p>
  <ul>
    <li>The cluster identified as containing the "best IPL players of all time" should primarily consist of players who meet the following criteria:</li>
      <ul>
        <li><strong>Matches Played:</strong> Minimum of 100 matches played in the IPL.</li>
        <li><strong>Runs Scored:</strong> Total runs scored exceeding 2500.</li>
      </ul>
  </ul>
</body>
</html>

  ## Run the Jupyter Notebook:
  Open a Jupyter Notebook environment and navigate to the downloaded repository. Locate and execute the Jupyter Notebook file containing the  analysis code. This will run 
  the analysis steps defined in the notebook.
