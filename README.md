Download Link: https://assignmentchef.com/product/solved-taxapplcation
<br>
The 1040EZ is an IRS form for individuals to complete their income taxes. It is easy to complete, hence the “EZ” in the name. In addition to personal information, there are only 14 lines on the 1040EZ. The lines are shown in the Appendix A.

For your final assignment, you will create a program to allow the user to complete the 1040EZ form. You will notice that some lines on the form require the user to enter information. See lines 1, 2, 3, 7, 8, and 11. Other lines are calculations, which your program needs to perform for the user. See lines 4, 5, 6, 9, 10, 12, 13, and 14.

To complete a program for the 1040EZ you would need to know conditions, but we have not covered them in this course. Conditions will be covered in the next course. So, to make this project easier we will make a few changes to the form. Here are the changes.

<ol>

 <li>Line 5 will always be $10,150.</li>

 <li>On Line 10 it states to look up the amount on a tax table. For this project, Line 10 will be computed as the value of Line 6 multiplied by 0.15.</li>

 <li>Line 13 is completed if the user gets a refund and Line 14 is completed if the user owes money. Let’s remove Line 14 and say that if the value in Line 13 is negative, the user owes money.</li>

</ol>

All of the values (entered by the user and computed) must be stored in an array.

Below is some sample output. Review it carefully. When you see a “&gt;&gt;” it means that what is to the right of it was entered by the user. Notice that the user does not enter computed values: The program computes them and displays the results.

Sample Output 1

Welcome to the 1040EZ Tax Form Application

1 Wages, salaries, and tips. This should be shown in box 1 of your Form(s) W-2. Attach your Form(s) W-2.&gt;&gt; 100050.002 Taxable interest.&gt;&gt; 510.153 Unemployment compensation and Alaska Permanent Fund dividends.&gt;&gt; 0.004 Add lines 1, 2, and 3. This is your adjusted gross income. $100,560.155 If no one can claim you (or your spouse if a joint return), enter $10,150 if single; $20,300 if married filing jointly. See back for explanation. 10,1506 Subtract line 5 from line 4. If line 5 is larger than line 4, enter -0-. This is your taxable income. $90,410.157 Federal income tax withheld from Form(s) W-2 and 1040.&gt;&gt; 7,876.258 Earned income credit (EIC)&gt;&gt; 0.009 Add lines 7 and 8. These are your total payments and credits. $7,876.2510 Tax. Multiply Line 6 by 0.15. $13,561.5211 Health care: individual responsibility&gt;&gt; 0.0012 Add lines 10 and 11. This is your total tax. $13,561.5213Subtract line 12 from line 9. If result is positive, it is your refund.  If result is negative, it is the amount you owe.  $−5,685.27

Appendix A.

<table>

 <tbody>

  <tr>

   <td>Line #</td>

   <td>Line</td>

  </tr>

  <tr>

   <td>1</td>

   <td>Wages, salaries, and tips. This should be shown in box 1 of your Form(s) W-2.Attach your Form(s) W-2.</td>

  </tr>

  <tr>

   <td>2</td>

   <td>Taxable interest.</td>

  </tr>

  <tr>

   <td>3</td>

   <td>Unemployment compensation and Alaska Permanent Fund dividends.</td>

  </tr>

  <tr>

   <td>4</td>

   <td>Add lines 1, 2, and 3. This is your <strong>adjusted gross income.</strong></td>

  </tr>

  <tr>

   <td>5</td>

   <td>If no one can claim you (or your spouse if a joint return), enter $10,150 if <strong>single; </strong>$20,300 if <strong>married filing jointly. </strong>See back for explanation.</td>

  </tr>

  <tr>

   <td>6</td>

   <td>Subtract line 5 from line 4.</td>

  </tr>

  <tr>

   <td>7</td>

   <td>Federal income tax withheld from Form(s) W-2 and 1040.</td>

  </tr>

  <tr>

   <td>8</td>

   <td><strong>Earned income credit (EIC)</strong></td>

  </tr>

  <tr>

   <td>9</td>

   <td>Add lines 7 and 8. These are your <strong>total payments and credits.</strong></td>

  </tr>

  <tr>

   <td>10</td>

   <td>Tax. Multiply Line 6 by 0.15.</td>

  </tr>

  <tr>

   <td>11</td>

   <td>Health care: individual responsibility</td>

  </tr>

  <tr>

   <td>12</td>

   <td>Add lines 10 and 11. This is your <strong>total tax.</strong></td>

  </tr>

  <tr>

   <td>13</td>

   <td>If line 9 is larger than line 12, subtract line 12 from line 9. This is your <strong>refund.</strong></td>

  </tr>

 </tbody>

</table>