# APIs

## About APIs

An API is a way for two or more apps to communicate with each other. Today’s online world has moved from monolithic systems to microservices which are based on REST (RESTful) APIs.

The importance of efficient and reliable APIs cannot be overstated and is why Solodev utilizes Swagger. Swagger is a set of rules (specifications) and tooling to semantically describe APIs using a common language that is readable by both humans and machines. This means the same documentation can be shared with your team while also being used to automate API-dependent processes which is great for testing and debugging API problems. Any API that adheres to the Swagger specs is easy to read, easy to iterate, and easy to consume.

---

## Access Swagger API UI

Choose settings from the left nav and then choose API. This will display the Swagger-UI which takes an existing JSON or YAML document and creates interactive documentation.

<a href="5-api-settings-lg.jpg" target="_blank"><img src="5-api-settings.jpg" style=" margin: auto; display: block"></a>


You can click the accordion to expand it and give you a full description of the parameters with an automatically generated example. This can be done for each method (get, put, post, delete).

<a href="5-api-settings-get-expand-lg.jpg" target="_blank"><img src="5-api-settings-get-expand.jpg" style=" margin: auto; display: block"></a>

---

## API Tokens

To authorize yourself to gain access to Swagger click the authorize button at the top right of the screen. This will bring you to the available authorizations screen.


<a href="5-api-settings-authorize-lg.jpg" target="_blank"><img src="5-api-settings-authorize.jpg" style=" margin: auto; display: block"></a>

There are two options for authorization: **Bearer** and **UserApiToken**.

**Bearer Authentication:**  

Bearer Authentication (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens. The name “bearer authentication” can be understood as “give access to the bearer of this token” the token is a cryptic string usually generated by the server in response to a login request. The client must send this token in the authorization header when making requests to protected resources.

**User Authentication:**

The second option is the UserApiToken (apiKey) which is the scenario we will detail here. 

<a href="5-api-settings-authorize-choice-lg.jpg" target="_blank"><img src="5-api-settings-authorize-choice.jpg" style=" margin: auto; display: block"></a>

To get your user token click on profile to go to your profile page. 

<a href="5-api-settings-click-profile-lg.jpg" target="_blank"><img src="5-api-settings-click-profile.jpg" style=" margin: auto; display: block"></a>

Once at your profile page, click the API Tokens menu option from the left nav. Here you can manage your API tokens by adding, activating, de-activating and deleting them. 

<a href="5-api-prifile-apitokens-home-lg.jpg" target="_blank"><img src="5-api-prifile-apitokens-home.jpg" style=" margin: auto; display: block"></a>

To add a new API Token, click the add API key button in the top right of your screen. This will bring out the add API key modal from the right. 

<a href="5-api-profile-apitokens-addbtn-lg.jpg" target="_blank"><img src="5-api-profile-apitokens-addbtn.jpg" style=" margin: auto; display: block"></a>

Here you can enter your new token’s name and hit the submit button at the bottom right of the modal.

<a href="5-api-profile-apitokens-addmodal-lg.jpg" target="_blank"><img src="5-api-profile-apitokens-addmodal.jpg" style=" margin: auto; display: block"></a>


To use your new key in the validation, click on the eye icon to the right of the hidden token. Then select and copy your key. 

<a href="5-api-profile-apitokens-view-copy-lg.jpg" target="_blank"><img src="5-api-profile-apitokens-view-copy.jpg" style=" margin: auto; display: block"></a>

You can now return to the authentication dialogue box and paste the key the value input field and then click the authorize button.

<a href="5-api-settings-authorize-choice-lg.jpg" target="_blank"><img src="5-api-settings-authorize-choice.jpg" style=" margin: auto; display: block"></a>