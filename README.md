# Histo-Scatter-Area-Plot, with randomer
Inspired by a chart seen on the Bloomberg News website and a visit to the Danish Design Museum in Copenhagen, this cross between a histrogram, a scatterplot and a filled area chart is ideal for visualising a change in a series of values over two points in time, especially where they skew positively and negatively in an oppossing manner. 

![image](https://user-images.githubusercontent.com/69304112/210713500-6faa36f0-5fa9-4a95-8b1e-2ab0c298c3fa.png)

The x axis represents the change in value (as a percent) that a percentile/bin has experienced.

The y axis represents the "original share" of each percentile - in other words, its proportion of the original sum of values. 

Rectangeles that skew negative are denoted by red, and those that are positive with green.

For illustrative purposes, this version includes functions to create a dataframe of random values.

I have used this HSA Plot, for example, to illustrate changes in airport traffic changes during the pandemic for airports in different percentiles. This showed audiences that many smaller airports had experienced an uptick in traffic at the same time as major airports had experienced a down turn.

Link: http://constituent.au/exposing_cronyism_through_aviation_data_analysis.html
