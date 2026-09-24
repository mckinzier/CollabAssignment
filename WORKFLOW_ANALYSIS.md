What triggers this workflow to run? (Look at the on: section)
- The code being pushed to main triggers the workflow to run

What are the four main steps this workflow performs? (List each step name)
- checkout code
- validate HTML
- check links
- upload artifact

What does the "Checkout code" step do and why is it necessary?
- It gets the code from the repository and it's important because workflow needs 
the access to the code in order to test and deploy

What is the purpose of the environment configuration?
- to configure the deployment environment

How does this automated deployment improve reliability compared to manual deployment?
- An automated system doesn't make mistakes. It can't forget or do things out of order. It is also 
a huge time saver. It does exactly as it was programmed to do. Humans are prone to making mistakes,
they are inevitable. Therefore, it is better to use automated over manual deployment.

What would happen if you pushed code to a different branch (not main)?
- The website would not deploy. It would checkout code, validate HTML, check links, upload artifact, 
but would not deploy

