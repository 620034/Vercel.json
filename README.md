# Vercel.json
{
  "version": 2,
  "name": "native-server",
  "builds": [{ "src": "server.js", "use": "@vercel/node" }],
  "routes": [{ "src": "/(.*)", "dest": "/server.js" }]
}
