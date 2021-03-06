---
node_id: 3633
title: Using RBAC with MyRackspace
type: article
created_date: '2013-07-30'
created_by: Renee Rendon
last_modified_date: '2016-01-15'
last_modified_by: Stephanie Fillmon
product: Cloud Servers
product_url: cloud-servers
---

Users who access their cloud accounts through the MyRackspace Portal are
acting as the Cloud account owners. With the implementation of RBAC,
account owners can leave permissions as they are in MyRackspace or set
up restricted access to specific products for users through the Cloud
Control Panel. RBAC is not available in MyRackspace, so these restricted
users have access to the linked Cloud account only through the Cloud
Control Panel.

Through the MyRackspace Portal, account owners grant users the following
permissions to linked Cloud accounts:

-   **Admin**, which only grants full access across all linked Cloud
    products
-   **Read-only**, which grants read-only access across all linked Cloud
    products
-   **None**

**The following scenario illustrates how account managers can grant
access through MyRackspace and through the Cloud Control Panel using
RBAC:**

Rob Smith is the owner of a MyRackspace account that is linked to a
Cloud account. Within the MyRackspace Portal, Rob has granted Bill admin
permissions to the Cloud account and has granted Alice read-only
permissions to the Cloud account. Three other users - Chris, Ted, and
Val - have no access to the Cloud account.

Rob has decided to use RBAC to provide restricted permissions for Chris,
Ted, and Val. Through the Cloud Control Panel, Rob sets up these users
and grants them the following roles:

-   Chris - admin role for Cloud Files
-   Ted - creator role for Next Gen Cloud Servers
-   Val - observer role for Cloud Load Balancers

As a result, Bill and Alice retain their access to the linked Cloud
account through the MyRackspace Portal only. Chris, Ted, and Val now
have access to the linked Cloud account, according to the privileges
granted to their respective roles, through the Cloud Control Panel (but
not through the MyRackspace Portal).

The following graphic illustrates this scenario.

<img src="https://8026b2e3760e2433679c-fffceaebb8c6ee053c935e8915a3fbe7.ssl.cf2.rackcdn.com/field/image/MyRack%20BEST%20Diagram.png" width="652" height="751" />

[&lt; Managing
RBAC](/how-to/managing-role-based-access-control-rbac)
 -   [RBAC Permissions Matrix
&gt;](/how-to/permissions-matrix-for-role-based-access-control-rbac)

