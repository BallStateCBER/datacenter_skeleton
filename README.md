# CBER Data Center Website Skeleton

## Installation

`composer create-project --prefer-dist BallStateCBER/datacenter_skeleton [app_name]`

## Configuration

- Update `config/app.php`
- Update `config/.env`, `config/.env.production`, and `config/.env.dev`
- Compile `webroot/css/style.less` into `style.css`
- Check to make sure the version of Bootstrap served via [BootstrapCDN.com](https://www.bootstrapcdn.com/) in `Template/Layout/default.ctp` matches that in `vendor/twbs/bootstrap`

## Setting up integrations
- Create a GitHub repository
- Add repo to [Slack's GitHub integration](https://cber.slack.com/apps/A0F7YS2SX-github)
- Add Code Climate to the GitHub repo's integrations & services tab  
  (Using GitHub Service Token found in Code Climate Integrations settings)
- Add to Code Climate tracked repos
- Turn on building in [Travis](https://travis-ci.org/profile/BallStateCBER)
- Add to [Data Center Panopticon](http://cberdata.org/panopticon)
- **Bonus points:** Add Travis and Code Climate badges to `README.md`