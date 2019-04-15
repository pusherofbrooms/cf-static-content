This is a simple example of static content on Cloud Foundry. To push this application:

Login to Cloud foundry with:

    cf login -a YOUR_API_ENDPOINT

Have your org manager create a space for you with:

    cf create-space SPACENAME -o ORGNAME

Target your org and space with:

    cf target -o YOUR_ORG -s YOUR_SPACE

And push the application with:

    cf push

You can inspect your application with:

    cf app hellotest

This will give you a lot of information about your application including the route (used in the url), memory and disk usage, uptime, and other useful stuff. Paste the "route" into your browser to see your application say Hello to the World.
