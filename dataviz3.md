# Critique the data visualization

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
Her feedback:

### Second test participant:
M is a softeware engineer based in Pittsburgh
<br>
His feedback:

## Step5. build my solution

A link to the original data visualization:
I used Tableau to visualize data because Tableau allows more custimized functionalities compared to Flourish.

### Key Design Decisions


### Final Data Visualization
