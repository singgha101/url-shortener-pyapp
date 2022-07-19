# URL-shortener-Webapp
This is a python webapp which converts a long url into a small url like into this pattern [https://mydomain/xyz/]. Basically it stores the long url in its database and returns a smaller url you can say tiny url to the user. And whenever the user clicks into it, redirects into this webapp database and mapping is done internally and finally redirects to the actual web page initially the long url was pointing to.

# Also hosted on heroku
[https://url-shortener-pyapp.herokuapp.com/]

![Screenshot url shortenere](https://user-images.githubusercontent.com/34748568/179671821-2a42173f-5cd4-4ea5-9b36-e0199b92c8cb.png)

# How to run locally with https
For that we need a certificate and a private key. Generate them and follow below steps.
### Steps
1. Make sure the links in the "shorturl.html" are as [https://] instead of [http://] after removing from the comment
2. Comment the heroku links
3. command: flask run --cert=certificate_file__name.pem --key=key_file_name.pem




