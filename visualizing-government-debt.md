| [home page](https://raslan2000.github.io/My-Portfolio/) | [visualizing debt](https://raslan2000.github.io/My-Portfolio/visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# General Government Debt
In this project, we examine government debt as a percentage of GDP across various nations, using data sourced from the OECD . Our objective is to depict the fiscal landscape and the impact of policies in different countries through diverse visualizations:

1. **Bar Chart**: Illustrates debt-to-GDP ratios for 2022, focusing on Japan's notably high debt relative to other countries such as Estonia and Luxembourg.
2. **Highlight Table**: Identifies countries with the highest and lowest levels of debt, making distinctions clear for the years 1995 to 2019.
3. **Area Graph**: Maps out the progression of each country's debt from 1995 to 2019, revealing long-term trends and shifts in economic policy.

This analysis is not only academically relevant but also offers valuable insights for policymakers, investors, and economists. The project involved utilizing web-based visualization tools to design and integrate these graphics into a dedicated GitHub portfolio page, in line with the strategies and techniques taught in class.

Further data analysis and visualization were conducted using Tableau, showcasing our proficiency with advanced visualization tools. This practical application has enhanced our ability to convey complex economic narratives effectively, an essential competency in the field of data science and economics.

## Part one: Working with web-based visualization tools and data

This bar chart illustrates the general government debt as a percentage of GDP for selected countries in the year 2022. Data is sourced from the Organization for Economic Co-operation and Development (OECD), providing a credible snapshot of fiscal health across these nations.
This visualization not only sheds light on the current fiscal positions but also raises questions about the economic strategies that lead to such varied debt levels, stimulating further research and discussion.
![OECD Bar Graph](OECD Bar graph.png)


## Working with Tableau

This table provides a comprehensive overview of the general government debt as a percentage of GDP from 1995 to 2006 for a selection of countries. The data, presented in a time-series format, allows us to track the trajectory of national debts over a 12-year period, highlighting trends and shifts in fiscal policy.

- **Insights and Trends**: The table shows varied patterns of debt percentages among the countries. For instance, Japan and Greece consistently exhibit high debt ratios throughout the period, reflecting their long-term fiscal challenges. Conversely, countries like Norway and Switzerland display relatively low debt levels, indicating stronger fiscal health and conservative financial management.
- **Utility of the Visualization**: By examining changes over time, policymakers and analysts can identify periods of fiscal consolidation or expansion. This data is crucial for understanding the impact of historical economic policies on current financial stability.
- **Interactive Elements**: Though not visible in the static image, in a Tableau dashboard, users would be able to interact with this data by highlighting specific years or filtering by country to examine particular patterns more closely.

This detailed view not only informs about past and present economic conditions but also serves as a foundation for predictive models concerning future governmental fiscal policies and economic outcomes.

<div class='tableauPlaceholder' id='viz1725891936822' style='position: relative'>
    <noscript>
        <a href='#'>
            <img alt='General Government Debt' src='https://public.tableau.com/static/images/Ge/GeneralGovernmentDebt_17257224254280/GeneralGovernmentDebt/1_rss.png' style='border: none' />
        </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='GeneralGovernmentDebt_17257224254280/GeneralGovernmentDebt' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https://public.tableau.com/static/images/Ge/GeneralGovernmentDebt_17257224254280/GeneralGovernmentDebt/1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
    </object>
</div>

<script type='text/javascript'>
    var divElement = document.getElementById('viz1725891936822');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Part three: create your own visualization

This visualization offers an insightful view of government debt as a percentage of GDP across several countries from 1995 to 2019. Each area chart corresponds to a different country, with the shaded area indicating debt levels at various intervals during this 24-year period.

The area chart allows for a visual tracking of debt trends within each country, providing a vivid representation of how debt evolves over time. For instance, Canada (CAN) displays a consistent reduction in debt ratios, reflecting strong debt management and sustained economic growth.

This type of graph is particularly valuable for economists and policymakers who aim to evaluate the effectiveness of fiscal policies over the long term. By revealing historical debt patterns, the area chart serves as a powerful tool for predicting future economic stability.


<div class='tableauPlaceholder' id='viz1725974843109' style='position: relative; width: 100%; height: 800px;'>
    <noscript>
      <a href='#'>
        <img alt='Country wise debt over the years' src='https://public.tableau.com/static/images/Ge/GeneralGovernmentDebt-Countrywise/Sheet1/1_rss.png' style='border: none' />
      </a>
    </noscript>
    <object class='tableauViz' style='display:none;'>
      <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
      <param name='embed_code_version' value='3' />
      <param name='site_root' value='' />
      <param name='name' value='GeneralGovernmentDebt-Countrywise/Sheet1' />
      <param name='tabs' value='no' />
      <param name='toolbar' value='yes' />
      <param name='static_image' value='https://public.tableau.com/static/images/Ge/GeneralGovernmentDebt-Countrywise/Sheet1/1.png' />
      <param name='animate_transition' value='yes' />
      <param name='display_static_image' value='yes' />
      <param name='display_spinner' value='yes' />
      <param name='display_overlay' value='yes' />
      <param name='display_count' value='yes' />
      <param name='language' value='en-US' />
    </object>
  </div>

  <script type='text/javascript'>
    var divElement = document.getElementById('viz1725974843109');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
  </script>


## Summary
In this research, we studied government debt as a proportion of GDP using OECD data and employed several visualization tools to emphasize different elements of fiscal health across nations from 1995 to 2019.

#### Bar Chart Analysis
The first visualization was a 2022 bar chart, which allowed for an instant visual comparison of debt-to-GDP ratios among nations. This strategy is straightforward, highlighting financial status differences quickly and efficiently.

#### Tabular Data Overview
The second technique displayed a table from 1995 to 2006, providing a thorough perspective of debt patterns over time. Although tables are rich in information, they require more effort to analyze than graphical representations.

#### Area Chart Development
The final visualization was an area chart covering 1995 to 2019, chosen for its ability to dynamically depict debt patterns. This technique effectively records changes over time, offering a more detailed narrative of fiscal health progression than earlier methods.

Each visualization serves a specific analytical purpose: bar charts for quick comparisons, tables for in-depth study, and area charts for tracking long-term trends. Together, these strategies form a solid foundation for successfully comprehending and discussing fiscal policy and economic realities.
