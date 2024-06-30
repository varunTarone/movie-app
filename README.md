# Movie App
A React movie landing page built with OMDb API
<br>

## Tech Stack
- Vite
- React
- Node.js
- API ( movie database [OMDb API](https://www.omdbapi.com/) )
  
Hosted on [Netlify](https://moviefandom.netlify.app)
<br><br>
[![Netlify Status](https://api.netlify.com/api/v1/badges/050d3376-d62a-47e2-b005-b11ec2c3ce31/deploy-status)](https://app.netlify.com/sites/clever-puffpuff-88ef84/deploys)

# NOTE  :rotating_light:
To see the website in action, Go to Settings -> Privacy and Security -> Site settings -> Additional content settings -> Insecure content -> Allowed to show insecure content -> Add https://moviefandom.netlify.app/ (domain that contains the web page you are loading via HTTPS, not the HTTP resource).

This is because the page was loaded with HTTPS requeest whereas the OMDB api gets called with an HTTP request. This Mixed Content error causes the website to not render the movie cards.
