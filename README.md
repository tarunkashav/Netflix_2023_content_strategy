# Netflix_2023_content_strategy_analysis

_hello_

In this project, I’ll take you through the task of Netflix Content Strategy Analysis with Python. I have analysed how content is created, released, distributed, and consumed to achieve specific goals, such as maximizing audience engagement, viewership, brand reach, or revenue.

For this task of Netflix Content Strategy Analysis, we need data based on content titles, type (show or movie), genre, language, and release details (date, day of the week, season) to understand timing and content performance. Viewership metrics like hours viewed are also crucial for measuring audience engagement.
I have attached a .csv file of the dataset for this task in this repository, which contains data about title, release date, language, content type (show or movie), availability status, and viewership hours of the content on Netflix of all the shows and movies released in 2023.

_let_us_begin_

-1 Importing the necessary Python libraries and the dataset as csv-
-
![Image](https://github.com/user-attachments/assets/4b7e6e23-094a-4edb-8163-695354644d8b)

-2 Then I started with cleaning and preprocessing the “Hours Viewed” column to prepare it for analysis-
-
![Image](https://github.com/user-attachments/assets/6e676bc8-f11b-488f-873f-a5fafa5a74ae)

The “Hours Viewed” column has been successfully cleaned and converted to a numeric format.

-3 I analyzed the trends in content type to determine whether shows or movies dominate viewership. Then I visualized the distribution of total viewership hours between Shows and Movies-
-
![Image](https://github.com/user-attachments/assets/c83a0f67-58db-4439-89dd-ef9ec2831c35)

This visualization indicates that shows dominate the total viewership hours on Netflix in 2023 compared to movies. This suggests that Netflix’s content strategy leans heavily toward shows, as they tend to attract more watch hours overall.

-4 Next, let us analyze the distribution of viewership across different languages to understand which languages are contributing the most to Netflix’s content consumption-
-
![Image](https://github.com/user-attachments/assets/44bd5ad2-9fe6-43fe-8451-16bf61120924)

The visualization reveals that English-language content significantly dominates Netflix’s viewership, followed by other languages like Korean. It indicates that Netflix’s primary audience is consuming English content,
although non-English shows and movies also have a significant viewership share, which shows a diverse content strategy.

-5 I’ll analyze how viewership varies based on release dates to identify any trends over time, such as seasonality or patterns around specific months-
-
![Image](https://github.com/user-attachments/assets/1099d45f-c614-47b2-a966-4fb05f900f20)

This graph shows the total viewership hours by month, which reveals a notable increase in viewership during June and a sharp rise toward the end of the year in December.
It suggests that Netflix experiences spikes in audience engagement during these periods, possibly due to strategic content releases, seasonal trends, or holidays, while the middle months have a steady but lower viewership pattern.

-6 Delving deeper, we can analyze the most successful content (both shows and movies) and understand the specific characteristics, such as genre or theme, that may have contributed to high viewership-
-
![Image](https://github.com/user-attachments/assets/022a9a2d-56a5-4ebb-a400-13c13f928fb6)

Looking at the image above we can see the top 5 most-viewed titles on Netflix in 2023 are:
-The Night Agent: Season 1 (English, Show) with 812.1 million hours viewed.
-Ginny & Georgia: Season 2 (English, Show) with 665.1 million hours viewed.
-King the Land: Limited Series (Korean, Movie) with 630.2 million hours viewed.
-The Glory: Season 1 (Korean, Show) with 622.8 million hours viewed.
-ONE PIECE: Season 1 (English, Show) with 541.9 million hours viewed.

English-language shows dominate the top viewership spots. But, Korean content also has a notable presence in the top titles, which indicates its global popularity.

-7 Now, let’s take a look at the viewership trends by content type-
-
![Image](https://github.com/user-attachments/assets/cc0b74b8-4083-439a-8f96-dac7de235c0d)

This graph compares viewership trends between movies and shows throughout 2023. It shows that shows consistently have higher viewership than movies, peaking in December.
Movies have more fluctuating viewership, with notable increases in June and October. This indicates that Netflix’s audience engages more with shows across the year, while movie viewership experiences occasional spikes, possibly linked to specific releases or events.

-8 Now,  le's see the total viewership hours distributed across different release seasons-
-
![Image](https://github.com/user-attachments/assets/7308236a-9046-4627-ad01-b65cab8ca1c1)

This graph indicates that viewership hours peak significantly in the Fall season, with over 80 billion hours viewed, while Winter, Spring, and Summer each have relatively stable and similar viewership around the 20 billion mark.
This suggests that Netflix experiences the highest audience engagement during the Fall.

-9 Now we will analyze the number of content releases and their viewership hours across months-
-
![Image](https://github.com/user-attachments/assets/4d82e625-9f2c-4c6c-81c7-d76d5b882880)

While the number of releases is relatively steady throughout the year, viewership hours experience a sharp increase in June and a significant rise in December, despite a stable release count.
This indicates that viewership is not solely dependent on the number of releases but influenced by the timing and appeal of specific content during these months.

-10 Next, let’s explore whether Netflix has a preference for releasing content on specific weekdays and how this influences viewership patterns-
-
![Image](https://github.com/user-attachments/assets/c963e629-b9f0-4fa5-a579-d04f13b6a387)

This graph highlights that most content releases occur on Fridays, with viewership hours also peaking significantly on that day. This suggests that Netflix strategically releases content toward the weekend to maximize audience engagement.
The viewership drops sharply on Saturdays and Sundays, despite some releases, indicating that the audience tends to consume newly released content right at the start of the weekend, which makes Friday the most impactful day for both releases and viewership.

-11 To further understand the strategy, let’s explore specific high-impact dates, such as holidays or major events, and their correlation with content releases-
-
![Image](https://github.com/user-attachments/assets/0b511a7c-8718-4e9a-aa09-987220bb8c32)

The data here reveals that Netflix has strategically released content around key holidays and events. Some of the significant releases include:

-New Year’s Period: The Glory: Season 1, La Reina del Sur: Season 3, and Kaleidoscope: Limited Series were released close to New Year’s Day, resulting in high viewership.
-Valentine’s Day: Perfect Match: Season 1 and The Romantics: Limited Series were released on February 14th, which align with a romantic theme and capitalize on the holiday’s sentiment.

-Conclusion-
-
So, we can conclude that the content strategy of Netflix revolves around maximizing viewership through targeted release timing and content variety. Shows consistently outperform movies in viewership, with significant spikes in December and June, indicating strategic releases around these periods.
The Fall season stands out as the peak time for audience engagement. Most content is released on Fridays, which aims to capture viewers right before the weekend, and viewership aligns strongly with this release pattern.
While the number of releases is steady throughout the year, viewership varies, which suggests a focus on high-impact titles and optimal release timing over sheer volume.




















