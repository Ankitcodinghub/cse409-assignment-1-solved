# cse409-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE409 Assignment 1 Solved](https://www.ankitcodinghub.com/product/coding-assignment-cse-409-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114646&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE409 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Create a folder with your student id, ex. 1705xxx.

2. Put the source files, an input file and three corresponding output images in the folder.

3. Zip the folder and upload it on Moodle at the appropriate assignment submission link.

Allowed Programming Language: Any. For c/cpp you can use bitmap header file shared with you for CSE 410 Offline 2. But in case of other languages, you need to find and use the appropriate bitmap image generation library.

Tasks:

Given the two end points of some lines, you have to draw them using the basic Midpoint Line

Algorithm, using Unweighted Area Sampling Antialiasing technique and using Weighted Area Sampling Antialiasing technique. You can assume that the background color is white and the color of the lines is black.

For the Unweighted Area Sampling technique, use the overlapping box count approach to approximate the overlap in area.

In the Weighted Area Sampling technique, make sure that the intensity of a pixel varies based on the distance between its center and the center of a line. In this regard, you can experiment with different functions and use any one that shows this property.

Note that, your program should be able to handle lines with any slope. You can exchange the start and end points and use the idea of reflection wrt different lines (e.g. x-axis, y-axis, y=x line etc.) as appropriate. You do not need to handle colors, drawing grayscale images will suffice.

2. Apply Anti-Aliasing using

Input Format:

Read inputs from a file titled “input.txt”. The first line of the input file will contain two integers W, H indicating the dimension of the bitmap images to be generated. The next line will contain an integer N denoting the number of lines to be drawn. Each of the next N lines will contain four integers denoting the (xstart, ystart), (xend, yend) points of each line. Limits:

• 0 &lt;= N &lt;= 25

• 1 &lt;= W &lt;= 800; 1 &lt;= H &lt;= 600

• For any x, y: 0 &lt;= x &lt; W, 1 &lt;= y &lt; H.

Sample Input:

200 300 // image dimension will have 200 pixel width, 300 pixel height

1 // Only 1 line is to be drawn

4 5 150 200 // Two end points of the line are (4, 5), (150, 200)

If you choose to do the bonus task, after the coordinates of each line, add an additional line denoting its color. For example,

4 5 150 200

255 0 0 // the line has red color

Output Format:

Generate three bmp images “1_R.bmp”, “2_RUA.bmp”, and “3_RWA.bmp”. The bottom left pixel of each image maps to (0, 0) coordinate and the top right pixel maps to (W-1, H-1) coordinate. So, the whole image should capture a part of the first quadrant only, which conforms to the constraint specified in the Input Format.

Sample Output: Not available, sorry. But you can see some visible differences while you implement the techniques.

Sum of (Best 3 of (CT-1, CT-2, Best 2 of (CT-3, CT-4, Coding Assignment)))

Anything you get over 20 in the assignment will be distributed to CT-3 and/or CT-4 as appropriate.
