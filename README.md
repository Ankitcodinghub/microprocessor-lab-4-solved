# microprocessor-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [Microprocessor Lab 4 Solved](https://www.ankitcodinghub.com/product/microprocessor-lab-4-requirement-description-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110220&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Microprocessor Lab 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Lab 4: Requirement Description

10/9 (21:14) update: Modified the contents of Basic and Advanced question.

● Introduction to Macro &amp; Subroutine:

○ video: https://youtu.be/XQF7c9myE1Y

○ Hackmd : https://hackmd.io/dlx_c18XSdWER4Y1gbkV2w

● Lab requirements:

● Basic (70%):

○ Description: Given two points A(x1,y1), B(x2,y2) and x1&gt;x2, y1&gt;y2, design a macro that can calculate the square of the distance between the two points: DIST x1, y1, x2, y2, F1, F2

○ Function: calculate the square of distance between the two points, the first four arguments map to the value of coordinates x1, y1, x2 and y2. F1 and F2 is the address where the answer stored.

○ Example test data:

After executing DIST 0x05, 0x07, 0x02, 0x03, 0x00 , 0x01:

Answer = (0x05 – 0x02)2 + (0x07 – 0x03)2 = 0x0019.

Put the high byte of the answer in [0x000], [0x000] = 0x00.

Put the low byte of the answer in [0x001], [0x001] = 0x19.

○ Standard of grading:

1. We will check whether you use the macros mentioned above. The name and arguments of the macro should be the same as the description.

2. The actual test data will not be same as example, make sure your code can be execute on any case

● Advanced (30%) :

○ Description: Write a subroutine named GP to calculate the sum of the first three terms of a geometric progression. You should use the loop in GP and modify program counter (PCL) instead of using goto and bra. Put the result in address 0x002.

The First term and the common ratio will be positive. The answer will be limited to 8-bits (0x00~0xFF)

○ Example:

when first term=1 and common ratio=3:

GP(3) = 1+3+9 = 13

○ Standard of grading:

1. We will check whether you use a subroutine named GP.

2. You should use rcall.

3. You should use loop.

4. The actual test data will not be same as example, make sure your code can be execute on any case

5. You should modify PCL in the loop instead of using goto and bra.

6. You cannot use goto and branch instructions which first character is B(ex. BRA,BZ,BN…).

7. You should put the result in 0x002.

● Bonus (20%):

○ Description: Write a subroutine named Hanoitower, use recursion to calculate the minimal number of moves required to solve a Tower of Hanoi puzzle in N disks, and put the result in address 0x000.

○ Tower of Hanoi: https://en.wikipedia.org/wiki/Tower_of_Hanoi

○ Example:

1. When N=2, the answer will be 3, put it in [0x000]

2. When N=3, the answer will be 7, put it in [0x000] 3. When N=4, the answer will be 15, put it in [0x000]

○ Standard of grading:

1. We will check whether you use a subroutine named Hanoitower.

2. You need to use recursion.

3. You should put the result in 0x000.

○ Hint:

1. You don’t need to show the process of moving ,only have to use recursion to calculate the minimal number of moves.

2. You can use FSRx to store the variable used in recursion.
