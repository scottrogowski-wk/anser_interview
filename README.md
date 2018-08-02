# anser_interview

This is the take-home problem for the software engineer role on the ANSER (Analytic Services) team here at Workiva. We're a small team but manage the analytics infrastructure for all Workiva applications. Additionally, we oversee several dozen ETL jobs and the dashboards used by teams all over Workiva to make data-driven decisions.

# The task
In this assignment, you will be analyzing historical weather data for the city of Boulder, Colorado. Here are the steps you need to complete:
1. Fork this repo to your personal github and then clone it locally
2. Download this file, NREL_Boulder_Weather.csv. Be patient, it's almost 1GB! https://data.colorado.gov/api/views/duk8-nhaq/rows.csv?accessType=DOWNLOAD
4. You have a script, "show_weather.py". Modify it to:
  a. Take the file's path as a command line argument
  b. Read in all the data
  c. Visualy display a few graphs and statistics around Boulder's weather. You have two audiences. The first is a person who is thinking about moving to Boulder and wants to know what it's like. The second is a scientist interested in how Boulder's weather has changed over the past 100 years.
5. Test your code, validate data sanity, push it, and link us to your forked repo
  
# Evaluation
We will be looking for a few things:
1. Does your code execute and provide some sort of a visual dashboard around Boulder's weather?
2. Is your code sane and readable?
3. How well are you catering to your audience?
In addition, anything that will get us to say, "wow", is encouraged

For the visual aspect, you can use any framework you are comfortable in. Matplotlib is a good standard option. If you want to use something like hipsterplot or output html and use D3, more power to you.
