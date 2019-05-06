![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Remote CRUD
### Author: Erin Trainor

### Description
- [ ] Remove the code that requires the .json file in your react app for the schema and adds it to state

- [ ] Pull the schema from the remote server via the resource path /api/v1/players/schema (or whichever model you choose)

- [ ] On your first pull from the server of the database records, save them in the store for faster retrieval

- [ ] Instead of saving straight to the Redux Store, use an async action creator function to send data to the server (using post or put) and then update the local store

- [ ] When rendering the forms and lists, use the store as a cache, and update it after you save to the server.

- [ ] Testing

- [ ] Styling

### Links, Resources and Documentation
* [PR](https://github.com/401-advanced-javascript-401d29/lab-34/pull/1)
* [Code Sandbox](https://codesandbox.io/s/kmon436rk5)

#### UML
![uml image](UNADJUSTEDNONRAW_thumb_1836.jpg)
