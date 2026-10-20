# Git-Github
Full Git-Github course
<br>
Author- yaswanth

<h1>Git</h1>
=> It is version control software
<br>
<h1>Git Hub</h1>
<p>It is a platform which is used to store project related files/ source code
in git hub, we can create a source code repository to store project code
All the developers can connect to project repository to store all source code 
Git Hub repository will monitor all code changes</p>

      - who modified
      - when modified"
      - what modified
      - why modified

<h2>Environment Setup</h2>
1) create a account in Git Hub<br>
2) Download and install the Git clint software in our system<br>
3) Open Git bash and configure your name and your email<br>
 <h2>$ git config -- global user.name "your name"</h2>
 <h2>$ git config --global user.email "your-email"</h2>
<br>

<h5>Note : Configuring name and email is just one time process</h5>
<br>
Repository is a place where we can store project source code/ files.<br>
for every project one repository will be created<br>
<p>
1) Public Repo (anybody can see & you can choose who can commit)<br>
2) Private repo (you choose who can see & who can commit)

@ @ Project Git repo URL : https://github.com/YaswanthReddy010201/Git-Github-/edit/main/README.md
Project team members will connect with git repository using URL.
<h2>Git Architecture</h2>
<ul>
     <li><h4> Working Tree</h4></li>
      <li><h4>Staging Area</h4></li>
      <li><h4>local Report</h4></li>
      <li><h4>Central Repo(Remote)</h4></li>
</ul> 
<h1>Basic commands in git</h1>
<h2>echo "# folder_name" >> file name</h2><p>It is used to create a new file </p>
<h2>git init : </h2><P>It is used to initialize the folder as a working tree</P><br>
<h2>git status : </h2><p>It is used for display files status(stated and un-staged </p>
<h2>git add : </h2><p>It is used to add a files to the folder</p><br>

<h2>git commit : </h2> <p> It is used to commit the files from staging area to local report </p><br><h4> git commit -m <msg></h4>

<h2>git remote.add : </h2><p>It is used to send the files from local report to central Repo  It is used the URL of Repo</p>
<h2>EX=> git remort.add https://github.com/YaswanthReddy010201/Git-Github-/edit/main/README.md</h2>
<h2>git.push :</h2><p>It is used to push files from local to central repo </p>
<h2>clear :</h2><p>It is used to clean the ternimal</p>
<h2> touch file name</h2> <p>It is used to create a new file</p>
<h2>git restore : <file name> </h2><p>It is used to discard changes in working directory .What ever changes made to file has be deleted .
</p>
<h5>If your file is in unstated it delete the contant </h5>
<h5>If you stage the changes to the file ( if you added the changes in github file) by git add <file name> (it is useful to staged the unstated file)  command you also git restore --staged <filr name> to get the file from staged to unstaged </h5>
<h1>git restore it depends on what the file status</h1>
<p> After the changes down and the file is in staged to publish you local commits by using <h5>git commit -m "mease"</h5> and use <h5>git push</h5> to get changes to central commits    </p>





</p>





      
