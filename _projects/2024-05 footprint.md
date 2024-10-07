---
title: 'CustomeFootprint'
subtitle: 'Human Behavior Map'
date: 2024-05-01 00:00:00
description: Board is a stylish full-width masonry grid theme. Made for designers, artists, photographers and developers to show off their best work.
featured_image: '/images/Projects/CustomeFootprint/standing_eating.gif'
---

<!-- ![hi]({{site.baseurl}}/images/Projects/gh/gh.png/) -->

<!-- <div class="gallery" data-columns="2">
  <img src="{{site.baseurl}}/images/Projects/CustomeFootprint/eating.gif" alt="Eating">
  <img src="{{site.baseurl}}/images/Projects/CustomeFootprint/walking.gif" alt="Walking">
  <img src="{{site.baseurl}}/images/Projects/CustomeFootprint/standing_eating.gif" alt="Standing Eating">
  <img src="{{site.baseurl}}/images/Projects/CustomeFootprint/YOLO_CLIP.gif" alt="YOLO CLIP">
</div> -->

<div class="kgallery">
    <div class="kgallery__item">
        <img src="{{site.baseurl}}/images/Projects/CustomeFootprint/eating.gif" alt="Eating behavior">
        <div class="kgallery__caption">
            <p><strong>Instructor:</strong> Panagiotis Michalatos, Nicholas Cassab</p>
            <p><strong>Tools:</strong> YOLO | CLIP | PYGLET | IMGUI</p>
            <p><strong>Time:</strong> 24Spring</p>
            <br><br>
            <p>The observation of human behavior in urban public space is vital for analyzing the social dynamics of cities and retrofitting urban infrastructure. However, traditional techniques of acquiring quantitative data on outdoor area usage have some limitations. Standard computer categorization methods can only detect pedestrian’s location and relative movement based on time series analysis, whereas manual counting and labeling approaches are both time-consuming and expensive. For user convenience and cost-effective urban spatial study, we developed CustomFootprint, a user-customized toolset for spatial evaluation, which draws behavior maps by combining human detection and further activity analysis via an objection detection model with a large language model.</p>
        </div>
    </div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/method.png" alt="Walking behavior">
<div class="kgallery__caption">
    <p style="color: rgb(0, 153, 153);"><strong>Method</strong></p>
    
    <p>Based on machine learning models, we developed CustomFootprint, a toolkit that offers an intuitive interface for customizable urban area research by observing human presence and activities (Figure 1). Initially, pedestrian statistics are collected via video captured from designated site-specific angles. Each frame from the tape is used as input for further analysis. Utilizing two machine learning models, the YOLO one recognizes and tracks participants, extracting their position and other pertinent data inside the picture. Simultaneously, the CLIP model generates numerical assessments that indicate the degree of similarity between the input photos and chosen keywords. At last, the toolset combines these models and functionalities into an interface, enabling users to easily set different variables according to particular investigation goals, such as pedestrian frequency statistics and spatial distribution of various behaviors.</p>
</div>
</div>


<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/YOLO_MODEL.png" alt="Walking behavior">
<div class="kgallery__caption">
    <p><strong>YOLO (You Only Look Once)</strong></p>
    
    <p>We utilize the advanced functionalities of the model to do pedestrian detection, obtaining data such as location, frequency, and bounding boxes of individuals. Specifically, we deploy YOLO v8 released by Ultralytics – the latest generation in the YOLO family. This version implements substantial enhancements in the architecture of networks, resulting in improved precision for outcomes as well as increased processing speed. [i] Such developments are vital for understanding human dynamics inside urban contexts.</p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/CLIP_MODEL.png" alt="Walking behavior">
<div class="kgallery__caption">
    <p><strong>CLIP (Contrastive Language–Image Pre-training)</strong></p>
    
    <p>In the model, it learns to detect distinct notions in images and connects them with their sorting names. Therefore. A fundamental strength of CLIP is its high versatility, making it relevant to practically every visual classification problem. Researchers can simply input the name of the category they wish to identify, and the model delivers an assessment of its closeness to the specified goal benchmark. In our project, we used this property of the CLIP model, allowing users to tailor keywords according to their own needs, precisely for the behavioral areas they are inspecting. They then can obtain numerical values showing the degrees of correlation between video frames and keywords, permitting the quantitative measurement of behaviors at certain times and locations to study spatial usage and patterns of human activities.</p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/M_FRE.png" alt="Walking behavior">
<div class="kgallery__caption">
    <p style="color: rgb(0, 153, 153);"><strong>Measure Human Behavior and Evaluate Urban Spaces on User’s Input</strong></p><br><br>

    <p><strong>Spatial Occupancy Frequency</strong></p>
    
    <p>Employing the YOLO model, the position coordinates of humans appearing in each selected frame are acquired as data for display. The site is divided into a grid layout, and the total amount of persons within each square over the provided time is computed. Finally, the results are shown via the brightness of colors to signify varying degrees of occupancy.</p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/FRE.png" alt="Walking behavior">
<div class="kgallery__caption">
    <p>Initially, we conducted an analysis to determine the frequency at which individuals appeared inside a specific time frame (Figure7). The distribution exhibits great variation. In the waiting and dining areas of the food truck, the grid colors are notably brighter, indicating a higher frequency of people showing up in these regions compared to other parts. Conversely, the parts that are lighter in color mainly correspond to locations that act as passageways. The graphic effectively and precisely represents the distribution of individual in the chosen site within the selected video sections.</p>

</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/YOLO+CLIP.png" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Distribution of CLIP Values for Persons and Specified Keywords</strong></p>
    
    <p>Employing the YOLO model, the position coordinates of humans appearing in each selected frame are acquired as data for display. The site is divided into a grid layout, and the total amount of persons within each square over the provided time is computed. Finally, the results are shown via the brightness of colors to signify varying degrees of occupancy.</p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/eating.gif" alt="Walking behavior">
<div class="kgallery__caption">
    <p><strong>Eating Distribution</strong></p>
    
</div>
</div>
<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/walking.gif" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Walking Distribution</strong></p>
</div>
</div>
<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/standing_eating.gif" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Standing & Eating Distribution</strong></p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/REGION+CLIP.png" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Distribution of CLIP Values Across Designated Site Sections and Corresponding Keywords</strong></p>
    
    <p>Each site may intrinsically have functional zones defined during its design phase. To study if these zones genuinely attract distinct activities in reality, the site is split according to the viewing windows of the acquired video. The model determines the keyword alignment values for the related portions of the site in each frame and computes their average results. This study finally permits a comparison of behavioral features demonstrated across various locations of the region.</p>
</div>
</div>

<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/REGION_EAT.png" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Eating Distribution</strong></p>
</div>
</div>
<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/REGION_STAND.png" alt="Sitting behavior">
<div class="kgallery__caption">

    <p><strong>Standing Distribution</strong></p>
</div>
</div>
<div class="kgallery__item">
<img src="{{site.baseurl}}/images/Projects/CustomeFootprint/REGION_ST+EAT.png" alt="Walking behavior">
<div class="kgallery__caption">

    <p><strong>Standing & Eating Distribution</strong></p>
</div>
</div>

</div>

<div style="text-align: left; margin-right: 25px;">

<strong><a style="font-size: 20px">↓↓Pre↓↓</a></strong>
</div>



<iframe src="{{site.baseurl}}//images/Projects/CustomeFootprint/Kefan_508.pdf" width="100%" height="600px"></iframe>

<!-- [download]({{site.baseurl}}/images/Projects/CustomeFootprint/Kefan_0322.pdf/) -->