# IMDB
 Restful API to Search ,Edit ,Insert and Delete Movie Data.
 Implemented using Python Flask and MongoDb
 
 
 # Authorization
 
  Used Json Web Tokens to authorize the user
 
 
 
 # Authentication 
 
 Used HTTPBasicAuth for  user Authanticaion
 
 
 # Requirements
   Python 3.6
   Flask
   MongoDB

# Create virtual environment and activate it
  virtualenv -p python3 env

  source env/bin/activate
  pip install -r requirements.txt
  
# Run The Server
  python main.py
  
# API

 User with admin credentials can Add Delete and Edit movies 
 
 Add movies 
 http://13.233.230.164:5001/add_data
 
 Delete Movies 
 http://13.233.230.164:5001/delete
 
 Edit Movies 
 http://13.233.230.164:5001/edit
 
 Homepage
 Implemented Pagination logic to display movies 
 http://13.233.230.164:5001/home?limit=10&offset=10
 
 Search movies with name 
 http://13.233.230.164:5001/search_by_name
 
 Search movies with genre
 http://13.233.230.164:5001/search_by_genre
 
# Deployment 
 
 Application is dockerized and deployed in Aws
 

