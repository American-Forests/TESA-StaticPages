## To Develop microsite for the 'Tree Equity Score' Project becaue Rohit says so

1. To run the site locally on your machine you'll need to first install Jekyll: https://jekyllrb.com/docs/.
1. To build the site and make it available on a local server:  `bundle exec jekyll serve `
1. Browse to http://localhost:4000

## To push microsite for the 'Tree Equity Score' Project

1. Ensure you have `TESA` credentials in your `~/.aws/credentials` file
1. To push site to production:  `aws s3 sync _site/ s3://tesa-static --delete --profile TESA`
1. Browse to appropriate URL
