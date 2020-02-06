# ioCash APIs Postman collections
This repository contains the updated Postman library and environment with all the API calls available in ioCash.
This way, in less than one minute you will be able to have access and test all ioCash functionalities

## Download postman

Download Postman desktop app. You can do so from <a href="https://www.postman.com/downloads/" target="_blank">here</a>. You can alternatively use the cloud version if you prefer so.

## Import the ioCash client collection

Download from this repository the "iocash client.postman_collection.json"
Open Postman and click on the "import" button on the left top corner. Insert the just downloaded file. Automatically you will see all the API calls on the left hand.

## Import the ioCash client environment

To be able to make the calls work, you will need to import the "iocash client.postman_environment.json" file that contains a couple of variables: 

* base-path: With the URL path pointing to our PRE environment. This variable is used in all the calls of the collection imported
* token_client_test: Here you have to paste your JWT token generated with your API key, public key and private key.

To import the environment, click on the settings button on the right top corner and click import.
