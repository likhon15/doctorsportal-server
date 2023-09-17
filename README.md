# doctorsportal-server


vercel code - that i always face problem when deploying server
`
{
 "version": 2,
 "builds": [
  {
   "src": "./index.js",
   "use": "@vercel/node"
  }
 ],
 "routes": [
  {
   "src": "/(.*)",
   "dest": "/",
   "methods": [
    "GET",
    "POST",
    "PATCH",
    "DELETE",
    "OPTIONS",
    "PUT"
   ]
  }
 ]
}
`
