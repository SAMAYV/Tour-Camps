## Tour-Camps Usage Instructions

- Welcome to the Tour-Camps

### Instructions to run the website on a local machine

- Ensure that you have a Functional Text Editor(Atom, SublimeText, VSCode, etc) on your System.

<details>
<summary>Installation</summary>

	- Run the command "$ npm i" to install all the dependencies present in package.json.

</details> 

<details>
<summary>For using virtual environment (Optional)</summary>

	- To install virtual environment:
		$ sudo pip install nodeenv
	- To create new environment:
		$ nodeenv env
	- To activate environment:
		$ . env/bin/activate
	- To deactivate environment: 
		$ deactivate_node

</details> 

<details>
<summary>Additional Work</summary>

	- Create a .env file.
	- Create an account on Cloudinary to upload images and MapBox for using Geolocation API.
	- Store CLOUDINARY_CLOUD_NAME, CLOUDINARY_KEY, CLOUDINARY_SECRET and MAPBOX_TOKEN using credentials of your account in .env file.
	- To use a remote database, create an account on MongoDB Atlas and create a database.
	- Store the database URL under the value DB_URL in .env file. 

</details>

<details>
<summary>Run Server</summary>

	- $ nodemon app.js  OR  $ node app.js
	- Use local database (if any) by "$ mongo"

</details>

<details>
<summary>About</summary>

	- Developed a Tourism Website (using Express.js) where people can search for locations to stay over the world. Used Geolocation API with MapBox to show the cluster Maps and used Sanitize-HTML to prevent attacks.
	- Implemented User-Authentication/Authorisation using Passport.js & rating, review, image upload system on staying locations for authenticated users.
	- Used MongoDB Database and deployed via Heroku.

</details>

### Deployed Website Link
	https://tour-camps.herokuapp.com/
