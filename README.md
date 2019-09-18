# Speach-Analyzer
Analyze Toxicity in speach text
<p>
  <img src="sppech_analyzer.png">
</p>
This is a generic Toxicity analysis classifier for texts in English. It works great in speech and opinion kind of texts. If you are not sure of which sentiment analysis classifier to use, use this one.
<br>
This simple webapp is created using python with Flask framework. ML models were built seperatley and loaded into pickle files. Didn't use any database to store any data. But we can extend that feature if we want to store data os users and their activities. This app contains two pages

- Main Home page
  - A text area where user can enter the speach text.
- Result page
  - After prdictions, Flask renders the result page with a Pie chart and table as shown below.

<p>
    <img src="speech_result">
</p>