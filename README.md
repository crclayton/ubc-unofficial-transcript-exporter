# UBC Unofficial Transcript Exporter

By default, the unofficial transcript you can download from the UBC student service center is quite ugly. It has some unattractive clutter at the top that forces it to spill over into the next page. It may be trivial, but when applying for jobs or graduate school, you probably want a cleaner and more professional looking transcript.

## Instructions

To export your unofficial transcript, go to your Grades Summary page here: https://ssc.adm.ubc.ca/sscportal/servlets/SRVSSCFramework?function=SessGradeRpt

Then <a href="javascript:(function()%7Bjavascript%3Avoid%20function()%7Biframe%3Ddocument.querySelector('%23iframe-main').contentWindow.document%2C%5B'%23UbcHeaderWrapper'%2C'%23UbcBottomInfoWrapper'%2C'%23UbcUtilNavWrapper'%5D.forEach(function(n)%7Bdocument.querySelector(n).remove()%7D)%2C%5B'%23calculator_title'%2C'%23calculator_title_text'%2C'.ui-tabs-nav'%5D.forEach(function(n)%7Biframe.querySelector(n).remove()%7D)%2Ciframe.querySelector('h1').style%3D'margin%3A10px%200%20-20px%2070px%3B'%2Ciframe.querySelector('%23header-invisible%20img').style%3D'margin-bottom%3A%2015px%3B'%2Ciframe.querySelector('%23tabs').style%3D'margin%3A%200px%20auto%3B%20width%3A590px'%2Ciframe.querySelector('%23printer').click()%7D()%7D)()">Drag this link to your bookmarks bar</a> and click it to run!

## Output

The code gets rid of the extra tabs/average calculator app, spaces things out a little better, and aligns the table to the header. 

![](./Comparison.png "Logo Title Text 1")

