# React.js + Flask Movie Recommendation System

[![GPLv3 License](https://camo.githubusercontent.com/5c3e00a7238fe082f0e7d85aa27ba7a70a123baf59d195c40e05b31cebdf399a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f507974686f6e2d332e392e362d626c756576696f6c6574)](https://opensource.org/licenses/)

[![GPLv3 License](https://camo.githubusercontent.com/a8256d965b9ade271a5aa6fffecc3b4564a0ede3c8a77287b1de5310fece95da/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4672616d65776f726b2d466c61736b2d726564)](https://opensource.org/licenses/)

[![GPLv3 License](https://camo.githubusercontent.com/58875188e864891d411fd7ccff7937ff4e2cae07d1e760fc7d42ea874dfba390/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f46726f6e74656e642d52656163742d677265656e)](https://opensource.org/licenses/)

[![GPLv3 License](https://camo.githubusercontent.com/8785a2cfa54ec466fe1d65c77a0aa7495f2b9188c4c46e50588f3bd65641dcd8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4150492d544d44422d666362613033)](https://opensource.org/licenses/)

## Overview 📋

1.A movie recommendation system using React and Flask would involve using React as the front-end framework for building the user interface, and Flask as the back-end framework for handling the server-side logic and database interactions.

2.The system would use various techniques such as content-based filtering

3.It enable user to search and go through various details (like cast, genre, trailer, etc) 5000+ movies (all these details are fetched using an API by TMDB) 

4.Based on the searched movie users are recommended movie which are fetched for the python-flask backend that uses local dataset and content-based filtering algorithm for recommendation. 

5.The web-app also allows user to get top movies filtered by genre (these are also fetched using an TMDB api).

6.The web app is responsive and can be used on mobile devies.







## Authors

- [@yash717](https://www.github.com/yash717)
Yash Dubbalwar



[![YES Maintained](https://img.shields.io/badge/Bookverse-movie%20recommendation%20system-blue)](https://choosealicense.com/licenses/mit/)

[![GPLv3 License](https://img.shields.io/badge/Maintained-Yes-orange)](https://opensource.org/licenses/)





## Installation 📦

Clone or download this repository to your local machine.

1.Install all the libraries mentioned in the [requirements.txt]

```bash
  $ pip install -r requirements.txt
```
2.Then run the flask server by

```bash
  $ python app.py
```
3.Go to the movie directory and install the node modules and build the project.

```bash
  $ cd movie
  $ npm i
```
4.Go to the package.json file and change the proxy to  your flask server local port which is most likely localhost:5000

5.Then build the project by

```bash
  $ npm run build
```

6.Type the command cd .. for returning back to the main directory then type flask run.

```bash
  $ cd..
  $ flask run
```




    
# Architecture

![alt text](https://user-images.githubusercontent.com/74367889/170507933-fabe5dcc-52a0-476f-8650-c454a433bc48.png)

# Algorithm For Recommendation

The Recommendations are made by computing similarity scores for movies using consine simarity. For each movie tags are created by combining various details like genre of the movie, title, top cast, director and then they are converted to vectors using which similarity matrix is formed. Then for any searched movie the movies with the largest similarity score with it are sorted and then recommended.

#Cosine similarity

![alt text](https://user-images.githubusercontent.com/74367889/170820479-843243b2-3659-4101-8adf-2e5c7cdbcc19.png)

 
## Project Screenshots 📷

### Homepage

![alt text](https://github.com/yash717/React-Flask-Movie-Recommendation-App/blob/main/photos/search.png?raw=true)

### Search Results

![alt text](https://github.com/yash717/React-Flask-Movie-Recommendation-App/blob/main/photos/searchresult.png?raw=true)

### Top Cast

![alt text](https://github.com/yash717/React-Flask-Movie-Recommendation-App/blob/main/photos/topcast.png?raw=true)

### Recommended Movies

![alt text](https://github.com/yash717/React-Flask-Movie-Recommendation-App/blob/main/photos/recommendedmovies.png?raw=true)



