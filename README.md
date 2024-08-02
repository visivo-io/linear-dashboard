# linear-dashboard
Pre-built dashboards to help visualize your Linear projects, issues and employee completions based on tables from the fivetran linear connector. 

# Demo

[Here is the deployed dashboard](https://visivo-linear-dashboard.netlify.app/)

# Getting Started 
1. In your visivo project.visivo.yaml file add the following block:
   ```
   includes:
    - path: visivo-io/linear-dashboard.git@main
   ```
2. Then set the following env variables:

  - `LINEAR_TARGET`: This env var should be the name of a functioning snowflake target in your project. 
