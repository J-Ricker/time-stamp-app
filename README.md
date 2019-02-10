# time-stamp-app
Created for understanding more of node.js and server setup with checks

Need node version: 10.9.0 or higher
Need npm version 6.4.1 or higher

Uses Nodemon for automatic server refresh

# What does this do?
allows user to get specifc timestamp
user must enter valid timestamp or api/timestamp

If data string is empty - will trigger new Date()
If data string is valid - returns JSON
{"unix":1549836602073,"utc":"Sun, 10 Feb 2019 22:10:02 GMT"}

If data string is invalid - returns JSON 
{"error" : "Invalid Date" }

