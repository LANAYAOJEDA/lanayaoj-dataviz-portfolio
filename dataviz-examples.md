| [home page](https://lanayaojeda.github.io/lanayaoj-dataviz-portfolio/) | [data viz examples](dataviz-examples.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one.md) | [final project II](final-project-part-two.md) | [final project III](final-project-part-three.md) |

# Data visualization examples

[Trust in News Visualization](newstrust.md)

**Map Visualization**  

For this visualization, I designed it based on how I would prefer to see the data presented. I immediately thought of using a map, where countries with higher national debt would be shown in red, and those with lower debt in green. I wanted to highlight the countries with the highest debt over time, and noticed that Greece, Japan, and Italy consistently topped the list, so I made sure to call them out in the title. Additionally, I wanted to emphasiize that even over the years, Greece, Japan, and Italy remain stuck in the high debt zone. To show this, I added a time filter, allowing users to slide through each year and track the trend in debt levels, observing how these countries debt burdens persist over time.

**Source:** OECD. *General Government Debt.* Accessed [March 22, 2025]. [OECD Data](https://www.oecd.org/en/data/indicators/general-government-debt.html)

<div class='tableauPlaceholder' id='viz1742750897495' style='position: relative'><noscript><a href='#'><img alt='Japan, Greece, and Italy Among the Most Indebted Nations: A Global Debt ComparisonSource: OECD. General Government Debt. Accessed [March 22, 2025]. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;63&#47;63PZB9F4T&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;63PZB9F4T' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;63&#47;63PZB9F4T&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1742750897495');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


**Highlight Table Visualization**  
This visualization presents the **debt burden by country** using a highlight table with an **orange-to-blue diverging color scale**. Higher debt-to-GDP ratios are represented in **deep orange**, while lower ratios appear in **dark blue**, making it easy to compare countries at a glance.  

**Source:** OECD. *General Government Debt.* Accessed [March 22, 2025]. [OECD Data](https://www.oecd.org/en/data/indicators/general-government-debt.html)


<div class='tableauPlaceholder' id='viz1742701291468' style='position: relative'><noscript><a href='#'><img alt='Debt Burden by CountrySource: OECD. General Government Debt. Accessed [March 22, 2025]. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebtBurdenByCountryOECD&#47;DebtBurdenbyCountryOECD&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DebtBurdenByCountryOECD&#47;DebtBurdenbyCountryOECD' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;DebtBurdenByCountryOECD&#47;DebtBurdenbyCountryOECD&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1742701291468');                    
  var vizElement = divElement.getElementsByTagName('object')[0];               
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                   
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
