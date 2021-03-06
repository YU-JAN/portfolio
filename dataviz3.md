
  
# Critique Data Visualization

## Step1. find a data visualization 

I found this chart from a post in Reddit's sub-discussion board "dataisbeautiful". The data visualization is made from a paper publised in 2006, called [Trajectories and Constraints in Brain Evolution in Primates and Cetaceans](https://link.springer.com/article/10.1007%2Fs11598-006-9027-4) where the researcher was investigated the brain sizes in different species.


![Image of original](https://ppt.cc/fM5J5x@.png)
<br>
[Brain size vs. body weight of various animals (Humans are an outlier)](https://www.reddit.com/r/dataisbeautiful/comments/poq0ks/oc_brain_size_vs_body_weight_of_various_animals/?utm_source=share&utm_medium=ios_app&utm_name=iossmf)

## Step2. critique the visualization

The critique is followed byStephen Few's Data Visualization Effectiveness Profile.
<br>
Usefulness:6/10 ★★★★★★☆☆☆☆
<br>
Completeness:9/10 ★★★★★★★★★☆
<br>
Perceptibility:7/10 ★★★★★★★☆☆☆
<br>
Truthfulness:6/10 ★★★★★★☆☆☆☆
<br>
Intuitiveness:3/10 ★★★☆☆☆☆☆☆☆
<br>
Aesthetics:6/10 ★★★★★★☆☆☆☆
<br>
Engagement:9/10 ★★★★★★★★★☆
<br>
### Overall Observations

I was initially intrigued by the appealing title: brain size and brain weight because it looks like the author will also share the relationships between EQ and brain size. But it turned out the graphic did not show any relationships with EQ, making me less excited after reading through the graphic. There are a few things I noticed in this graphic:
<br>
(1) The axes are log scales: I did not notice the author used a logarithmic scale until I further looking into the dataset. This graphic somehow gave me a feeling of "most animals have a similar brain-to-body ratio", yet it's not true. I understand there are some outliers, and the log scale can better handle it, but we might need to be mindful that whether the chart will mislead readers. 
<br>
(2) The colors of dots: I am not convinced by the color palette in this graphic because I do not think purple stands for any definition of "small". Instead of color-coding dots, I might change dot size to articulate the differences.
<br>
(3) A wall of labels: While looking at this graphic, my first impression was overloaded information. Especially, I was using my smartphone to read the visualization, and I could barely see the labels. Even "Human" is colored in yellow, I was not able to spot it on my phone. My suggestion will be (a) to Increase the label size (b)Eliminate some labels and remain ones we would like to share. 
<br>


### Primary Audience?
I can't be sure who the target audiences are, but since the graphic was posted on Reddit, I assume the intended reader would be people who like data visualization. This post got 3.7k likes with 290 comments, so I believe the DataViz is quite successful in terms of catching people's eyes.

### Final Thoughts: 
I like Stephen Few's Data Visualization Effectiveness method because it gives comprehensive usability and aesthetic evaluation, I could imagine implementing this rubric into my future design critique sessions. If I were to add any other dimension for the critique evaluation, I might include "technical difficulty" and "business impact"(if it really can trigger some actions or behaviors?). Data visualization not only requires a strong design sense but also the tech capability to analyze data. On the other hand, I once heard from my friend who works at a media saying DataViz sometimes is just a deliverable that excites engineers but rarely drives business impact. Learning from her words, I think it is essential to consider business impact while making a chart.

## Step3. wireframe a solution

I intended to have my readers focus on the comparision of brain-to-body ratios among all 40 species, and I think a bubble chart might help reader to visually compare.I skethced the wireframe on Figma:
<br>
![Image of wireframe](https://ppt.cc/feQYpx@.png)

<br>

## Step4. test the solution

I tested my wireframe with two people. I created a set of questions similar to the questions on the Canvas:
- Can you tell me what you think this is?
- Can you describe to me what this is telling you?
- Is there anything you find surprising or confusing?
- Any other things you want to see in this chart?
- Who do you think is the intended audience for this?
- Is there anything you would change or do differently?
<br>


### First test participant:
J is a softeware engineer based in Taiwan
<br>
<img src="https://ppt.cc/f2Egex@.png" alt="testee1" width="701" height="517">
<br>
Her feedback:
<br>
Since J has experience making data visualization before, she double confirmed all variables on the chart first. She liked having bubble maps to articulate the brain-to-body ratio, but she also questioned the relationships between different positions of dots, which in this chart has no meaning. She also pointed out that it's important to have x and y axes in a chart because she could compare the relative brain and body weights with different species. She was curious about that whether I could add the EQ data to the chart. Her insight from the chart was that the higher brain-to-body ratio does not mean the smarter species because a ground squirrel has the highest brain-to-body ratio, yet its EQ, in common sense, is not higher than human beings.


### Second test participant:
M is a softeware engineer based in Pittsburgh
<br>
<img src="https://ppt.cc/fn0g9x@.png" alt="testee" width="701" height="517">
<br>

His feedback:
He hoped to see more animals such as dolphins, polar bears, leopards, tigers, lions, spiders, and so on. He also found out all creatures in the chart are mammals, and he suggested I should not have a title with "most species" because it's misleading. Like the first testee, he also wanted to see the relationship between the brain-to-body ratio and EQ. He believes this chart might be helpful for archaeologists and biologists. He would like to have the bubbles line up from small to big, and label every bubble, helping users identify the biggest and smallest bubbles.


## Step5. build my solution

A link to the original data visualization:
I used Tableau to visualize data because Tableau allows more custimized functionalities compared to Flourish.

### Key Design Decisions
I did not expect I could get such valuable feedback from both testees. I enjoyed the time talking with them, getting to know some blind spots I had for the chart redesign. Based on their feedback, I made four major changes:
1. *Add the x and y-axis*: Though I am not a fan of the scale to be log-based, I added them back so that readers can easily compare brain weights and body weights among different species.
2. *Change the chart header*: I modified the title to be "Higher Brain-to-body Ratio in Mammals Means Smarter?" to avoid misleading users that this chart includes all species. Also, using questions as a header enable users to critically think about the graphic, and have their explanation.
3. *Tweak the color palette*: Instead of having a yellow-to-purple color spectrum, I made it purple shades, which helps users to better compare different circles.
4. *Add one more view for brain-to-body ratio comparison*: I like both test participants' opinions, yet what they suggested are for different issues, and I did not see the point to combine two ideas, so I added one more screen to help users see the highest and lowest brain-to-body ratio.

### Final Data Visualization

View 1
<br>
[Click here](https://public.tableau.com/app/profile/yu.jan.chang/viz/assignment3_16319901230970/Sheet1)

<iframe src="https://public.tableau.com/app/profile/yu.jan.chang/viz/assignment3_16319901230970/Sheet1?:embed=yes&:tabs=yes&:toolbar=yes" width="800" height="600" allowfullscreen="true"></iframe> 

<div class='tableauPlaceholder' id='viz1631990146588' style='position: relative'><noscript><a href='#'><img alt='Higher Brain-to-body Ratio Means Smarter Species? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3_16319901230970&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='assignment3_16319901230970&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3_16319901230970&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-TW' /><param name='filter' value='publish=yes' /></object></div>            

<br>
View 2
<br>
[Click here](https://public.tableau.com/views/assignment3-2_16320739795200/Sheet2)

<div class='tableauPlaceholder' id='viz1632074282425' style='position: relative'><noscript><a href='#'><img alt='Higher Brain-to-body Ratio in Mammals Means Smarter? ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3-2_16320739795200&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='assignment3-2_16320739795200&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;as&#47;assignment3-2_16320739795200&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='zh-TW' /><param name='filter' value='publish=yes' /></object></div>     

<iframe src="https://public.tableau.com/views/assignment3-2_16320739795200/Sheet2?:embed=yes&:tabs=yes&:toolbar=yes" width="800" height="600" allowfullscreen="true"></iframe> 
