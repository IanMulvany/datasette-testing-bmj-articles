# Learning Datasette with some sample data about BMJ publications. 

I am interested in learning about datasette - an open soruce tool for publishing and exploring data. In order to learn about the tool I've decided to see if it can be used to create an interface to explore some informaiton about papers published by the BMJ. The goal is to see if Datasette could be a useful tool for publishing and sharing data. 

In this notebook I'm going to: 

- get some data about 100 BMJ artilces using the crossref API 
- take a selection of the metadata from those articles
- install Datasette locally 
- use sqlite_utils to create a local sqlite databse 
- use datasette running locally to explore and interact with this data 
- export to CSV from my local instance 
- upload this CSV to an online instance of Datasette running on Glitch 
- configre the Glitch instance to enable full text search on some of the fields 

The final output can be seen running at  [https://watery-alder-carpenter.glitch.me/data/article](). 

Overall it went really well, and I'm excited about Datasette. 
