## Testing OpenAI Api
In this application you can ask something to the chat Gpt in your terminal and receive answers.
It is just a study application

### About the application
#### Docs and Packages
- npm init (create your package)
- create a js document in the package root
- set type to module in the package.json
-  npm i dotenv 
-  npm i openai
-  run the project (npm run dev)

#### How to use OpenAI api
- Create a login  : https://openai.com/blog/openai-api
- go to your profile  and select the manage account option
- select the api keys option
- click on create a new key and copy the key
- go to your .env document 
- create a var API_KEY= Your key 
-import{Configuration,OpenAIApi} from 'openai
- create a new openai object and set the configs



\*const openai= new OpenAIApi(new Configuration({
    apiKey:apiKey
}))\*



### Preview
 ![fotor_2023-3-30_11_13_6](https://user-images.githubusercontent.com/59897065/228864444-170ac534-b0d8-4e74-b385-a473e6cd9f53.png)


### Documentation : https://platform.openai.com/docs/introduction
