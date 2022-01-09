# BestBuyAPI
BestBuyAPI Task
https://learning.getpostman.com/docs/postman/launching_postman/installation_and_updates Newman Node.js

Steps to follow:

cd api-playground npm install

npm start

cd public/postman/OBE_postman_collections

newman run Best-Buy-API-Playground.postman_collection.json -e BestBuyAPI.postman_environment.json -d BestBuyData.csv

Approach: To automate tests json files were used in Postman. En were created for new collection and basic data set.Test suite structure is provided in Test Cases section below. Every endpoint is covered in the collection.Testcases are attached(API_Testcases.xlsx)
