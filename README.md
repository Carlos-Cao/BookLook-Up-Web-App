# MSA Web App
<h2> Book Searcher </h2>
<b>URL to the deployed website:</b> https://booksearcher.azurewebsites.net/ <br>
<br>
Book Searcher uses Google Book’s API to aggregate book titles based on search terms, to get the book image, title, authors, date published, published by and description, with up to 30 results available. <br> 
<br>
Built with TypeScript and React. <br>
<br>
<b>Note:</b> No API key is needed.

<h2> Dev-Ops Pipelines </h2>

<ul>
<li> I started my project using Microsoft Azure portal to create a domain to deploy my web app with a URL. </li>
<li> I created a build pipeline with Azure DevOps to configure my pipeline using a `YAML` file which makes changes to the pipeline so that it can build and deploy the react app. </li>
<li> I used Azure DevOps to set up the release piplines for continuous deployment to the production server through my GitHub Repository. By running the azure-pipelines.yml script for every change commited and pushed to the `master` or `develop` branch, the script automatically updates and deploys the latest changes to the live server. </li>
</ul>
