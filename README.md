## Social Advertisement Effect
Web Application for comparing stocks, twitter mentions, TV mentions.

##### Currently Hosted on: https://95.211.109.210/statsChart/default/index

##### The Web Application is made using Web2py framework

####Working:
##### Backend:
- The backend has three normal python script which retrieve stock prices from google finance,
  Twitter Mentions from twitter Api, TV Mentions from CCExtractor database.
  https://github.com/Akirato/statsChart-backend
- This data is then passed through a sentiment Analysis Tool for getting the opinion in the
  sentence. Positive or Negative.
- This output is stored in a MySQL database.

##### Frontend:
- The frontend is made using simple BootStrap.
- Python module Pygal has been used for plotting graphs.

  
