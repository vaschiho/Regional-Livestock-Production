# Regional Livestock Production Analysis in Africa

## Overview
This project explores and analyzes the trends of livestock production across different regions in Africa, focusing on key livestock products like meat, eggs, hides, milk, and fat. Using data sourced from the **Food and Agriculture Organization (FAO)**, the analysis aims to uncover insights into regional variations, production patterns, and potential areas of growth.

The dataset used is restricted to African regions, and various statistical analyses, including **hypothesis testing** and **confidence intervals**, are applied to evaluate the significance of differences between regions.

## Project Goals
The main objective of this project is to:
- Identify **regional differences** in livestock production within Africa.
- Explore the production levels of key livestock products such as meat, eggs, hides, milk, and fat.
- Perform **statistical analysis** to determine if certain regions dominate in livestock production.
- Visualize the data in a way that highlights key trends and findings.

## Data and Columns Used
| Column  | Description                                      |
|---------|--------------------------------------------------|
| **Year**    | The year of livestock production data.(1961- 2022)            |
| **Region**  | The African region (West Africa, East Africa, etc.).|
| **Item**    | The type of livestock product (meat, eggs, milk, etc.). |
| **Value**   | The quantity of production (in tons).          |
| **Area**    | Specific country or sub-region within Africa.  |

## Technologies Used
- **Python**: For data cleaning, visualization, and analysis.
- **Pandas**: For data manipulation and analysis.
- **Seaborn & Matplotlib**: For visualizing production trends.
- **Tableau**: For productive visualization
- **FAO Dataset**: The main data source used for this project.
  
## Methodology
- **Data Collection**: The data was obtained from the FAO Livestock Production Dataset, focusing on African regions.
- **Data Cleaning**: Missing values and inconsistencies were addressed through data imputation and outlier handling.
- **Exploratory Data Analysis (EDA)**: Visualizations were created to examine regional distribution and trends in production across livestock categories.
- **Statistical Testing**: Hypothesis testing was performed to evaluate differences in production between regions.

## Key Insights
### Livestock Proportion in Africa (2022)

In recent years, Africa has experienced a modest increase in livestock production. In 2022, production grew by 1.1% compared to the previous year. Meat production remained the leading livestock product, reaching 704 million tonnes. This was followed by fat production at 348 million tonnes, hides at 305 million tonnes, and milk at 255 million tonnes. Egg production, though smaller in scale, amounted to 569 thousand tonnes. These figures highlight the steady growth of the livestock sector in Africa, with meat production dominating the market.

![Livestock Production by Category](./image/category_p.png)

## Regional Distribution of Livestock Products

In 2022, there was a minor decrease in egg production compared to the previous year, with a drop of 2.86%. West Africa emerged as the major producer, contributing 39.9% of Africa's total egg production, followed by North Africa (38.22%). Central Africa and Southern Africa were the least contributors, accounting for 21.85% combined.

East Africa also demonstrated strong production in cattle-related products such as meat, hides, and milk. Meat production, a key livestock product in Africa, reached 704M tons (43.62%) in 2022. East Africa led with 31.1% of total meat production, followed by North Africa and West Africa, which together made up 51.76%. Southern Africa and Central Africa had lower outputs, contributing 4.24%.

Hides, another significant livestock product, saw a 1.57% increase in production compared to the previous year. Eastern, West, and North Africa were the top producers, accounting for 83.34% of total hide production, while Central Africa and Southern Africa produced 13.20% and 3.34%, respectively.

In terms of fat production, 346M tons were produced in 2022, with Eastern Africa leading the way at 31.3%, followed by West Africa and North Africa, contributing a combined 51.59%. Southern Africa had the lowest production at 4.13%.

Milk production represented 15.82% of Africa’s total livestock output in 2022. East Africa and North Africa were the major contributors, producing 69.32% combined, followed by West Africa (26.9%) and Central Africa (3.11%).

![Regional Distribution](./image/region.png)


## Meat Production

The top producers of meat in 2022 were **West Africa** and **North Africa**, with **goat** and **sheep** meat leading production. **Central** and **Southern Africa** had relatively low meat production compared to these regions.

#### Meat production is divided into two categories:
1. **Pure meat** from livestock animals.
2. **Edible offal**, which refers to the internal organs of butchered animals, also known as organ meats.

![Meat Production](./image/meat.png)

**Sheep meat**, **goat meat**, **cattle meat**, and **pig meat** have been the major contributors to meat production, making up **97.55%** of the total meat market. Over the years, sheep meat was the leading meat product, but it experienced a steady decline of about **1.1%** since 2020. In contrast, goat meat saw steady growth, topping the meat production chart in 2022 with **133 million tonnes**, followed by cattle meat at **42 million tonnes** and pig meat at **41 million tonnes**.

### Edible Offal vs Pure Meat

Both **pure meat** and **edible offal** have shown similar production patterns, contributing significantly to the livestock sector in Africa.

![Meat and Offal Production](./image/meat_offal.png)

### Top Meat Producers in Africa

In 2022, **Nigeria** was the highest producer of meat, accounting for around **17%** of Africa's total production. Other major producers included **Ethiopia** and **Sudan** (9% each), **Chad** (5%), and **Malawi** (6%).

![Top Meat Producers](./image/top_meat.png)

## Fat Production

**Sheep fat**, **goat fat**, **cattle fat**, **pig fat**, **buffalo fat**, and **camel fat** are the major fat products in Africa. Fat accounted for the second-largest livestock product category in Africa in 2022, with about **346 million tonnes** produced. **Goat fat** led the production with **133 million tonnes**, followed by **sheep fat** at **129 million tonnes**. **Cattle fat** production reached **42 million tonnes**, and **pig fat** contributed **41 million tonnes**. **Camel fat** accounted for **1 million tonnes**, while **buffalo fat** produced **598,000 tonnes**.

![Fat Trends](./image/fat_trends.png)

### Top Fat Producers in Africa

As with meat production, **Nigeria** was the leading producer of fat in 2022, accounting for **17%** of Africa's fat production. Other key producers were **Ethiopia** and **Sudan** (9% each), **Chad** (8%), and **Malawi** (6%).

![Top Fat Producers](./image/top_fat.png)

## Hides Production

Hides production in Africa has grown steadily over the years but faced a decline in 2022, with approximately **305 million tonnes** produced. The four major sources of hides in Africa are **lamb hides**, **goat hides**, **cattle hides**, and **buffalo hides**.

![Hides Production Trend](./image/hides_trend.png)

### Top Hides Producers in Africa

In 2022, **Nigeria** was the leading producer of hides, contributing **50 million tonnes**, which accounted for **16%** of Africa's total production. Other significant producers included **Sudan** with **32 million tonnes** (**11%**), **Ethiopia** with **31 million tonnes** (**10%**), **Chad** producing **29 million tonnes** (**10%**), and **Algeria** with **21 million tonnes** (**7%**).

![Top Hides Producers](./image/top_hides.png)

## Milk Production

Milk production has significantly contributed to livestock production in Africa. However, 2022 saw a slight decline of **0.5%** compared to the previous year, with around **255 million tonnes** produced. The primary sources of milk include **goat milk**, **sheep milk**, **cattle milk**, **camel milk**, and **buffalo milk**. Goat and sheep milk followed similar production trends over the years, accounting for **90 million tonnes** and **88 million tonnes**, respectively, contributing **70.35%** of total milk production. **Cattle milk** contributed **67 million tonnes** (**26.35%**), **camel milk** produced **7 million tonnes** (**2.87%**), and **buffalo milk** accounted for **732 thousand tonnes** (**0.29%**).

![Milk Production Trend](./image/milk_trend.png)

### Top Milk Producers in Africa

In 2022, **Sudan** was the leading milk producer, accounting for **20%** of Africa's total production. Other top producers included **Mali** with **15%**, **Algeria** at **9%**, **South Sudan** with **8%**, and **Somalia** contributing **6%**.

![Top Milk Producers](./image/top_milk.png)

## Egg Production

Egg production contributed **0.04%** to the livestock market in 2022, with **569 thousand tonnes** produced. Egg production consists of two main types: **hen eggs** and **bird eggs**. **Hen eggs** have been the major source of egg production over the years. Despite a decline in 2019, hen egg production saw a positive increase of **1.9%** in 2022 compared to 2021, accounting for **94.7%** (539 thousand tonnes) of total egg production. **Bird eggs** made up **5.3%** (30 thousand tonnes) and have shown steady growth since 2020.

![Egg Production Trend](./image/egg_trend.png)

### Top Egg Producers in Africa

In 2022, **Nigeria** emerged as the leading producer of eggs, contributing **20%** of Africa's total egg production. Other significant producers included **Angola** and **South Africa**, each accounting for **7%** of production, followed by **Egypt** at **6%** and **Tanzania** with **5%**.

![Top Milk Producers](./image/top_eeg.png)

## Statistical Analysis
I carried out statistical tests, such as the **chi-square test**, to compare the regional distribution of livestock production. For regions like West Africa and East Africa, **z-tests** were applied to compare proportions of specific livestock products.


## Global Contribution of Livestock to GDP

Globally, the livestock sector, including meat, milk, hides, egg and fat production, plays a significant role in agriculture and contributes greatly to many countries' GDP. In Africa, the livestock sector is particularly important for rural livelihoods, food security, and nutrition. It contributes significantly to national economies, especially in countries like **Nigeria**, **Ethiopia**, and **Sudan**, where livestock production is a major agricultural activity.

According to the **Food and Agriculture Organization (FAO)**, livestock production in Africa makes up a substantial part of the agricultural GDP, contributing between **10-15%** of the continent's total GDP, depending on the country. The sector also provides employment and supports over **350 million** people across the continent, many of whom rely on livestock for their livelihoods.

---

This analysis highlights not only the importance of livestock production within Africa but also its critical role in the global agricultural sector. By understanding regional production trends, stakeholders can make informed decisions to improve production efficiency, boost exports, and enhance food security across the continent.

## Conclusion
This analysis offers valuable insights into livestock production across Africa, highlighting the role of different regions in producing key livestock products like meat, eggs, and hides. It also identified growth patterns and significant regional differences in production, which can inform future agricultural policies and investments. Understanding these trends helps provide a foundation for improving livestock management, food security, and economic stability in Africa.



