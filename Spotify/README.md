# 🎵 Music Dataset Overview
This dataset was part of the Top 200 projects in the NVIDIA Llama-Index Contest, supporting the Abracadabra project — a Retrieval-Augmented Generation (RAG) system for intelligent playlist creation using LLMs.

#### Dataset Link:
🔗 [https://www.kaggle.com/datasets/devdope/200k-spotify-songs-light-dataset/data]()

## 📦 Dataset Overview
This lightweight version of the music dataset offers a simplified yet powerful subset of features for each track, making it ideal for:

- ⚡ Quick experiments

- 📈 Visualizations

- 🎭 Emotion-based music analysis

# 🧠 How Emotions Were Extracted
Emotions in the emotion column were automatically generated using a fine-tuned Hugging Face model:

🔗 [mrm8488/t5-base-finetuned-emotion]()

## 📊 Column Descriptions
#### 📌 Included Features
<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Description</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><code>artist</code></td><td>Name of the artist or music group.</td><td>Steven Wilson</td></tr>
    <tr><td><code>song</code></td><td>Title of the song.</td><td>The Raven That Refused to Sing</td></tr>
    <tr><td><code>emotion</code></td><td>Dominant emotion extracted from lyrics using a fine-tuned language model.</td><td>sadness</td></tr>
    <tr><td><code>variance</code></td><td>Variability measure across audio features of the song.</td><td>0.83</td></tr>
    <tr><td><code>Genre</code></td><td>Primary musical genre.</td><td>progressive</td></tr>
    <tr><td><code>Release Date</code></td><td>Year of release.</td><td>2013</td></tr>
    <tr><td><code>Key</code></td><td>Musical key.</td><td>F Maj</td></tr>
    <tr><td><code>Tempo</code></td><td>Tempo in BPM.</td><td>137</td></tr>
    <tr><td><code>Loudness</code></td><td>Average volume level in decibels (usually negative).</td><td>-13.07</td></tr>
    <tr><td><code>Explicit</code></td><td>Indicates whether the track contains explicit content.</td><td>No</td></tr>
    <tr><td><code>Popularity</code></td><td>Popularity score (0–100).</td><td>38</td></tr>
    <tr><td><code>Energy</code></td><td>Perceived energy level (0–100).</td><td>23</td></tr>
    <tr><td><code>Danceability</code></td><td>How danceable the track is (0–100).</td><td>29</td></tr>
    <tr><td><code>Positiveness</code></td><td>Positivity or valence score (0–100).</td><td>7</td></tr>
    <tr><td><code>Speechiness</code></td><td>Presence of spoken words (0–100).</td><td>3</td></tr>
    <tr><td><code>Liveness</code></td><td>Likelihood of the track being a live performance (0–100).</td><td>6</td></tr>
    <tr><td><code>Acousticness</code></td><td>Acoustic quality score (0–100).</td><td>20</td></tr>
    <tr><td><code>Instrumentalness</code></td><td>Likelihood that the track is instrumental (0–100).</td><td>34</td></tr>
  </tbody>
</table>
