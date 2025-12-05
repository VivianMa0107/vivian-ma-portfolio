| [home page](https://vivianma0107.github.io/vivian-ma-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique and Redesign Assignment: The Cheapest Countries to Study in Europe

## Step one: The Visualization

The data visualization I chose to critique and redesign is this one: https://www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe

The map provides an overview of the average yearly costs (in UK pounds) to study in 28 different European countries. The title of the map is “The Cheapest Countries to Study in Europe”, which highlights the main message of the graph, and the data from which the graph is built further breaks down this total cost of study by tuition fees and living expenses.

I’m particularly interested in examining this data visualization because I’m an international student who has studied in two different countries over the years. I have never lived in Europe as a student, so I’m curious to learn more about the living expenses and tuition costs associated with studying there.

Here is a screenshot of the graph. On the website, viewers can hover over each country on the map to see its name and total yearly costs.

<img src="original data viz.png" width="1000"/>



## Step two: The Critique
### _Describe your overall observations about the data visualization here. What stood out to you? What did you find worked really well? What didn’t work well?_

Because the dataset contains geographical information (country names), using a map as the data visualization is appropriate for two reasons: (1) With 28 countries included, mapping the regions rather than listing them reduces the complexity of the graph, and (2) the map makes it immediately clear which regions have data collected and which do not.

Another strength of this graph lies in its simplicity and clarity. Instead of presenting a full world map, it focuses only on Europe. The color gradient from light to dark blue effectively conveys the transition from lower to higher costs, making the data visualization intuitive. The use of gray to indicate missing data is also logical, while the white background provides a strong contrast, making sure that the central elements stand out.

However, this graph also has several issues:
- The title emphasizes the “cheapest countries to study in Europe,” yet darker shading represents more expensive countries. This misalignment creates confusion at first glance, requiring viewers to click into the graph to understand that darker areas actually indicate higher costs, not lower costs.
-  While the color gradient suggests different levels of expense, it does not allow viewers to easily identify the cheapest countries, since all lower-cost regions appear in similar shades. Thus, the design only conveys relative differences in expenses but fails to highlight rankings, which should be the central message of the graph. A clearer legend with distinct color bands for expense levels would improve viewers’ immediate comprehension.
-   Although maps can highlight areas where data/information is missing, in this case, the gray regions add little value to viewers’ understanding and may be perceived as unnecessary.

### _Who is the primary audience for this tool? Do you think this visualization is effective for reaching that audience? Why or why not?_

I found this data visualization on Finder, a UK-based personal finance and investing company, so the intended audience of this graph is likely its clients or potential clients, specifically younger generations who are interested in studying or living in other European countries. Since I assume this group generally has a basic familiarity with data visualization, the graph is fairly easy to comprehend, particularly for those interested in quickly identifying regions with higher or lower costs. Despite some design issues that reduce its intuitiveness, the visualization remains easy to interpret due to its simplicity and interactive features. Users can hover over a country to see its name and total costs, which helps clarify the graph. However, the graph is less effective for viewers seeking to identify the countries with the lowest cost. To do so, they must manually click through each country’s data and compare on their own, rather than seeing the ranking presented directly on the graph.

### _Based on your critique, what do you think you’ll try to focus on in your redesign? Any ideas or inspiration for how you can make a better data visualization? What are you excited to try next?_

For my redesign, I want to prioritize conveying the central message: helping viewers easily identify the European countries with the lowest costs for studying and living. To achieve this, I want to emphasize country rankings, since a map is not particularly effective for that purpose. I also noted that the original dataset breaks total costs into tuition fees and living expenses, which is information missing from the current visualization. Including this breakdown would add valuable context, as audiences are likely to be curious about how the totals are calculated. Finally, I am not concerned with displaying countries where data is unavailable because they are not necessary to understanding the graph.

With these three goals in mind, I decided to use a stacked bar chart. While the inclusion of 28 countries will make the chart lengthy, I believe this is acceptable as long as the design remains intuitive and the rankings are clear. I considered using distinct colors to highlight the top 10 cheapest countries, but I suspect this may be unnecessary because ranking by bar length alone should allow viewers to quickly distinguish the least expensive options.



## Step three: Sketch a Solution

Taking my critique and brainstorm into consideration, I drafted the following graph as my redesigned visualization. I intentionally sorted the countries from cheapest to most expensive so that viewers can immediately identify the most affordable destinations for study. For the cost breakdown, I selected two distinct yet visually balanced colors, mint green and orange, that are easy on the eyes without being overly vibrant. A legend placed on the side is used to clarify the categories of cost represented in the breakdown of total costs. 

<img src="redesign draft.jpeg" width="1000"/>



## Step four: Test the Solution

Without providing background on the original graphic or its sources, I asked two peers for feedback on my redesign draft. Below is a summary of their responses.

The first peer is a student in the MAM program. She interpreted the graphic as one that targets students who are interested in studying in Europe. She found my redesign easy to understand, though she was surprised to see Malta ranked with such high combined costs. She also questioned the absence of Switzerland, which she expected to be costly based on her prior knowledge. For improvements, she suggested ensuring consistent scaling and bar lengths for clarity, and recommended including an alternative currency unit since she found it difficult to interpret costs in pounds.

The second peer is a student in the MSPPM program. She believed the primary audience would be students outside Europe, such as those from North America or Asia, who are considering studying there. She was struck by the fact that European countries are generally cheaper than the United States, while Sweden and Denmark appeared unexpectedly expensive. She was really interested in seeing the breakdown of total costs, particularly tuition fees by country. Her main suggestion was to make the visualization more interactive, allowing viewers to hover over bars to see exact breakdown values. She also questioned whether the data specifically reflected higher education costs, noting that a clearer title would provide more context.

Each of my peers have different interests when viewing the chart: one paid attention to country-specific costs and missing data, and the other on the breakdown of expenses. The MAM student’s comments made me realize that missing values, such as Switzerland, may be more important to some viewers than I initially assumed. The MSPPM student’s feedback highlighted the need to use Tableau for my final redesign, since its interactive features would enhance the clarity and usability of this draft. Her question about whether the data reflects higher education costs also underscored the need to revise the title to provide more precise context.



## Step five:  Build the Solution

Based on the feedback I received, here are the changes I plan to make to my redesign draft:
- I will still exclude missing values from the graph, since the central message should remain focused on the cheapest countries for which data is available. But, I can add a note at the bottom of the graph clarifying that not all European countries are represented.
- I will retain the use of pounds as the currency unit, as the source website indicates that the primary audience for the graph is British, who are already familiar with pounds.
- I will revise the graphic’s title to specify that the figures represent the total costs of higher education (university) in Europe.
- I will use Tableau to produce the final redesign so that there will be more accurate bar scaling and interactive features that allow viewers to engage directly with the data.


<div class='tableauPlaceholder' id='viz1763052347132' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt='The Cheapest Countries in Europe to Pursue Higher Education ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignAssignment&#47;Sheet1&#47;1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='CritiqueandRedesignAssignment&#47;Sheet1' />
    <param name='tabs' value='no' /><param name='toolbar' value='yes' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CritiqueandRedesignAssignment&#47;Sheet1&#47;1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
    <param name='filter' value='publish=yes' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('viz1763052347132');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width='100%';
  vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>



## References

Boyle, Matthew. “The Cheapest Countries to Study in Europe.” Finder UK, 11 July 2024, www.finder.com/uk/current-accounts/student-bank-accounts/cheapest-countries-to-study-europe. 



## AI Acknowledgements

I used Grammarly to check my spelling and grammar for the write-up, and I used Microsoft Copilot to guide me through creating the stacked bar graph with my dataset in Tableau. 

