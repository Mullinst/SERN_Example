Basic SERN setup with SQLite init script, set up with create-react-app and express generator.


To run open two terminal tabs, one to client and one to backend. Run the command "npm install" on both tabs. Then run "PORT=3001 node bin/www" on the backend tab. Then run "npm start" on the client tab. Go to "http://localhost:3000", should show react frontend with some mock user info. User info is hard coded into the server, but the sql db is up and the init script works. Just a show of the stack.