Setting up CI/CD pipeline on AWS and deploying remote web application made using Node.js 

Install Node.js from its official website and create a directory and open cmd in that directory 

Use npm –v command to check the npm version  

Use npm init commnad to create package.json file  

After creating package.json file download express,nodemon and jade dependecy using npm install package_name command 

For Application Code refer to Github https://github.com/dhairya2019 in the express-website repository 

After creating application using git init command in that same directory you are working 

Use git status command to check the unstaged files. 

 

Use npx gitignore node command to create .gitignore file to ignore nodemodules  for being uploaded to github 

Now use git add .  command to move files to staging area 

Now  use git commit –m “your_message” command  to commit your application 

 

Now git origin remote “remote-url” command  

And push your code to the remote repository by using git push –u origin master command . 

Now go to AWS console and go to AWS Beanstalk and create your application. 

Now create its enviroment and choose enviroment in which your app is made version and other details 

Now click on create enviroment 

 

Then go to AWS Code Pipeline Choose its name  

Choose Source to Github  

Then Login Github using prompt and then choose your repo in which we have pushed the code 

Choose branch as mater and go to next step  

Choose skip to build stage for now on 

Choose Deploy source to EB and then choose application name and enviroment name that you have created and click on create pipeline . 

 

After that the process will start  

After few minutes when both ticks come go to link provided in the enviroment page check your beanstalk link. 

 

 

 

Note: AWS Beanstalk automatically creates the Ec2 for processing ,S3 for storage and Elastic Load Balancers for default in backend. If you want to change their default configration. Go to Configration Settings when creating Pipleine. 

 

 

 

Website Link: http://cicd.ap-south-1.elasticbeanstalk.com/ 

The website is made using Node.js ,Express and Jade in place of HTML 

Its is just a template website 

Node Mailer is also used in Contact Section 

So if you want to give any reviews or suggestion go to contact section page and send it 

It will reach to me 

Don’t forget to follow me on github :https://github.com/dhairya2019 

 

Here are links to my some more websites: 

http://sansartech2018.wordpress.com/ 

https://sr2018.000webhostapp.com/ 

Linkedin:https://www.linkedin.com/in/dhairyaupes500069956/ 

 
