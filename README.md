# CBER Data Center Website Skeleton
[![Build Status](https://travis-ci.org/BallStateCBER/datacenter_skeleton.svg?branch=development)](https://travis-ci.org/BallStateCBER/datacenter_skeleton)
[![Code Climate](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/badges/80311f8e2345008349a3/gpa.svg)](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/feed)
[![Test Coverage](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/badges/80311f8e2345008349a3/coverage.svg)](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/coverage)
[![Issue Count](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/badges/80311f8e2345008349a3/issue_count.svg)](https://codeclimate.com/repos/5988cd375c5bfe02640000ff/feed)

## Installation
1. `composer create-project --prefer-dist ballstatecber/datacenter-skeleton [app_name] -s dev`
2. `cd [app_name]`
3. `npm install`
4. `gulp less`

## Configuration
- Update `app.php`, `.env`, `.env.production`, and `.env.dev` in `/config`
  - `data_center_subsite_title`
  - `google_analytics_id`
  - Database configuration
  - Optional email configuration
- Update `README.md`
- Update `package.json`
- Change 'App Name' in `gulpfile.js`
- Check to make sure the version of Bootstrap served via [BootstrapCDN.com](https://www.bootstrapcdn.com/) in `Template/Layout/default.ctp` matches that in `vendor/twbs/bootstrap`

## Setting up integrations
- Create a [GitHub](https://github.com/BallStateCBER/) repository
- Add repo to [Code Climate](https://codeclimate.com/dashboard)
    - Add Slack integration
    - Add GitHub issue integration
- Add Code Climate to the GitHub repo's integrations & services tab  
- Add repo to [Slack's GitHub integration](https://cber.slack.com/apps/A0F7YS2SX-github)
- Turn on building in [Travis](https://travis-ci.org/profile/BallStateCBER)
- Add to [Data Center Panopticon](http://cberdata.org/panopticon)
- **Bonus points:** Add Travis and Code Climate badges to `README.md`
