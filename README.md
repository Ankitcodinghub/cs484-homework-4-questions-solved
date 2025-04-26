# cs484-homework-4-questions-solved
**TO GET THIS SOLUTION VISIT:** [CS484 Homework 4 Questions Solved](https://www.ankitcodinghub.com/product/cs484-homework-4-questions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;84821&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS484 Homework 4 Questions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Questions

Q1:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Imagine we were tasked with designing a feature point which could match all of the following three pairs of images. Which real world phenomena and camera effects might cause us problems? Use the OpenCV function <em>cornerHarris </em>to investigate.

<em>RISHLibrary </em>— <em>Chase </em>— <em>LaddObservatory</em>

A1: As shown in ”Chase”, camera shake can cause problem as edges and corners get blurred when camera is shaked. Also if the object has repetitive pattern it can cause problem which is shown by RISHLibrary. LaddObservatory shows that objects shown only in one image and not in the other can also cause problem as new edges and corners arises.

Q2: In designing our feature point, what characteristics might we wish it to have? Describe the fundamental trade-off between feature point invariance and discriminative power. How should we design for this trade-off?

A2: We wish our feature point to have appearance invariance, which is invariant to brightness and illumination, and gemoetric invariance, which is invariant to translation, rotation and scale. However, focusing too much on geometric invariance may make feature point inaccurate as it can be corresponded to other points that has repeated ans similar feature. To avoid this, we should look at the neighboring pixels of the point and their derivatives. Also for the trade-off, we compare the feature point correspondence and the correspondence of point with second nearest feature so that if the feature difference between the given point and feature point or second nearest point is not very different, we reject the feature point. This way, we can avoid feature points matching to similar, but not same points.

Q3: In the Harris corner detector, what do the eigenvalues of the ‘M’ second moment matrix represent? Discuss both how they relate to image intensity and how we can interpret them geometrically.

A3: The eigen values represent slope change of the image pixel values. If the both eigenvalues are large, it means the image shows rapid change in the image pixels in two directions, one direction orthogonal to the other, meaning corner is shown in the point. If only one of the eigenvalues is large, it means the image shows rapid change in the image pixels in one direction, meaning edge is shown in the point. If both eigenvalues are small, it means no big change is shown in the pixel values, meaning that point is not in corner nor in edge.

Q4: Explain the difference between the Euclidean distance and the cosine similarity metrics between descriptors. What might their geometric interpretations reveal about when each should be used? Given a distance metric, what is a good method for feature descriptor matching and why?

A4:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Euclidean difference showns the geometric distance between two points, where cosine similarity measures the angle between two points. Therefore, cosine similarity is useful when the intensity of two points does not matter, and the angular difference is more important. It can also show how dependent the points are to each other. For feature descriptor, cosine similarity is better method as it compares data based on angular values. The data to be compared represents angular statistics for image derivativces in a certain point so that cosine similarity is better method for distance metric.
