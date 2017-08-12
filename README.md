# www-jobs

Runs cron jobs for www-stephen-cresswell.net

## Jobs
1. Renews [Let's Encrypt](https://letsencrypt.org/) certificates using (certbot)[https://certbot.eff.org/]
1. Purges old containers, images and volumes (TODO)

## Scripts
The project also contains script for obtaining [Let's Encrypt](https://letsencrypt.org/) for the first time. See [run-once](https://github.com/cressie176/www-jobs/blob/master/container-files/run-once) and [run-once-pretend](https://github.com/cressie176/www-jobs/blob/master/container-files/run-once-pretend). These scripts must be run in conjunction with a web server configured such as [www-nginx](https://github.com/cressie176/www-nginx) to serve files from `/.well-known/acme-challenge`. 
