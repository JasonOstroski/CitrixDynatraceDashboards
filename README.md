# Dynatrace Citrix Dashboards
![OverviewDashboard](images/Overview.png)

These Dynatrace dashboards are pre-configured for monitoring your Citrix Environment. From VDA hotspots to StoreFront and end user analytics, the Dynatrace Citrix Dashboard Pack makes it easy to analyze your Citrix implementation and pinpoint areas for infrastructure and performance optimization. They are most effective when used with the [Dynatrace Citrix Extension](https://www.dynatrace.com/news/blog/optimize-citrix-platform-performance-and-user-experience-with-dynatrace/). For deployment, utilize the [BizOps Configurator](https://dynatrace.github.io/BizOpsConfigurator). 

# Pre-Requisites and Best Practices
- Dynatrace deployed on your Citrix hosts. This includes VDAS, Delivery Controllers, and StoreFront Servers. 
- A [Management Zone](https://www.dynatrace.com/support/help/shortlink/management-zones-hub) defined in Dynatrace for your entire Citrix Environment.
  - When multiple Citrix farms or regions are utilized, it is recommended to utilize a [Host Group](https://www.dynatrace.com/support/help/shortlink/host-groups) and Management Zones for each Citrix VDA farm/region for easy filtering and analysis.
- An [Application Definition](https://www.dynatrace.com/support/help/shortlink/my-web-application) for the StoreFront app.
- An Application Definition for the custom Citrix App.

