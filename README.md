# Interview
This project was a web app wherein one has to register or login to access. After logging in you can add or contribute topics and questions as per your choice for others, which then further be verified and uploaded by admins and practice them to improve your cp skills. 

# Dependencies used
   * [Mongoose](https://mongoosejs.com/docs/)
   * [EJS](https://ejs.co/)
   * [Express](http://expressjs.com/)
   * [Admin-bro](https://adminbro.com/section-modules.html/)
 
## Usage

Inorder to run the website locally on your computer , follow the steps given below:

* Clone this Github repo.
* Open the terminal and change the directory to the downloaded folder, then run the command 

```sh
 npm install
```
* The above command will install all the required packages and dependencies required for the project


* Add your mongodb URI in the app.js

`module.exports = {
    MongoURI : 'mongodb+srv://<user>:password@cluster08451.am7f4.mongodb.net/<name of database>?retryWrites=true&w=majority'
}`

* The final step is to run the following command
```sh
 nodemon app
 
```
 
 `Visit http://localhost:3000`

## Welcome Page
![1](https://user-images.githubusercontent.com/75686458/126052437-f1f8f808-24a4-424e-9f08-7966e98915e9.png)

## Login/SignUp Page
![2](https://user-images.githubusercontent.com/70435148/108624704-8913d380-746c-11eb-8a7d-5726329755e2.png)

## User Panel(Practice Panel)
*You can practice questions related to all the topics mentioned. 
You can also contribute by adding questions and topics.*

![3](https://user-images.githubusercontent.com/70435148/108629695-2a0f8800-7487-11eb-877b-483f2797f4e8.png)

*This is how the added questions will look like.*

![4](https://user-images.githubusercontent.com/70435148/108629831-c5086200-7487-11eb-8339-2f36103954e9.png)

## Admin Auth
![5](https://user-images.githubusercontent.com/70435148/108629919-30eaca80-7488-11eb-8f4f-137da8a9e0d6.png)

## Admin panel
*I have used admin-bro library for making an interactive admin panel. Main purpose of the admin is to approve the questions and topics added by the users. He can also control various other site services.* 
![6](https://user-images.githubusercontent.com/70435148/108630065-0baa8c00-7489-11eb-97f8-f1e44c2ff940.png)
