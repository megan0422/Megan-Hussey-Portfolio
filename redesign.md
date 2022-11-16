## Assignment: Critique by Design

#### Choosing the visualization
For this assignment, I was tasked to first critique an existing visualization and then offer up a redesign solution. I chose to critique and redesign the following visualization from the Prison Policy Initiative on state prison populations by racial demographic. 

![Visualization to be critiqued](C:\Users\mhuss\OneDrive\Documents\Telling Stories with Data\Visualization.png)

[Source: Prison Policy Initiative](https://www.prisonpolicy.org/reports/beyondthecount.html)

I chose this visualization because I believe this tells an incredibly important story - that Black people are overrepresented in U.S. state prisons relative to their proportion of the United States population. However, I think the way the visual depicts this message is confusing and takes time for the viewer to fully grasp. 

### Critiquing the visualization
My overall critiques of this visual were that it was very difficult to comprehend at first glance and took some processing to grasp the message. The labels at the bottom of each side of the graph were especially confusing, because I didn't know right away what the dots on both sides represented.  The long title works well to remedy this, because it helps the viewer to understand the message of the visualization right away to give them purpose while deciphering it. However, with more effective uses of color and scaling, I don't believe a long title would be necessary to aid in understanding. 

### New wireframes and feedback loop
I first attempted to recreate a similar version to the original visualization, using lines instead of circles to make the categories a little bit easier to track across both the U.S. population side and the state prison population side. I also moved the titles to the top to make it easier for the reader to initially see the two separate sides. 

---------Wireframe 1 here-------------------

**User feedback on first wireframe**
I spoke to two mid-twenty graduate students (1M and 1F) who both could interpret what my sketch was trying to convey, but who both expressed confused if the two sides added up to 100% separately or individually. That planted the idea for me to try two separate pie charts, to make it clear for the viewer that while we are comparing the two population proportions by racial breakdown, they should *separately* add up to 100%, not together.

The second wireframe I drew up was thus the two separate pie charts. I found this task to be deceptively simple, but after thinking about my own struggles to make sense of the two separate population counts on the inital visual, I decided to give it a go. 

---------Wireframe 2 here---------------------

**User feedback on second wireframe**
I got feedback from 3 other classmates on the pie charts, who suggested that if I was truly trying to just tell the story that White people are disproportionately underrepresented in state prison population counts relative to their overall population total when compared to Black people and other minorities, that I should just color White vs. Black or White vs. Black and one other racial cateogry (perhaps Hispanic). This led to me to the final design.

### Final redesign
<div class='tableauPlaceholder' id='viz1668407698456' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataVizandRedesign&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='DataVizandRedesign&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Da&#47;DataVizandRedesign&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1668407698456');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  if ( divElement.offsetWidth > 800 ) 
  { vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else if ( divElement.offsetWidth > 500 ) { 
  vizElement.style.width='1000px';vizElement.style.height='827px';} 
  else { vizElement.style.width='100%';vizElement.style.height='727px';}                     
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>
