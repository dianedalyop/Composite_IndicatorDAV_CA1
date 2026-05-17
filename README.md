womens Development Index 👩 ♀️

Overview

I would be developing a coposite indicator This project develops a composite indicator called the **Women’s Development and Economic Impact Index**.

The aim of the index is to compare countries based on how women’s development, rights, opportunities, and participation may relate to economic outcomes. The index investigates whether countries where women have better access to education, employment, health, political representation, and legal rights also tend to perform better economically.


Questions I would be answering

I.  Do countries with higher female education levels show stronger economic outcomes?
II. Does women’s labour force participation relate to GDP or economic productivity?

III. Does political representation of women correlate with national development?

IV Do health, rights, and safety indicators influence women’s economic participation?


Theoritical framework 

This index is based on investigating if women have better access to opportunities, countries may benefit from:
a larger skilled workforce,
better health and education outcomes,
stronger democratic participation,
and an inclusive economic growth.

The index is divided into several sub-indices

- Education 
- Economic Participation
- Health and well-being
- Political Representation
- Legal Prghts and Protection


Data Sources

Potential data sources 

| Area | Example Indicators | Possible Source |
|---|---|---|
| Education | Female literacy rate, female school enrolment, years of schooling | World Bank / UNESCO |
| Employment | Female labour force participation, unemployment, wage gap if available | World Bank / ILO |
| Health | Maternal mortality, life expectancy, adolescent birth rate | World Bank / WHO |
| Politics | Seats held by women in parliament | World Bank / IPU |
| Rights | Women’s legal rights, gender equality laws | World Bank Women, Business and the Law |
| Economy | GDP per capita, GNI per capita, unemployment, HDI comparison | World Bank / UNDP |

Data Cleaning Steps

- Loading Datasets
- Filtering
- Standardization when needed
- Cleaning and removing Duplicate Rows
- conversion of necessary values into numerical format
- Handling missing values
- Merging indicators into a finalized dataset

Missing Data 

Possible approaches:

- Remove countries with too many missing values.
- Fill small amounts of missing data using mean or median imputation.
- Use regional averages where appropriate.
- Document all imputation decisions clearly.



Multivariate Analysis

Multivariate analysis will be used to understand the structure of the dataset.

Planned analysis includes:

- correlation matrix,
- scatter plots between women’s development indicators and economic outcomes,
- Principal Component Analysis if useful,
- checking for highly correlated variables,
- identifying variables that may be removed from the index.

Normalisation

The indicators have different units, so normalisation is required before aggregation.

Sample normalisation method 

Min-Max Normalisation:
X_normalised = (X - min(X)) / (max(X) - min(X))