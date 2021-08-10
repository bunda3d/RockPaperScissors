# RockPaperScissors
### a Blazor game of Paper, Rock, Scissors

Play online at:
https://bunda3d.github.io/RockPaperScissors/ 

## GitHub Pages Static Site Branch
This branch was created for a GitHub Actions Workflow job to publish a static site version of the blazor app to, for GitHub Pages to host and serve the app.  

****  

## For more info about this app or on publishing Blazor apps to GitHub Pages, see: 

### Step by step from Niels Swimberghe  
https://swimburger.net/blog/dotnet/how-to-deploy-aspnet-blazor-webassembly-to-github-pages

### MS Docs briefly touches on publishing Blazor (Do as Steve Sanderson does):
but also points to Steve Sanderson's repo, with his workflow yaml and wwwroot files are what I ultimately copied from the most, I think...  
https://docs.microsoft.com/en-us/aspnet/core/blazor/host-and-deploy/webassembly?view=aspnetcore-5.0#github-pages-1

### This guy did the best job explaining a couple things:  
Like setting up a github_token (or publish_token as he names it), and setting up gh-pages (create a gh-pages branch to publish your static site app to or you'll have repo merge issues from the remote files your job bot is creating on Master that git doesn't understand how to merge back its history).  
https://www.meziantou.net/publishing-a-blazor-webassembly-application-to-github-pages.htm
  
### The app is my take on Felipe Gavilán's Rock, Paper, Scissors app
Felipe has excellent courses on Udemy, buy this one and build a Blazor app that will help you understand a lot about the architecture and how to apply it to real-world requirements.  
https://www.udemy.com/course/programming-in-blazor-aspnet-core/ 
