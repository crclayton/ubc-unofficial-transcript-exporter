# UBC Unofficial Transcript Exporter

By default, the unofficial transcript you can download from the UBC student service center is quite ugly. It has some unattractive clutter at the top that forces it to spill over into the next page. It may be trivial, but when applying for jobs or graduate school, you probably want a cleaner and more professional looking transcript.

This JavaScript code/bookmarklet gets rid of the extra clutter, spaces things out a little better, and center-aligns the table to width. 

To export your unofficial transcript, go to your Grades Summary page here: https://ssc.adm.ubc.ca/sscportal/servlets/SRVSSCFramework?function=SessGradeRpt

Then [Drag this link to your bookmarks][1] and click it to run.

[1]: javascript:void%20function(){iframe=document.querySelector(%22%23iframe-main%22).contentWindow.document,[%22%23UbcHeaderWrapper%22,%22%23UbcBottomInfoWrapper%22,%22%23UbcUtilNavWrapper%22].forEach(function(e){document.querySelector(e).remove()}),[%22%23calculator_title%22,%22%23calculator_title_text%22,%22.ui-tabs-nav%22].forEach(function(e){iframe.querySelector(e).remove()}),iframe.querySelector(%22h1%22).style=%22margin:10px%200%20-20px%2070px;%22,iframe.querySelector(%22%23header-invisible%20img%22).style=%22margin-bottom:%2015px;%22,iframe.querySelector(%22%23tabs%22).style=%22margin:%200px%20auto;%20width:590px%22,iframe.querySelector(%22%23printer%22).click()}();