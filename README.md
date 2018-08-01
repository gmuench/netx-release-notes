# Network Exchange

Network Exchange is a CenturyLink cloud satellite application that provides automated interconnection of heterogeneous networks.

### Prerequisites

You will need to have a CenturyLink Cloud user account prior to using Network Exchange. Please log into https://control.ctl.io if you dont have an account.

## Versioning

* API    V1.1.12
* CLC-UI V1.1.12
* CAM-UI V1.1.15
* DCB    V1.1.9

## Release Update – August 1, 2018
### Enhancement
* API - Reserve Ports by SFP is possible.
* CLC-UI - Increased COLO/DA/DCCF route CIDR to /8.
* CAM-UI - Admin View for CAM portal. Increased COLO/DA/DCCF route CIDR to /8. 
### FIX
* API/CLC-UI/CAM-UI - Minor bug fixes.

## Release Update – July 13, 2018
### Enhancement
* API/CLC-UI/CAM-UI - Added Third Party Shared Access with Single Line feature.

## Release Update – July 2, 2018
### Enhancement
* API/CLC-UI/CAM-UI - Added CenturyLink private Cloud DCCF feature.

## Release Update – June 19, 2018
### Enhancement
* CLC-UI - Minor cosmetic changes.
* CAM-UI - Global map shows combined sites. Minor cosmetic changes. 

## Release Update – June 06, 2018
### Enhancement
* CLC-UI - Minor cosmetic changes.
* CAM-UI - Added global map. Minor cosmetic changes. 

## Release Update – May 03, 2018
### Enhancement
* CLC-UI/CAM-UI - Added redundancy type to the COLO/DA endpoint view. Updated delete exchange/endpoint confirmation wording. Updated AS number valiation logic. More robust filter options for exchanges(for Admin view). 

## Release Update – April 20, 2018
### FIX
* API - Updated logging hostname.

## Release Update – April 11, 2018
### FIX
* API - Updated database hostnames.

## Release Update – April 11, 2018
### FIX
* CLC-UI - Changed backend hostname.
* CAM-UI - Changed backend hostname. 

## Release Update – April 06, 2018
### FIX
* CLC-UI - Added inactivity time out. Disable 'Next' button on CLC feature page after it is being clicked.
* CAM-UI - Added inactivity time out. Disable 'Next' button on CLC feature page after it is being clicked. 

## Release Update – March 28, 2018
### FIX
* CLC-UI - Cross Application validators added for Centurylink Cloud. Atlas version updated to 3.0.3 to fix large hierarchies.
* CAM-UI - Cross Application validators added for Centurylink Cloud. Added CAM provider identity selection.

## Release Update – March 21, 2018
### Enhancement
* CAM-UI - Filtered out CAM personal workspaces. Added a logout button.

## Release Update – March 20, 2018
### Enhancement
* CLC-UI - Added last polled usage data for admins. Removed KB and release notes buttons.
* CAM-UI - Added last polled usage data for admins. Removed KB and release notes buttons.
* API  - Added dependencies for future features.
### Fix
* CLC-UI - Fixed logout button. Test Next hop now uses VIP address. Username shows near logout button.

## Release Update – March 6, 2018
### Fix
* API  - Datacenter expansion bug fixes.

## Release Update – March 2, 2018
### Enhancement
* CLC-UI - Color changes for buttons. Added Test ARP feature. Added Test Next Hop feature.
* CAM-UI - Color changes for buttons. Added Test ARP feature. Added Test Next Hop feature.
* API  - Added Test ARP feature. Added Test Next Hop feature.
### Fix
* API  - Bug fix for port reservation. Bug fix for small architecture datacenters.

## Release Update – February 23, 2018
### Enhancement
* UI/API  - Refactored to support both CLC and CAM authentication. CLC firewall rules view and refresher. 

## Release Update – February 8, 2018
### Bug Fix
API - Prevent exchanged created in CAM showing in CLC.

## Release Update – February 2, 2018
### Enhancement
* API - Database schema change.

## Release Update – February 2, 2018
### Enhancement
* UI/API - Show CLC Firewall Rules.
### Bug Fix
* UI - Add additional Cloud endpoint performs intended pre-build validations.

## Release Update – January 26, 2018
### Enhancement
* UI/API - MLAG Refactoring for CLC
### Bug Fix
* Fix updatedBy field on the UI is not showing correct username when a static route is updated.
* Fix switch usage data is not showing correctly when there are multiple endpoints with same type in one exchange.

## Release Update – January 16, 2018
### Enhancement
* UI/API - Endpoint description update. Allow creating a static endpoint with no static routes.

## Release Update – January 11, 2018
### Enhancement
* UI/API - Add endpoint description. Add NextDC as Colo provider. Add Show Vrrp Action. Add ability to disable endpiont. All multiple static route adds.

## Release Update – January 2, 2018
### Enhancement
* API - Bug fix for iBGP IPs. Added BGP status button for clc endpoints.

## Release Update – December 14, 2017
### Enhancement
* UI - Increased allowed subnet CIDRs for static routes.

## Release Update – October 5, 2017
### Enhancement
* API - Promotional code. IBGP only for HAN. Fix COLO BGP instructions. 
* DCB - Added term billing.
* UI - Added term billing.

## Release Update – September 14, 2017
### Enhancement
* UI - Add DATA3 as a new provider to Managed Hosting.
* UI - Allow homogeneous endpoints in one exchange
* UI - Add "Show Physical Interface" action to COLO and Dedicated Access Endpoints.
* API - Add code related to the UI enhancement.

## Release Update – August 15, 2017
### Fix
* API - Additional firewall rules created for CLC endpoints.
* UI - Special characters allowed in exchange descriptions.
## Release Update – August 8, 2017
### Fix
* API - Added UUID to endpoints.
* UI - Added more meaningful error messages.
## Release Update – June 29, 2017
### Fix
* API - Bug fix related to reseller authentication.
* UI - Bug fix related to reseller authentication.
## Release Update – June 14, 2017
### Fix
* API - Bug fix related to test exchange.
* API - Updated physical interface descriptions.
* UI - Minor cosmetic word change in review your request page.
## Release Update – June 13, 2017
### Enhancement
* API - Added CenturyLink Dedicated Access and Third Party Dedicated Access features.
* UI - Added CenturyLink Dedicated Access and Third Party Dedicated Access features.
## Release Update – June 6, 2017
### Enhancement
* API - Added Exchange Configuration View backend.
* UI - Added Exchange Configuration View.
## Release Update – May 25, 2017
### Enhancement
* API - Fixed naming convention for HAN vlans.
## Release Update – May 24, 2017
### Enhancement
* API - Added internal artifacts for version tracking and endpoint identification.
## Release Update – May 22, 2017
### Enhancement
* API - Exchange Diagnostic tests both primary and secondary paths.
## Release Update – May 19, 2017
### Enhancement
* UI - Added Feature "Providers" to wizards.
* API - Added REST endpoint to support Providers base feature selection.
### Fix
* UI - Minor bug fix related to using the back button in wizards.
## Release Update – May 5, 2017
### Enhancement
* UI - Added KB Button to landing view.
## Release Update – May 4, 2017
### Enhancement
* API - Minor enhancement around internal proxy configuration.
### Fix
* UI - Fixed validation error for "Name Your Exchange" view.
## Release Update – April 27, 2017
### Fix
* API - Minor bug fix.
## Release Update – April 26, 2017
### Enhancement
* API - Added additional logging.
## Release Update – April 25, 2017
### Fix
* API - Minor bug fix.
### New
* UI - Added Release Notes link.
## Release Initial – April 24, 2017
### New
* API/UI - Added ability to create an "Exchange" connecting "Endpoints" together in a virtual mesh of connectivity.
* API/UI - Added "COLO/Dedicated Access" endpoint type for use with customers that have space in CenturyLink datacenters.
* API/UI - Added "HAN" endpoint type to provide connectivity to CenturyLink legacy Hosting and Managed Services.
* API/UI - Added "CLC" endpoint type to provide access to the CenturyLink cloud space.
