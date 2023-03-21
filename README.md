# CryptoClustering

---

## Project Introduction

A collective insanity has sprouted around Bitcoin over the last decade. The thrill of riches or ruin leaves some investors wary, but others want to chase the chance for massive profits from investing in Bitcoin. This project attempts to utilize unsupervise learning to see if cryptocurrencies are affected by 24-hour or 7-day price changes.

### Methodology

Bitcoin data was normalized with standard scaler.
The elbow method, and PCA analysis was conducted to determine the number of clusters and to reduce dimensionality.
KMeans algorithim was used to cateogrize bitcoin market data for further investigation. 


#### Dependencies

- Pandas/Numpy
- HV Plots
- Sci-Kit Learn | KMeans

#### Results

![bokeh_plot](https://user-images.githubusercontent.com/89043234/225771732-d3b9f053-16aa-4c96-9e6a-a652c6450ec0.png)

Based on the elbow method, the number of clusters is 4. 

![bokeh_plot (1)](https://user-images.githubusercontent.com/89043234/225772033-1757d65c-4bf9-48ea-ad58-d5f97bc31ed6.png)

The scatter plot illustrates the four groups generated by K-means, and the groups act as a segway for further investigation. 

---


---

