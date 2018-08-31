# CBER Data Center Website Skeleton
[![Build Status](https://travis-ci.org/BallStateCBER/datacenter-skeleton.svg?branch=development)](https://travis-ci.org/BallStateCBER/datacenter-skeleton)
[![Maintainability](https://api.codeclimate.com/v1/badges/aa3005ac2fe03da8a2be/maintainability)](https://codeclimate.com/github/BallStateCBER/datacenter-skeleton/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/aa3005ac2fe03da8a2be/test_coverage)](https://codeclimate.com/github/BallStateCBER/datacenter-skeleton/test_coverage)

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

## Setting up integrations
- Create a [GitHub](https://github.com/BallStateCBER/) repository
- Add repo to [Code Climate](https://codeclimate.com/dashboard)
    - Add Slack integration
    - Add GitHub issue integration
    - Go to Repo Settings > Git repository and install webhook  
- Add repo to [Slack's GitHub integration](https://cber.slack.com/apps/A0F7YS2SX-github)
- Turn on building in [Travis](https://travis-ci.org/profile/BallStateCBER)
- Add to [Data Center Panopticon](http://cberdata.org/panopticon)
- **Bonus points:** Add Travis and Code Climate badges to `README.md`
