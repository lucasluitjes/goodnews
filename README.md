# goodnews

Tiny hacky script that grabs news from a bunch of RSS feeds, asks ChatGPT if they're likely to make people feel hopeful, and publishes the result as a static site. Issues/PRs welcome.

## provisioning

droplet aanmaken, DO guide voor nginx+letsencrypt volgen, domein er naar wijzen, repo er naar toe rsyncen, .env ook, cronjob instellen die het scriptje draait.

## dev

lokaal dit: `ls | entr rsync -avz . root@goodnews.luitjes.it:/root/goodnews`

en dan op de server, eerst `cd goodnews` en dan `ls | entr ruby grab.rb`


