# cultural.musicology.portfolio
In this repository I will be uploading the weekly assignmnets for the Cultural Musicology course. 
(Weekly assignment 5 (Week 12) is below Weekly assignment 3)


# Weekly Assignment 3
As I already introduced in my first assignment upload, I would like to analyze Rosalia’s musical evolution throughout her 4 studio albums *Los Angeles*, *El Mal Querer*, *Motomami* and *Lux*.

Last week, I created different chromograms comparing the four chosen songs that I will be using to analyze the different Rosalia's albums. 

The conclusion was that, except for “Catalina” and “Malamente” (which, as I said, are both rooted in flamenco), the chosen Rosalia’s songs are harmonically very different. 

This week, I want to compare "Catalina" and "Berghain", which are the songs from her first and last album. I will be doing a **cepstrogram** from both of the songs so I can have a better visualization of them. This way, I will have more insights when analysing both songs' vocal timbre, harmonic richness, and production aesthetics.


## Cepstrogram from "Catalina" 

![Cepstrogram Catalina](https://github.com/luciahita/cultural.musicology.portfolio/blob/main/catalina_cepstogram.png?raw=true)


## Cepstrogram from "Berghain"

![Cepstrogram Berghain](https://github.com/luciahita/cultural.musicology.portfolio/blob/main/berghain_cepstogram.png?raw=true)


Both of the images show very clean cepstrograms. In the "Catalina" cepstrogram, I can see how in the lower MFCC coefficients (more or less from mfcc_02 to mfcc_05), there is clearly more fluctuations and dynamic variation across time than in the higher ones. The higher coefficients remain relatively stable and low-intensity. This might be due to its higher vocal frequence. 


In the "Berghain" cepstrogram, there is a stronger intensity in mfcc_02 (very bright yellow activity). Towards the end,  there is a noticeable block of spectral change (the uniform darker region). This fits with the final moment of the song in which the music (melody and vocals) swifts completely (the "I'll f*** you till you love" part). 

In conclusion, "Berghain" shows stronger and more constant low-order MFCC energy, which goes hand in hand with the thicker production and greater low-frequency emphasis. "Catalina" appears lighter and more fluctuating. The cepstrograms, therefore, suggest that "Catalina" is based on vocal expressivity, whereas "Berghain" emphasizes textural density and production-driven timbral stability. 




# Weekly Assignment 5
For this last assignment, I will firstly compare the three different dendrograms comparing the four chosen Rosalia's songs to see which one shows more details about the differences between them. Secondly, I will analyze the heatmap of these four chosen songs on which I will base my final analysis. 


## Hierarchical clustering for "Catalina", "Malamente", "CUUUUuuuuuute" and "Berghain"

![Single Dendrogram](https://github.com/luciahita/cultural.musicology.portfolio/blob/main/dendrogram_single.png)
**Single Dendrogram**

The single linkage dendrogram shows a chaining effect, where clusters are formed based on the closest individual points between songs. In this case, the chosen Rosalía’s tracks appear more loosely connected. I noticed an earlier merging between *Berghain* and *CUUUUuuute* than between *Catalina* and *Malamente*. This suggests that there are minimal similarities such as timbral or rhythmic features that group the representative songs from Rosalia's latest albums together more quickly than the earlier ones. 




![Average Dendrogram](https://github.com/luciahita/cultural.musicology.portfolio/blob/main/dendrogram_average.png)
**Average Dendrogram**

The average linkage dendrogram provides a more balanced clustering, considering the average distance between all points in clusters. Here, *Berghain* and *CUUUUuuute* still cluster together first, but the structure is more stable and interpretable. *Catalina* joins this cluster at a moderate distance, while *Malamente* remains more distinct. This suggests again a gradual stylistic transition across the songs. 




![Complete Dendrogram](https://github.com/luciahita/cultural.musicology.portfolio/blob/main/dendrogram_complete.png)
**Complete Dendrogram**

The complete linkage dendrogram emphasizes the maximum distance between clusters, producing tighter and more separated groups. In this case, *Berghain* and *CUUUUuuute* again form the closest pair, but the separation between clusters is more pronounced. *Malamente* appears as the most distinct track, joining only at a high distance, indicating stronger dissimilarity in its musical characteristics.


<br><br><br>

All in all, there are certain conclusions that can be drawn from the three presented dendrograms. Firstly, *Berghain* and *CUUUUuuute* consistently cluster together, which conveys a strong similarity between Rosalia's representative songs from her 3rd and 4th studio albums. Secondly, *Malamente* is the most distinct track, which could be read as an stylistic outlier but, in my analysis, can be seen as a representative of the uniqueness of Rosalia's second studio album. Finally, *Catalina* occupies an intermediate position, which I think is interetsing considering it is the representative song from Rosalia's first studio album. 

For my final portfolio, I think I will choose the average linkage dendrogram because it avoids the chaining problem of the single one and it doesn’t over-separate like complete linkage. In conclusion, it gives a more realistic representation of the musical similarity of the four chosen songs. 

<br><br><br>

## Heatmap for "Catalina", "Malamente", "CUUUUuuuuuute" and "Berghain"


