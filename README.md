# FFR-Calculator
### Intro
I made a calculator for FFR (Flash Flash Revolution) to find statistics for certain files and make theoretical decisions. I made this a long time ago.

**[Link to the Sheet itself](https://docs.google.com/spreadsheets/d/12sPlkAMrOT0cYreezpS99vcdxBwRyzElUTp-ss3ebFk/edit?usp=sharing)**

## How to use it

You type in the faint yellow the statistics from any play and type in any difficulty and it will calculate the results just like the game. You will receive statistics you wouldn't normally see such as the accuracy of your total raw score including osu! grade, the max grand total and raw score, the total AAA equivalency, and the total credits you would get.

<p align="center">
<img src="https://github.com/user-attachments/assets/ab00fe09-3205-49fe-a004-477145350bef" width="238" height="534" border="0"/>
</p>

In this section, you can test different values to see how much you would get to see certain ways scores could turn out.

<p align="center">
<img src="https://github.com/user-attachments/assets/210d037e-18e0-4eaa-aacb-de50797cba89"/>
</p>

### Example
The calculator can accurately give you the Grandtotal and Raw Score (with a max possible for comparison), AAA Equivalency based on the Raw Goods, and the total Credits you get.

<p align="center">
<img src="https://github.com/user-attachments/assets/bf57abd4-5e91-4f14-856d-be4d9fc900e4"/>
</p>

An extra section tells you how much raw score you would need to be at any of these ranks below an S rank using osu grades. Purely made out of curiosity.

<p align="center">
<img src="https://github.com/user-attachments/assets/0ed66d5e-aa49-47e2-9972-987cbdbb8629"/>
</p>

## How I made it

I used FFR forums and wikis for the base formulas. A lot of this was using algebra to isolate certain variables using the base formuals. Also, the osu! calculation uses the osu!mania accuracy calculation. A few calculations are within the black cells to hide extra variables I need to use.

In the diff calculator tab, you can see a method I thought of to find the answer similar to gradient descent but on Google Sheets. It narrows down the difficulty (maximum is 120) to the hundredth place. It starts from a range of 0 to 120 and picks the closest answer and then increases in resolution based on the number picked. A way I could do this better is by using my adam optimization function.



