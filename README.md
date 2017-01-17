# dsipy -- Twitter User Gender Classification<
Code Repository for Data Science Intensive Course of Springboard
<div class=WordSection1>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><b><span style='font-family:"Arial",sans-serif;color:black'>Twitter
User Gender Classification</span></b><span style='font-family:"Arial",sans-serif;
color:black'>. Found dataset from Kaggle. The dataset was used to train a
CrowdFlower AI gender predictor. The prediction task is to view a Twitter
profile and judge whether the user was a male, a female or a brand. The dataset
contains rows, each with a username, a random tweet, account profile and image,
location, and link and sidebar color.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<table class=MsoNormalTable border=0 cellspacing=0 cellpadding=0
 style='border-collapse:collapse'>
 <tr>
  <td valign=top style='border:solid black 1.0pt;background:#DDEEFF;padding:
  5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'>Dataset Character: &nbsp;</span></b></p>
  </td>
  <td valign=top style='border:solid black 1.0pt;border-left:none;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>Multivariate</span></p>
  </td>
  <td valign=top style='border:solid black 1.0pt;border-left:none;background:
  #DDEEFF;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'># of Records:</span></b></p>
  </td>
  <td valign=top style='border:solid black 1.0pt;border-left:none;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>20050</span></p>
  </td>
  <td valign=top style='border:solid black 1.0pt;border-left:none;background:
  #DDEEFF;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'>Area:</span></b></p>
  </td>
  <td valign=top style='border:solid black 1.0pt;border-left:none;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>Business</span></p>
  </td>
 </tr>
 <tr>
  <td valign=top style='border:solid black 1.0pt;border-top:none;background:
  #DDEEFF;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'>Attribute:</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid black 1.0pt;
  border-right:solid black 1.0pt;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>Real</span></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid black 1.0pt;
  border-right:solid black 1.0pt;background:#DDEEFF;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'># of Variables:</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid black 1.0pt;
  border-right:solid black 1.0pt;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>26</span></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid black 1.0pt;
  border-right:solid black 1.0pt;background:#DDEEFF;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><b><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654;background:#DDEEFF'>Source:</span></b></p>
  </td>
  <td valign=top style='border-top:none;border-left:none;border-bottom:solid black 1.0pt;
  border-right:solid black 1.0pt;padding:5.25pt 5.25pt 5.25pt 5.25pt'>
  <p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
  normal'><span style='font-size:10.0pt;font-family:"Arial",sans-serif;
  color:#123654'>CrowdFlower</span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>Source URL: </span><span
style='font-size:12.0pt;font-family:"Times New Roman",serif'><a
href="https://www.kaggle.com/crowdflower/twitter-user-gender-classification"><span
style='font-size:11.0pt;font-family:"Arial",sans-serif;color:#1155CC'>https://www.kaggle.com/crowdflower/twitter-user-gender-classification</span></a></span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><i><span style='font-family:"Arial",sans-serif;color:black'>Target
Audience: </span></i></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>marketing
department responsible for twitter promotion for a certain brand</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><i><span style='font-family:"Arial",sans-serif;color:black'>Is gender
true label available?</span></i><span style='font-family:"Arial",sans-serif;
color:black'> </span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>There is a
gender confidence column next to gender column, which show a probability ( 0 to
1) of how confidence &nbsp;those labels were correctly marked.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><i><span style='font-family:"Arial",sans-serif;color:black'>Analytical
needs: gain understanding of profile of twitter users and help develop
marketing message for this brand. What is the value of having this prediction
for the marketing department?</span></i></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>Marketing
department can seamlessly promote certain products or services on twitter
according to twitter user’s gender and profile </span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>From the
source of the dataset, crowdflower, t</span><span style='font-size:10.5pt;
font-family:"Arial",sans-serif;color:black;background:white'>hey achieved about
60% accuracy on their three-way (male, female, brand/organization)
classification task. In my initial effort, utilizing Naive Bayes Model and just
considering tweets for female-male gender relationship (without using other
variables such as sidebar color), I achieved about 57% accuracy.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:10.5pt;font-family:"Arial",sans-serif;
color:black;background:white'>There were some earlier such studies, where:
“researchers Burger, Henderson, Kim, and Zarrella 2011, that measured 184,000
“authors,” or Twitter users, which was able to obtain 75.5 percent accuracy for
identifying the gender of the speaker, granted that their algorithm had
multiple tweets per author to work with. 67.8 accuracy was obtained from single
messages per author. Bamman, Einsentein, and Schnoebelen, were able to best
these results, arriving at an impressive 88.8 percent accuracy.”</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:10.5pt;font-family:"Arial",sans-serif;
color:black;background:white'>For my project, I hope to achieve the 67.8%
accuracy based on single message per user.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>I also ike to
follow a book called ‘<i>Mastering Social Media Mining with Python</i>’ by
Macro Bonzanini when working on this project. In this book, the author
describes the process for building a social media mining application as the
following steps:</span></p>

<ol style='margin-top:0in' start=1 type=1>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Authentication
     (Tweeter or Facebook API, etc)</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Data
     Collection</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Data
     Cleaning and pre-processing</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Modeling
     and analysis</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Result
     presentation</span></li>
</ol>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>In this
project, I would like to focus on steps 3, 4, 5 by the using the dataset listed
above, if time permits, then I may do the Data Collection step directly via
twitter.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>I think the
key components of this project for me would be Natural Language Processing
(NLP), text preprocessing, word tokenization, word normalization, stemming,
lemmatization, stop word removal, the exercises on the text modeling of Naive
Bayes, and Support Vector Machines by reducing the reduce the rates of false
positives and false negatives.</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>With this
project, I hope to accomplish:</span></p>

<ol style='margin-top:0in' start=1 type=1>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Take
     my python programming skill to a level where I am comfortable and
     confident working for my future employers.</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Be
     able to fluently extract useful knowledge from the Social media data.</span></li>
 <li class=MsoNormal style='color:black;margin-bottom:0in;margin-bottom:.0001pt;
     line-height:normal;vertical-align:baseline'><span style='font-family:"Arial",sans-serif'>Communicate
     clearly of my findings to the potential stakeholders.</span></li>
</ol>

<p class=MsoNormal style='margin-bottom:12.0pt;line-height:normal'><span
style='font-size:12.0pt;font-family:"Times New Roman",serif'>&nbsp;</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-family:"Arial",sans-serif;color:black'>The initial
analysis has been posted here as of Jan 15 2017:</span></p>

<p class=MsoNormal style='margin-bottom:0in;margin-bottom:.0001pt;line-height:
normal'><span style='font-size:12.0pt;font-family:"Times New Roman",serif'><a
href="https://github.com/lin-meng/dsipy/blob/master/TweetAnalysis_RevC.ipynb"><span
style='font-size:11.0pt;font-family:"Arial",sans-serif;color:#1155CC'>https://github.com/lin-meng/dsipy/blob/master/TweetAnalysis_RevC.ipynb</span></a></span></p>

<p class=MsoNormal><span style='font-size:12.0pt;line-height:107%;font-family:
"Times New Roman",serif'><br>
<br>
</span></p>

</div>
