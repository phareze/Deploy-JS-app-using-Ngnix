# Deploy-JS-app-using-Ngnix
Install Nginx on your server. Create a configuration file for your application in the /etc/nginx/conf.d/ directory. This file should define the server block for your application, specify the root directory for your application, and set the appropriate values for the listen and server_name directives.
Test your Nginx configuration by running nginx -t.
If the test is successful, reload Nginx to apply the changes: systemctl reload nginx
That's it! Your JavaScript application should now be accessible at the domain specified in the server_name directive. If you want to serve your application over HTTPS, you'll need to obtain and install an SSL certificate, and update your Nginx configuration to listen on port 443 and use the ssl directive.

I hope this helps! Let me know if you have any questions.
