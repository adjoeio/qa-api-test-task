# Senior QA Engineer (API) - Test Task
You have done an awesome job in your first interview! We designed this case study to get to
know you and your way of working a little better.  
Please take no more than 2h to solve the following questions. Try to focus on the main
important topics and if you struggle with one task try to continue with another one :-)
 
Important: we want to hire human intelligence, not artificial intelligence. Therefore do not use
AI-assisted tools like chatbots or AI coding assistants (e.g. ChatGPT or GitHub Copilot) to solve
this task. You are of course free to use any other tool you like such as IDEs, normal
autocomplete, libraries and so on. But keep in mind that the point of this task is not to present
the perfect solution under ideal conditions, but to show us how you work.  
Note: please do not upload the task or your solution to GitHub or anywhere else. We want to
keep the experience of working on the task the same for all candidates.  

## Run instructions
Clone this Git repository. You will need docker and docker compose installed.  
After doing “docker compose up -d” in the root folder of the repo, the backend API as well as the swagger
documentation will be available. In order to access the swagger documentation, go to
your browser and visit http://localhost:8081. All the backend APIs will be available with
the host http://localhost:8080, you can use Postman or curl to test the API and inspect
requests.  
Good luck and have fun! 💫  

## Task description
The backend developer has finished implementing APIs that the frontend should use in
order to get campaigns, make a view and make a click. The backend developers have
also created swagger documentation describing the API. 
A user is supposed to make a request to /campaign-distribution/campaigns in order to
get the list of campaigns. A campaign is always related to an app, which has a unique creative. 
The frontend will later render this response. When a user
scrolls through the list of campaigns, a request to the ViewURL given in the list should be
executed once and this request will return an empty response. When the user clicks on
the campaign in the list, a request to the ClickURL should be executed and this request
will return in the response the store URL to which the user should then be redirected.  

## Todo
When you are done, send us a zip file containing the test report with prioritization of the bugs, 
as well as any additional material (for example screenshots or log files). If you wrote code or
scripts please include them as well.
Your task is to test the backend API and not any frontend. After your findings, write down a
list of test cases that should be done for regression testing. Suggestions and improvements to the process are also welcome.  
