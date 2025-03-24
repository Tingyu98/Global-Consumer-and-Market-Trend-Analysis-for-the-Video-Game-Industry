# Video-Game-Sales-Exploratory-Data-Analysis
[Introduction](#Introduction) /
[Features](#Features) /
[Key Finding](#Key_Finding) /
[Results](#Results) /
[Discussion](#Discussion) /
[Conclusions](#Conclusions) /
[Data Sources](#Data_Sources) /
[Extended Analysis](#Extended_Analysis)

## Introduction
The global video game industry has become one of the most dynamic and profitable entertainment sectors. To remain competitive, it is essential to understand the factors influencing sales. This project aims to analyze historical data to uncover key trends, including the most successful genres, platforms, publishers, and regional preferences across North America, Europe, and Japan.

Additionally, the analysis will explore the relationship between a country’s GDP and video game sales, shedding light on how economic factors influence market performance. The findings will be presented using intuitive visualizations to ensure clarity and accessibility, enabling video game companies and stakeholders to leverage these insights for strategic decision-making and market expansion.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Features
- Exploratory data analysis (EDA)
- Visualization
- Tools and frameworks (R, ggplot2, dplyr, tidyverse, Plotly)

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Key_Finding
- Global Trends: Video game sales peaked in the late 2000s, followed by a decline due to market saturation and competition from mobile and online gaming.
- Popular Genres: Action games became the leading genre, surpassing sports games in releases and sales, especially on platforms like PS2, Xbox 360, and PS3.
- Regional Insights: North America led in sales, followed by Europe and Japan, with Japan showcasing stable performance despite economic fluctuations.
- Top Performers: Blockbuster games like Wii Sports and publishers such as Nintendo dominated the market, significantly influencing industry trends.
- Economic Correlation: GDP and sales trends aligned before 2008, but sales recovery lagged behind GDP post-crisis, except in Japan, where sales remained steady.
- Consumer Behavior: Higher IGN scores (above 7.5) generally correlated with greater sales, though exceeding this threshold did not guarantee higher performance. Steam reviews showed greater variability, even among top-selling games.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Results
<img width="703" alt="image" src="https://github.com/user-attachments/assets/0bc8ac68-b2d4-4d06-a0fe-4618f91e25a0" />

Figure 1 illustrates the trend in global video game sales from 1980 to 2020, highlighting significant changes over time. We observe a peak in the late 2000s, with total global sales reaching 678.9 million units, indicated in orange as the highest point. The steady decline after 2010 likely reflects market saturation, increasing competition from mobile and online gaming, and shifting consumer preferences. This trend emphasizes the evolving dynamics of the gaming industry and the challenges faced by traditional video game platforms in adapting to these
changes.

<img width="723" alt="image" src="https://github.com/user-attachments/assets/7b13831b-cc17-4576-9e84-96224decba3d" />

Figure 2 shows the number of games released in each genre per year, allowing us to see how the popularity of different game genres has evolved. From the 1980s to early 2000s, there was a steady 
increase in the number of game releases across various genres, reflecting industry growth and increased interest in gaming. A notable peak appears around 2008-2010. After 2010, there is a noticeable decline. In the early period shown in the chart, sports games (pink line) had a higher count, indicating their popularity at that stage. However, over time, action games (red line) gradually caught up and eventually surpassed sports games in release numbers2. Over time, action games firmly established themselves as the genre with the highest number of releases.

<img width="729" alt="image" src="https://github.com/user-attachments/assets/ab87e8bb-bf41-4d46-8f8e-66b66a0f6bda" />

Figure 3 illustrates the global sales of video games across the top 10 platforms and various genres. The intensity of the color represents total sales in millions, with deeper red shades indicating higher sales. The PS2, Xbox 360, and PS3 are the top three platforms in total sales, showing strong performance in genres such as Action, Sports, and Shooter. Action games stand out as the top-performing genre overall, particularly on the PS3 and PS2, while Sports games also demonstrate significant popularity, especially on the Wii and PS2. In contrast, Puzzle, Simulation, and Strategy are all relatively light in shading across the board, which is representative of their relatively low overall sales contributions.

<img width="725" alt="image" src="https://github.com/user-attachments/assets/03219ca9-9b6c-49f4-98e4-e9ed1c6ff162" />

In Figure 4, each bar represents a region, with its height indicating the total video game sales volume. North America clearly leads with the highest total sales, significantly surpassing Europe, Japan, and other regions. Europe ranks second, reflecting its strong presence in the global video game market. Notably, the data for Europe and North America are aggregated from multiple countries, while Japan's data represents a single country. This highlights Japan's remarkable performance and underscores its status as a major video game powerhouse, emphasizing its substantial contribution to the global gaming industry.

<img width="697" alt="image" src="https://github.com/user-attachments/assets/74bab0e4-d23d-4865-975e-dd8e0ac0ddb4" />

Figure 5 illustrates the sales distribution across various game genres and regions using a stacked bar chart. Each bar represents a genre, with different colors showing the contribution of
each region, including North America, Europe, Japan, and others. The chart highlights that the Action genre dominates sales, particularly in the North American region. The Sports and Shooter genres also perform strongly across all regions. In contrast, genres such as Puzzle, Strategy, and Adventure exhibit lower sales overall. North America consistently demonstrates higher sales across most genres, highlighting its significant market potential for game developers.

<img width="705" alt="image" src="https://github.com/user-attachments/assets/293b01cd-c3dc-42a1-8f4d-7514fd9fca38" />

Figure 6 effectively illustrates the proportions of global sales among the top 10 video games. Each rectangle in the treemap represents a game, with its size corresponding to its global sales volume. The result shows that "Wii Sports" occupies the largest area, representing 82.74 million global sales. "Super Mario Bros." and "Mario Kart Wii" also stand out as leading games in global sales. This visualization underscores the significance of blockbuster games in shaping the video game industry.

<img width="735" alt="image" src="https://github.com/user-attachments/assets/ef2468c4-7612-42c6-aa8d-49eec9d7d91a" />

Figure 7 highlights the top 10 video game publishers by global sales, with Nintendo leading by a significant margin, followed by Electronic Arts and Activision. This bar chart emphasizes Nintendo's market dominance and the critical role of major publishers in shaping the global video game industry. Furthermore, many of the top-selling games mentioned in Figure 6, such as Wii Sports and Mario Kart Wii, were developed by Nintendo, reinforcing its influential position in the market.

<img width="726" alt="image" src="https://github.com/user-attachments/assets/80f9a446-eb49-40e7-873e-b262961b5abd" />

Figure 8 presents three key pieces of data. The multiple thin lines represent the GDP per capita of various European countries. To simplify the analysis, we averaged these values into a single thick black line. Additionally, a thick red line represents the total video game sales in Europe, based on the release year of the games. A secondary y-axis is included to reflect the scale of the red line3. It is important to note that the y-axis for sales does not represent the sales made in a specific year but rather the total sales of games released in that year.

While this approach differs from measuring annual sales, it is reasonable to assume that most game sales occur within the same year of release, especially for games without significant updates. The chart reveals that both GDP and video game sales experienced growth from the late 1990s until the 2008 financial crisis. However, while GDP began to recover after the crisis, video game sales did not follow the same trend. This divergence could be attributed to businesses exercising caution in an uncertain economic climate, resulting in fewer investments in the video game industry during this period.

<img width="714" alt="image" src="https://github.com/user-attachments/assets/00842135-f7b2-466d-a833-e0fb8cb2ae2d" />

In Figure 9, the thick black line represents the average GDP of the North American region, while the thick red line indicates video game sales in North America. Similar to Figure 8, both trends rose consistently from the late 1990s, peaking before the 2008 financial crisis. However, video game sales did not recover alongside GDP, likely due to businesses avoiding risks in the still recovering economy.

<img width="718" alt="image" src="https://github.com/user-attachments/assets/d1e72acc-2b82-49b4-8f8b-2c644ebf548c" />

In Figure 10, the thick black line represents Japan's average GDP, while the thick red line indicates video game sales in Japan. The chart shows that Japan's GDP experienced fluctuations, but the impact of the 2008 financial crisis was smaller compared to the European and North America regions. This is likely due to Japan’s “lost decade”, where it faced many financial crises. Additionally, the correlation between video game sales and GDP in Japan appears weak, as video game sales remained relatively stable throughout the period. This stability highlights Japan's prominent and consistent role in the global video game industry.

<img width="705" alt="image" src="https://github.com/user-attachments/assets/6f47e804-f6b5-47e4-a772-dec7d9b2897b" />

In Figure 11, we set the average of the Steam reviews for a game on the X axis and we set the IGN score given to the game on the y axis. We allow the color of the game to be its ESRB rating and let the size of each of the bots be the global sales in millions for the point. We notice the intuitive trend that, as the scores increase, the number of sales increases as a highly acclaimed game is more likely to sell more copies. One interesting trend we see here is the high variance of Steam reviews even among high selling games. For example, Call of Duty5 has about 60% Steam rating but still has sold on the high end of the games in the set. On the contrary, it appears that IGN rating is still able to capture many games with high sales. However, we should notice that, once a game rises above a 7.5 IGN rating, a higher score than that does not guarantee higher sales. To the contrary, there are some games with quite a high score which did not sell many copies. This shows that a higher IGN score (above 7.5) might be a necessary condition to sell well but increasing past that threshold does not strictly increase sales.

## Discussion

This analysis highlights the dynamic evolution of the video game industry. It demonstrates how market preferences, regional trends, and economic factors interact to shape sales outcomes. The findings suggest that tailoring strategies to regional preferences and leveraging top-performing game genres and platforms are crucial for driving market success. Additionally, the analysis of stable markets like Japan underscores their potential for sustained growth, even under economic fluctuations.

However, there are some potential sources of misinterpretation in this analysis. For example, the interpretation of game sales data by release year assumes that most sales occur in the year of release. This assumption may not hold for games with long-tail effects or updates that happen. It will potentially lead to biases when correlating GDP with game sales.

The report also faces some challenges. The dataset focuses primarily on traditional video games, potentially overlooking emerging platforms such as mobile gaming or streaming services, which limit the scope of the analysis. Additionally, while the analysis shows a correlation between GDP and sales, establishing causation would require more detailed data on consumer behavior and economic conditions.

To enhance the precision and comprehensiveness of the analysis, several improvements can be made. Incorporating time-series analysis of game sales trends across years could provide a clearer picture of long-term performance and better align with economic trends. Expanding the dataset to include data from mobile gaming platforms and new business models, such as subscription services, would also make the analysis more complete and insightful.

By addressing challenges and expanding the scope of analysis, stakeholders can better predict consumer behavior and market dynamics. That ensures ongoing innovation and competitiveness in the industry.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Conclusion

We have taken steps to identify trends among different platforms, genres, publishers, and geographic regions with respect to sales. Our investigation has let us identify several key insights for game developers and more generally those interested in the video game industry. Namely, we see that the Playstations 2 and 3, the Xbox 360, and the Wii are competitive platforms for those interested in making games, and compatibility with those systems should be considered when the cost is low. Those interested in creating games that cater to a wide audience should consider
action and sports games when brainstorming game ideas. Additionally, it may behoove aspiring developers to take some inspiration from Nintendo, Electronic Arts, and Activision, as they have been quite successful. Lastly, though Japan is a single country compared to the larger region, marketers should pay attention to the region given the role of video games in its economy. However, these results should still be contextualized in light of the fast-evolving video game industry. Recall that our data is still missing mobile game data, the burgeoning sub-industry in the broader video game landscape. Our results must be taken with the risk that such platforms and genres may drastically change when accounting for mobile games. Further investigation into mobile games will greatly reward aspiring developers.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Extended Analysis
<img width="787" alt="image" src="https://github.com/user-attachments/assets/a58c0277-8bde-46c7-b912-253a19f7f8d9" />
To further analyze the sales trends revealed in Figure 7 regarding the top 10 global video game publishers, an interactive Power BI dashboard was developed. This extended analysis focuses on the global sales performance of these leading publishers across various platforms, game genres, and regions. The dashboard allows users to dynamically filter and visualize key insights, such as Nintendo’s strong performance in platform and role-playing games, as well as regional differences in sales trends across North America, Europe, and Japan.

The dashboard provides a more detailed and interactive approach to data exploration, offering significant value for business analysis. It enables stakeholders to identify top-performing game genres in specific markets, understand regional preferences for gaming platforms, and compare publisher performance over time. These insights can support strategic decisions related to product release planning, marketing resource allocation, and identifying high-potential or underserved market segments.

With real-time filtering and multi-dimensional comparison features, the dashboard serves as a powerful tool for scenario planning and trend forecasting. By transforming static data into interactive visualizations, this extended analysis effectively bridges the gap between data exploration and actionable decision-making.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)

## Data_Sources
"Video Game Sales." Kaggle,
https://www.kaggle.com/datasets/gregorut/videogamesales/data.
"Video Games Rating By 'ESRB'", Kaggle,
https://www.kaggle.com/datasets/imohtn/video-games-rating-by-esrb.
"GDP per Capita (Current US$)", World Bank DataBank,
https://databank.worldbank.org/indicator/NY.GDP.PCAP.CD/1ff4a498/Popular-Indicators#
"IGN scores dataset", Kaggle,
https://www.kaggle.com/datasets/advancedforestry/ign-scores-dataset.
"Steam Trends 2023", Reddit,
https://www.reddit.com/r/gamedev/comments/x0qs4z/we_gathered_data_about_54000_games_
in_steam_and/.

[Back to Top](#Video-Game-Sales-Exploratory-Data-Analysis)
