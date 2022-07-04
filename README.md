# kong-api
I was trying out this kong API but there are two main modes of configruing theis gate way, 
    1> using the postgre data base to store the API gateway configrutation
    2> Using the kong.yml file to store the API gateway configrutation. 
    
  My bad I was not able to configure the kong with DATABASE, but insider I have configured the kong with the database less configuration. 
  
  the file are uploaded.
  
  what is does!
      Kong api gate was acts as a middel ware for the API call, I had two routes configured in this code which I have uploaded, 
        1> http://localhost:8000/about 
        When you hit this url then the kong api will fetch the data from some othere (https://python-web-balakuberox-dev.apps.sandbox-m2.ll9k.p1.openshiftapps.com/) api         url that I have configured inside kong.yml file
        
        2> http://localhost:8000/git-api
        When you hit this url this will redirect you to the api which is avaiabel in git hub (https://api.github.com)
        
        
