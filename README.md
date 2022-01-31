# HW2.md

# Nations' Debt-to-GDP Ratios

<iframe src="https://data.oecd.org/chart/6Bm3" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6Bm3" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>



# Grid of Lines Chart Visualization of Debt-to-GDP Ratios Across Time

<div class="flourish-embed flourish-chart" data-src="visualisation/8566207"><script src="https://public.flourish.studio/resources/embed.js"></script></div>



# Grid of Stacked Area Chart Visualization of Debt-to-GDP Ratios

<div class="flourish-embed flourish-chart" data-src="visualisation/8566477"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


# Different Visualization Techniques and Further Questions

The first graph shows a snapshot of the Debt-to-GDP ratios of each nation (gathered from a publicly-available OECD dataset, link at bottom of each visualization), from smallest to largest, in the year 2020. This type of visualization is useful for a one year comparison of all nations, but doesn't show trends. For instance, are those nations with higher ratios experiencing higher levels because of some sort of precipitating event, or have their ratios always been that high? Likewise, are there nations that have worked hard to improve their ratios and have experienced reductions? This visualization will not be able to answer these questions.

The second visualization is a Grid of Lines Chart that shows Debt-to-GDP ratios across time, from 1996-2020 for all nations. This has an advantage over the previous graph in that we can see if there are common trends among nations or outliers in terms of behavior. However, it is still a huge amount of information all colorized the same way, which can be overwhelming to a reader.

The third visualization is a compromise on what I was trying to research how to do; I was tinkering with a "Horce-race" florish template, that would have shown the respective rankings of nations' ratios over time, moving dynamically year-to-year. However, I realized that the way the data is presented in its current form does not allow for these types of visualizations, and only allows for either grid views of each nation, or one single graph of one nation over time. This is because dates are not unique in the dataset; we would need nations to be in a column (unique entries only, not multiple), and years to be on the top row, with ratios in the matrix between. Given that I wasn't able to translate the data to such a format, I decieded to do another grid setup, but stacked area charts instead. I thought this might be a bit easier for readers to digest, with the area below each line now filled in. it feels a bit more solid and the trends look a bit clearer, with higher ratios being more obvious and drawing one's eyes.
