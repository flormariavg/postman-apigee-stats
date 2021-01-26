# Postman Apigee Stats

[![Video Stats API](https://img.youtube.com/vi/7XGZ4RCq6A4/0.jpg)](https://www.youtube.com/watch?v=7XGZ4RCq6A4&feature)

## Requirements

### Apigee:

- Apigee Edge account (evaluation version was used for this development)
- Import Demo proxies from apigee
  ![Apigee Proxies](https://github.com/flormariavg/postman-apigee-stats/blob/main/resources/images/apigee-proxies.png?raw=true)
- Deploy to test and prod environments

### Postman  
- Postman Account
- Change apigee credentials in Authorization tab
  ![Apigee Credentials](https://github.com/flormariavg/postman-apigee-stats/blob/main/resources/images/config-apigee-credentials.png?raw=true)
- Change environment variables, you can play with dimensions and
  ![Enviroment Variables](https://github.com/flormariavg/postman-apigee-stats/blob/main/resources/images/env-variables.png?raw=true)
### Details

Access metrics collected by Apigee Edge that measure API consumption and performance, faster, metrics chart in real time, notifications in case of error and store your metrics in your own database (Mock Server)

What is the problem:

"Data older than six months from the current date is not accessible by default. If you want to access data older than six months, contact Apigee Support." (https://docs.apigee.com/api-platform/reference/policies/statistics-collector-policy#accessing-statistics)
"Note: Data delay interval After API calls are made to proxies, it may take up to 10 minutes for the data to appear in dashboards, custom reports, and management API calls." (https://docs.apigee.com/api-platform/analytics/use-analytics-api-measure-api-program-performance)

## We got it !!!

We created and API in Postman (Stats Api) to save metrics in our Mock server (emulate save metrics in database).

Now you can access faster to your own Database and get the stats that you need anytime.

### Plus:

Analyze your metrics in real time:

- Charts Js and Material Components.
- Notifications: you will recibe a notifications in teams if there are an error in (is Error or Policy Error)