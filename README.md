# Mapchat
You have a map  
You have a chatgpt  
Boom, mapchat  

## Install
- Create map-chat-proxy/.env with params
  - OPENAI_API_KEY 
- Add Google Map API Key to URL near bottom of index.html

## Run
- Node proxy server to add Bearer token
```bash
cd map-chat-proxy
node server.js
```
- Open index.html in browser

## Functions to Add
- saveAs

## Other To-Dos
- Add marker colors, icons
- After placing a set of markers, make sure viewport will include them all
- Make target host a parameter
- Routes, paths
- Navigation? Distance?

