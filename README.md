## Summary
The ITSI Content Pack for Okta-Identity-Cloud from Kinney Group is specifically designed to monitor system health related to Okta Identity Cloud services. It leverages Splunk ITSI to provide in-depth analysis and visualization of logs for Okta Identity Cloud, ensuring critical identity and access management systems are operating optimally. This content pack is an essential tool for IT professionals looking to enhance the reliability and performance of their Okta infrastructure.

* Comprehensive Authentication Monitoring: Offers detailed insights into user authentication processes, multi-factor authentication, and API interactions, enabling optimized security and user experience.
* Critical System Status Tracking: Monitors the real-time operational status of user management, directory synchronization, and single sign-on services, helping IT professionals swiftly identify and address potential issues.
* Enhanced Resource Efficiency: Facilitates better decision-making on resource allocation and system adjustments by analyzing performance trends and detecting inefficiencies across the identity management infrastructure.

This ITSI Content Pack is open source and available for community collaboration and enhancement on [GitHub](https://www.github.com/kinneygroup).

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

## Details
The ITSI Content Pack for Okta-Identity-Cloud contains service definitions and KPIs ready to import to ITSI. The KPI Thresholds and importance values are set to defaults so that they can be tuned manually for your use case. After configuration, this content pack provides a comprehensive monitoring solution for Okta Identity Cloud services.

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

### Services
Okta Identity Cloud monitoring encompasses several specialized services, each targeting specific aspects of identity and access management:

1. AuthService
    * Description: Manages user authentication processes.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
2. MFAService
    * Description: Handles multi-factor authentication processes.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
3. UserMgmt
    * Description: Manages user creation, deletion, and updates.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt)
4. DirSync
    * Description: Synchronizes user data with directory services.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt)
5. APIService
    * Description: Manages API requests and responses.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
6. SSOService
    * Description: Manages single sign-on processes.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt)
7. EventLogs
    * Description: Manages event logging and monitoring.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
8. HealthCheck
    * Description: Monitors the overall health and uptime of the system.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)

### KPIs
Each service utilizes specific KPIs to measure its effectiveness:

1. AuthSuccessRate
    * Description: Measure the percentage of successful authentication attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
2. AuthFailRate
    * Description: Measure the percentage of failed authentication attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
3. AvgAuthTime
    * Description: Measure the average time taken for authentication.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
4. MFASuccessRate
    * Description: Measure the percentage of successful MFA attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
5. MFAFailRate
    * Description: Measure the percentage of failed MFA attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/requirements.txt)
6. AvgMFATime
    * Description: Measure the average time taken for MFA.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
7. UserAddRate
    * Description: Measure the rate of user additions.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
8. UserDelRate
    * Description: Measure the rate of user deletions.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
9. UserUpdRate
    * Description: Measure the rate of user updates.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
10. SyncSuccessRate
    * Description: Measure the percentage of successful directory syncs.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt)
11. SyncFailRate
    * Description: Measure the percentage of failed directory syncs.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/tree.txt)
12. AvgSyncTime
    * Description: Measure the average time taken for directory syncs.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
13. APIReqRate
    * Description: Measure the rate of API requests.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
14. APIFailRate
    * Description: Measure the percentage of failed API requests.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
15. AvgAPIRespTime
    * Description: Measure the average response time of API requests.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
16. SSOLoginRate
    * Description: Measure the rate of SSO logins.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
17. SSOFailRate
    * Description: Measure the percentage of failed SSO attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
18. AvgSSOTime
    * Description: Measure the average time taken for SSO logins.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
19. LogGenRate
    * Description: Measure the rate of log generation.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
20. LogFailRate
    * Description: Measure the percentage of failed log generation attempts.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
21. AvgLogProcTime
    * Description: Measure the average time taken to process logs.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
22. Uptime
    * Description: Measure the system uptime.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
23. Downtime
    * Description: Measure the system downtime.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)
24. HealthScore
    * Description: Measure the overall health score of the system.
    * Source: [../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt](../../itsi-docs-library/Okta-Identity-Cloud/files/length.txt)

### Relationships
#### Dependencies: 
Services are interconnected; for instance, AuthService is dependent on MFAService and APIService. Similarly, SSOService relies on AuthService and APIService for its operations.
#### Hierarchical Structure: 
Some services form a hierarchy, such as UserMgmt depending on DirSync and APIService, illustrating a layered approach to identity management where base services support broader functionalities.

## Installation

### Installation prerequisites:

[Splunk Addon for Okta](https://splunkbase.splunk.com)

[Splunk App for Content Packs](https://splunkbase.splunk.com/app/5391)

[Splunk ITSI](https://www.splunk.com/en_us/products/it-service-intelligence.html)

## Troubleshooting

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

[Github and Readme](https://www.github.com/kinneygroup)

support@kinneygroup.com

## Contact

To provide feedback, visit our [Github and Readme](https://www.github.com/kinneygroup) for our content packs.

support@kinneygroup.com

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

## Version History

| Version | Date  | Description                |
|---------|-------|----------------------------|
| -.-.-   | -/-/- | Initial Preview Release    |

## Considerations:

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)