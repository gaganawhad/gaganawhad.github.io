#### Setting ac

- passenger on heroku which has perfomed well
- using passenger picks up nginx by default
- for example you may want to set access control headrs example Access-Control-Allow-Origin, on your fonts  on your fonts because Fiefox will need to have it set. 
- since the request doesn't hit the rack layer (which includes your app) solutiosn to set headers on your static assets don't work. 
- Setting accept headers using font assets is very convenient. 
- font assets uses 
- passenger verion 4.0.39. 
- {% gist 5555251 %}0
- as ever since passenger 
- 
