**Setting up CI/CD pipeline on AWS and deploying remote web application made using Node.js**

Install Node.js from its official website and create a directory and open **cmd** in that directory

Use **npm –v** command to check the **npm** version

Use **npm init** commnad to create **package.json** file

After creating **package.json** file download **express,nodemon** and jade **dependecy** using **npm**** install **_** package\_name**_ command

For Application Code refer to Github [https://github.com/dhairya2019](https://github.com/dhairya2019) in the express-website repository

After creating application using **git init** command in that same directory you are working

Use git status command to check the unstaged files.

![](RackMultipart20200508-4-n5x69t_html_a3e9899c08ea3755.png)

Use **npx gitignore node** command to create **.gitignore** file to ignore nodemodules for being uploaded to github

Now use **git add .** command to move files to staging area

Now use **git commit –m &quot;your\_message&quot;** command to commit your application

![](RackMultipart20200508-4-n5x69t_html_b855608474a1e3d6.png)

Now **git origin remote &quot;remote-url&quot; command**

And push your code to the remote repository by using **git push –u origin master command**.

Now go to AWS console and go to AWS Beanstalk and create your application.

Now create its enviroment and choose enviroment in which your app is made version and other details

Now click on create enviroment

![](RackMultipart20200508-4-n5x69t_html_e8cafff1c8da11f0.png)

Then go to AWS Code Pipeline Choose its name

Choose Source to Github

Then Login Github using prompt and then choose your repo in which we have pushed the code

Choose branch as mater and go to next step

Choose skip to build stage for now on

Choose Deploy source to EB and then choose application name and enviroment name that you have created and click on create pipeline .

![](RackMultipart20200508-4-n5x69t_html_4e77c2b2484c8422.png)

After that the process will start

After few minutes when both ticks come go to link provided in the enviroment page check your beanstalk link.

![](RackMultipart20200508-4-n5x69t_html_204893de7fc39f68.png)

Note: AWS Beanstalk automatically creates the Ec2 for processing ,S3 for storage and Elastic Load Balancers for default in backend. If you want to change their default configration. Go to Configration Settings when creating Pipleine.

![](RackMultipart20200508-4-n5x69t_html_f2b789065df44450.png)

![](RackMultipart20200508-4-n5x69t_html_7d7479df423e613.png)

Website Link: [http://cicd.ap-south-1.elasticbeanstalk.com/](http://cicd.ap-south-1.elasticbeanstalk.com/)

The website is made using Node.js ,Express and Jade in place of HTML

Its is just a template website

Node Mailer is also used in Contact Section

So if you want to give any reviews or suggestion go to contact section page and send it

It will reach to me

Don&#39;t forget to follow me on github :[https://github.com/dhairya2019](https://github.com/dhairya2019)

Here are links to my some more websites:

[http://sansartech2018.wordpress.com/](http://sansartech2018.wordpress.com/)

[https://sr2018.000webhostapp.com/](https://sr2018.000webhostapp.com/)

Linkedin:[https://www.linkedin.com/in/dhairyaupes500069956/](https://www.linkedin.com/in/dhairyaupes500069956/)
