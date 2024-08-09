<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Dataset Analysis</title>
</head>
<body>

<h1>Movie Dataset Analysis</h1>

<h2>Overview</h2>
<p>This project performs an exploratory data analysis (EDA) and presents insights using a dataset containing information about various movies. The analysis includes data inspection, filtering, and visualization techniques to explore different aspects of the dataset, such as revenue, budget, profitability, and other key movie metrics.</p>

<h2>Dataset</h2>
<p>The dataset used in this project is <code>movies_complete.csv</code>. It contains detailed information about movies, including:</p>
<ul>
    <li><strong>id:</strong> Unique identifier for each movie</li>
    <li><strong>title:</strong> Official title of the movie</li>
    <li><strong>tagline:</strong> Tagline of the movie</li>
    <li><strong>release_date:</strong> Theatrical release date</li>
    <li><strong>genres:</strong> Genres associated with the movie</li>
    <li><strong>belongs_to_collection:</strong> Information on the movie series/franchise</li>
    <li><strong>original_language:</strong> Language in which the movie was originally shot</li>
    <li><strong>budget_musd:</strong> Budget of the movie in million dollars</li>
    <li><strong>revenue_musd:</strong> Total revenue of the movie in million dollars</li>
    <li><strong>production_companies:</strong> Production companies involved in the movie</li>
    <li><strong>production_countries:</strong> Countries where the movie was produced</li>
    <li><strong>vote_count:</strong> Number of user votes on TMDB</li>
    <li><strong>vote_average:</strong> Average rating of the movie</li>
    <li><strong>popularity:</strong> Popularity score assigned by TMDB</li>
    <li><strong>runtime:</strong> Runtime of the movie in minutes</li>
    <li><strong>overview:</strong> A brief blurb of the movie</li>
    <li><strong>spoken_languages:</strong> Languages spoken in the movie</li>
    <li><strong>poster_path:</strong> URL of the poster image</li>
    <li><strong>cast:</strong> Main actors appearing in the movie</li>
    <li><strong>cast_size:</strong> Number of actors appearing in the movie</li>
    <li><strong>director:</strong> Director of the movie</li>
    <li><strong>crew_size:</strong> Size of the film crew (excluding actors)</li>
</ul>

<h2>Analysis Summary</h2>

<h3>1. Data Import and Inspection</h3>
<ul>
    <li>Imported the dataset using Pandas and inspected its structure using <code>.info()</code> and <code>.describe()</code> methods.</li>
    <li>Explored the distribution of key numerical features through histograms.</li>
</ul>

<h3>2. Best and Worst Movies</h3>
<ul>
    <li>Filtered the dataset to identify the best and worst movies based on various metrics:
        <ul>
            <li>Highest and lowest revenue</li>
            <li>Highest and lowest budget</li>
            <li>Highest and lowest profit</li>
            <li>Highest and lowest return on investment (ROI)</li>
            <li>Most and least voted movies</li>
            <li>Highest and lowest rated movies</li>
            <li>Most popular movies</li>
        </ul>
    </li>
</ul>

<h3>3. Movie Recommendations</h3>
<ul>
    <li>Developed a user-defined function to filter and sort the dataset based on specific criteria, such as:
        <ul>
            <li>Science Fiction Action movies featuring Bruce Willis</li>
            <li>Movies with Uma Thurman directed by Quentin Tarantino</li>
            <li>Most successful Pixar Studio movies between 2010 and 2015</li>
            <li>Action or Thriller movies in English with a minimum rating of 7.5</li>
        </ul>
    </li>
</ul>

<h3>4. Wordcloud Visualization</h3>
<ul>
    <li>Generated word clouds to visualize the most common words in movie titles, taglines, and overviews.</li>
</ul>

<h3>5. Franchise Success Analysis</h3>
<ul>
    <li>Analyzed whether movies that belong to a franchise are more successful than standalone movies in terms of:
        <ul>
            <li>Mean revenue</li>
            <li>Median ROI</li>
            <li>Mean budget</li>
            <li>Mean popularity</li>
            <li>Mean rating</li>
        </ul>
    </li>
</ul>

<h3>6. Most Successful Franchises and Directors</h3>
<ul>
    <li>Identified the most successful franchises and directors based on total movies, revenue, and ratings.</li>
    <li>Analyzed the impact of actors on movie success, including total revenue, mean rating, and popularity.</li>
</ul>

<h2>Visualizations</h2>
<p>Various visualizations were created using Matplotlib to illustrate key insights, including bar charts and histograms. Word clouds were generated to visualize frequent terms in movie titles, taglines, and overviews.</p>

<h2>How to Run the Analysis</h2>
<ol>
    <li>Ensure you have Python installed along with the necessary libraries:
        <ul>
            <li>Pandas</li>
            <li>Matplotlib</li>
            <li>NumPy</li>
            <li>IPython</li>
            <li>WordCloud</li>
        </ul>
    </li>
    <li>Clone the repository to your local machine:
        <pre><code>git clone https://github.com/sajinpaloli/Baby-names-Data-analysis.git</code></pre>
    </li>
    <li>Place the <code>movies_complete.csv</code> file in the same directory as the script.</li>
    <li>Run the script to perform the analysis.</li>
</ol>

<h2>Future Work</h2>
<ul>
    <li>Further analysis can be conducted on the dataset by exploring additional relationships and metrics.</li>
    <li>More visualizations and machine learning models could be applied to predict movie success.</li>
</ul>


</body>
</html>
