# Data Critique & Redesign: [Los Angeles Artist Census](https://losangelesartistcensus.com/imgs/LA%20Artist%20Census%20Quick%20REPORT.jpg) 

## Part 1: Original Data Visualization

This data visualization is part of an initiative which began last year in Los Angeles. The Los Angeles Artist Census was started to gather data from artists specifically residing in LA County as a way to shed some light on aspects or conditions of artists living in LA through a quantitative perspective. The information provided in this “quick report” is aimed at highlighting points that may be used to further advocate for artists in Los Angeles. 

I was curious to see this report come out when it did because I had been following the LA Artist Census group closely for the past year. I had seen, through my own network, all of the ways the group was partnering with local arts organizations to bring more visibility to the surveys that were sent out. While the data in this report is a preliminary overview of the information that has been gathered, it serves as a resource and provides a tool for those interested in learning more about the creative economy.

<img src="./TSWD_Artist Census.png">

## Part 2

While going through the critique method the biggest thing I realized with this chart was it was hard for me to understand anything that was happening at first glance. I knew from the title of the chart that this was about income, but the number labeling and placement plus the outlines of the bar and the additional text explanation around the chart made this less intuitive. Through this method I concluded that while the information is very useful and valid, it is completely lacking in perceptibility.

To help create structure around the process I referred to the Good Charts Workbook warm up exercises from this past week. The steps included writing out what exactly the original chart was conveying to me vs. what the actual purpose was and then into writing out a couple of statements about what I think the statement should look like:

This chart is trying to show that income ranges as an artist in LA is below the median household which creates unstable financial situations. I want a visualization to represent the need for more financial resources for artists and increase in support by comparing median households to those who fall below that. There is a gap between what the majority of artists make and the county median income.

From here, I noted keywords such as “income ranges”, “comparing”, “median income”, “gap between” which directly led to my next step of brainstorming chart types. The short list I came up with was a stacked bar, a treemap or a unit map. After attempting to sketch some of these out, I landed on the stacked bar chart. I used feedback from a couple of people who have very different backgrounds and experiences with data viz so that I could understand some of my own biases or assumptions which may be embedded into my redesign. The main critique was to rework the color gradient, shifting the orientation of the stacked bar and clarifying/simplifying the labeling. There was additional feedback surrounding adding more context to where these numbers came from, unfortunately, the original data source is private so I didn’t have access to this. Detailed feedback is below the wireframe solutions.

### My final wireframe:
<br>
<img src="./TSWD Assignment_wireframe.jpg" width="500" height="250">

### Feedback

#### Can you tell me what you think this is?
  
  Sangita 
      
   - Where the median household income stands for LA based artists
  
  Sunny
      
   - An income distribution graph that shows the skew. The title clearly calls out the intended message. But the viz could be tweaked a little bit to mirror that message as suggested in the below comments.

#### Can you describe to me what this is telling you? Is there anything you find surprising or confusing?
  
  Sangita 
    
   - That lower income ranges occupy/ have more share of the population 
    
   - Curious to know differentiating factor between a 210k artist vs a 65k artist. Is it their type of work? The way they're selling their         work... etc. Maybe define that in the title (ie. Majority of LA based painters/photographers/designers, etc.)
   -  The color coding sort of throws me off. I think it would be less confusing if it were one color. With the way it's colored now, you're        calling out the fact that 210k is a lot of money and 65k isn't - but for some people 65k is significant. That's why if it was all in one color, it doesn't seem as biased 
  
  Sunny 
    
   - The rainbow color grid is confusing .Red denotes bad and should be on the extreme left. Also, what is the unit here for each bar segment? As in what does the width of the bar represent? Percentages/Population? Make that clear. Also, when was this data collected? Is this the average monthly income/ Yearly income? Someone who does not have an idea of income ranges in LA could be confused by this.

#### Who do you think is the intended audience for this?

Sangita 
  -  artists and galleries that work directly with artists, artist management/agents
  - I could see a world where a Glassdoor type of site or websites that host artist work use this as well
Sunny 
  - LA Based artists, artist communities, galleries who work with artists, etc.

#### Is there anything you would change or do differently?
  
Sangita 
  - Agree with Sunny's comment regarding stacking the chart vertically. It's easier to digest. 
  - Personally, I'd be curious to know what type of institution these artists are connected to that their main source of income is coming from. ie. are the artists that are in the 210k range at a private gallery vs. an artist on the lower end selling their art on an independent site (etsy, their own website, etc.)
 
Sunny 
  - Yes, I would put the stacked bar chart vertically, so that I can read the percentages on the left side of the stacked bar and the   income labels close to each of the bar’s edges on the right side. Stacking it vertically and having percentages to the left side would also let the user look at the viz and figure out the 76%, 46% statistics given in the text above the original viz.
  - Also, if the aim is to draw attention to values below the median, then I would color each of the bars below the median in shades of red. Red signifies bad and captures the reader’s attention. So dark red would be used for <10k and the shades of red can be made lighter as income increases. Values beyond the median could be greyed out or given a color that doesn’t grab the attention.


A preliminary sketch/experimenting with chart types: <br>
<img src="./TSWD Sketch.jpg" width="500" height="500">

## Part 3

<div class='tableauPlaceholder' id='viz1605670345710' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assgn34_SarikaSanyal2&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TSWD_Assgn34_SarikaSanyal2&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;TS&#47;TSWD_Assgn34_SarikaSanyal2&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>var divElement = document.getElementById('viz1605670345710');var vizElement = divElement.getElementsByTagName('object')[0];if ( divElement.offsetWidth > 800 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='727px';}  var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

Source: [Los Angeles Artist Census](https://losangelesartistcensus.com/imgs/LA%20Artist%20Census%20Quick%20REPORT.jpg) 
