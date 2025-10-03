# Host The Mern Stack Application 
> - Host the Frontend Using the Vercel Service
> - Host the backend Using the redner Service
> - Deploy the Database using the mongoDB. 

> ## MONGODB
>> - Login MONGOBD Dashboard
>>> ![Login](image.png)

>> - Create a New Project
>>> ![project_creation](image-1.png)

>> - Enter the Project Name
>>> ![alt text](image-2.png)

>> - Deploy the Cluster
>>> ![alt text](image-3.png)

>> - Configure the User Credential For DB
>>> ![alt text](image-4.png)

>> - Select the perfect connect
>>> - Select the **Driver**
>>> ![alt text](image-5.png)

>>> - copy the connection strink address 
>>> ![alt text](image-6.png)
>>> ![alt text](image-7.png)

>>> - verify the created user
>>> ![alt text](image-8.png)

> ## Host the frontend using the vercel
>> - Import the source files from git repo
>>> ![alt text](image-9.png)

> ## Push the Code to GitHub 
>> ![alt text](image-10.png)

> ## Deploying the frontend in Vercel
>> ![alt text](image-11.png)

>> ## Verified the Hosting Frontend
>>> ![alt text](image-12.png)

> **Error**
>> - When we try to access the Database using the browser. its not appear here. 
>>> ![alt text](image-13.png)

>> - so we need to create a file vercel.json to overwrite the croute configuration. and put the some source code.
>> - then push the code to git repo. the Deployment is running Automatically.
>>> ![alt text](image-14.png)

> ## Host the Backend using the render Service
>> - Login the Render using the Mail.

>> - Select the **web service** to host the backend.
>>> ![alt text](image-15.png)

>> - Select the public Repo from github
>>> ![alt text](image-16.png)

>> - Enter the Proper name of this project
>> - set the root Directory into our project.
>> - enter the build and start command of backend.
>>> ![alt text](image-17.png)

>> - Set the Env veriables of the DB server and frontend application URL too. in backend service provider.
>>> ![alt text](image-18.png)

>> - Then Redeploy the Backend provider.

>> - Copy the URL of the backend. then Go to frontend provider.
>> - Add the URL in frontend environment.
>>> ![alt text](image-19.png)

>> - Redeploy the backend as manually. 

>> - Mern stack application is completly Working
>>> ![alt text](image-20.png)

>>> ![alt text](image-21.png)

>>> ![alt text](image-22.png)

>>> ![alt text](image-23.png)

> ## Auto Deployment When we push the Code to Repo. it will deploy as automatically 
>> ![alt text](image-24.png)
>> ![alt text](image-25.png)

> ## Access URLs
>> - Frontend   : https://messageappclient.vercel.app
>> - Backend    : https://messageappclient.vercel.app/messages   