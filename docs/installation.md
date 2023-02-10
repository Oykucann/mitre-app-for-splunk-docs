---
title: Installation
---

1. Download the latest [AppInspect Passed](https://splunkbase.splunk.com/app/4617/) version. For the latest changes and development efforts see [github page](https://github.com/seynur/DA-ESS-MitreContent/)
2. Install the application on Splunk Enterprise.  DA-ESS-MitreContent should be installed on the Search Head or Search Head Cluster where Enterprise Security Application resides.
  For details on add-on installation please refer to [Splunk Documentation](https://docs.splunk.com/Documentation/AddOns/released/Overview/Installingadd-ons)

### Initial Setup

--8<-- "initial_setup.md"

### Setup Instructions
After installation of the application you will be on Setup page.  Review your desired configuration for scheduled searches and simply hit Save to continue.  Default view will be the Compliance Dashboard.  If the matrix is not populated, click on the table to run manually, which will direct you to the Lookup Generation dashboard (searches run automatically on that dashboard).

__Note__: If using Alert Manager app, you will need to uncheck ```Use Enterprise Security App``` checkbox within __Setup__ view.
