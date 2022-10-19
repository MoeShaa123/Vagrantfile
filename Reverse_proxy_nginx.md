# To set up Reverse Proxy you need to got through these steps.

## To set up the reverse proxy, you first need to get in to the Nginx files.

## To do this, `sudo nano /etc/nginx/sites-available/default` into VM home folder

## Then where it says location, replace the comments with this:

        proxy_pass http://localhost:3000;
        proxy_http_version 1.1;
        proxy_set_header Upgrade $http_upgrade;
        proxy_set_header Connection 'upgrade';
        proxy_set_header Host $host;
        proxy_cache_bypass $http_upgrade;`

## Exit once you have done that, and then check the syntax with `sudo nginx -t`

## Run `sudo sytemctl restart nginx`, then go back in to the app folder and `npm start`

## Now you have the app open without including Port 3000
