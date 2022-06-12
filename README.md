<img src = 'https://www.secretshoresmusic.com/wp-content/uploads/2017/10/spotify-banner.png'><br>
# Spotify Top Hits (2000-2019) | Exploratory Data Analysis
--<br><br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)<br>

--

# About 
This notebook presents an **Exploratory Data Analysis** of the dataset <a href="https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019">Top Hits Spotify from 2000-2019</a> posted on Kaggle by user Mark Koverha.<br>
The dataset is formed by 2000 rows and 18 columns, whose content description is as follows: <br><br>

- **artist:** Name of the artist.<br><br>
- **song:** Name of the track.<br><br>
- **duration_ms:** Duration of the track in milliseconds.<br><br>
- **explicit:** Whether or not the content of a song is offensive or inappropriate for children.<br><br>
- **year:** Year of release of the track.<br><br>
- **popularity:** The higher the value the more popular the song is.<br><br>
- **danceability:** Describes how suitable the track is for dancing based on tempo, rythm stability, beat strength, and others, where a value closer to 0.0 indicates lower danceability and a value closer to 1.0 indicates higher danceability.<br><br>
- **energy:** It represents the perceptual measure of intensity and activity going from 0.0 to 1.0<br><br>
- **key:** What key the track is in. Uses integer to represent keys where 0 = C, 1 = C♯/D♭, 2 = D, and so on. In case there's no key detected, the value is -1.<br><br>
- **loudness:** Represents the overall loudness of a track in decibels (dB) and it's the quality of a sound that is the primary psychological correlate of physical strength (amplitude). Loudness values are averaged across the entire track, with values typically between the range of -60 and 0 dB.<br><br>
- **mode:** Indicates if the track is in a major or in a minor scale, where major = 1 and minor = 0.<br><br>
- **speechiness:** It detects the presence of spoken words in a track. The more exclusively speech-like the recording, for instance a talk show or an audiobook, the closer to 1.0 will be the attributed value. Values above 0.66 describe tracks that are mostly made entirely of spoken words, while values between 0.33 and 0.66 describe tracks that may contain both music and speech. Values below 0.33 most likely represent music and other non-speech tracks. <br><br>
- **acousticness:** A confidence measure from 0.0 to 1.0 that indicates whether a track is acoustic or not, where 1.0 represents high confidence the track **is** acoustic.<br><br>
- **instumentalness:** Predicts if the track contains vocals or not. The closer its value is to 1.0, the greater likelihood the track contains no vocals. Any value above 0.5 is intended to represent instrumental tracks, but confidence is higher as the value approaches 1.0. "Ohh"s and "aah"s are treated as instrumental in this context.<br><br>
- **liveness:** Detects the presence of an audience in the recording. A value above 0.8 indicates higher probability that the track was performed live.<br><br>
- **valence:** A measure from 0.0 to 1.0 that describes the positiveness conveyed by the track. Tracks with higher valence may trigger positive emotions, such as happiness, cheerfulness and euphoria, while tracks with lower valence may trigger negative emotions, such as sadness, depression and anger.<br><br>
- **tempo:** Tempo in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.<br><br>
- **genre:** Genre of the track.<br><br>

Different techniques of **data transformation** and **data treatment** were used in order to make it easier to make studies using *data visualization* with **matplotlib**, **seaborn** and **plotly** libraries.<br><br>


---

#### Kaggle
In order to have a better comprehension and interaction with **plotly charts** used in this study, please <a href="https://www.kaggle.com/code/lusfernandotorres/spotify-top-hits-2000-2019-eda">click here to view this notebook on Kaggle</a>.

## Author:
**Luís Fernando Torres**
