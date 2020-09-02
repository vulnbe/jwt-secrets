# jwt-secrets

The goal for this project was to find as many public-available JWT secrets as possible to help developers and DevOpses identify it by traffic analysis at the Wallarm NGWAF level. 

We focused on Google search and GitHub dorks by using mainly two query patterns: 
1. ```jwt example +TECHNOLOGY``` where the ```TECHNOLOGY``` is the language itself like PHP, Ruby, Rails, or framework like ExpressJS, Struts of Flask.
1. Google BigQuery search based on 3M GitHub projects
