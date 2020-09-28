---
title: Viewing people in your enterprise account
intro: 'To audit access to enterprise-owned resources or user license usage, enterprise owners can view every administrator and member of the enterprise account.'
product: '{{ site.data.reusables.gated-features.enterprise-accounts }}'
redirect_from:
  - /articles/viewing-people-in-your-enterprise-account
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

### Viewing enterprise owners and billing managers

You can view enterprise owners and billing managers, as well as a list of pending invitations to become owners and billing managers. You can filter the list of enterprise administrators by role. You can find a specific person by searching for their username or full name.

{{ site.data.reusables.enterprise-accounts.access-enterprise }}
{{ site.data.reusables.enterprise-accounts.people-tab }}
{{ site.data.reusables.enterprise-accounts.administrators-tab }}

### Viewing members and outside collaborators

You can view the number of pending members and outside collaborators. You can filter the list of members by deployment ({{ site.data.variables.product.prodname_ghe_cloud }} or {{ site.data.variables.product.prodname_ghe_server }}), role, and organization. You can filter the list of outside collaborators by the visibility of the repositories the collaborator has access to. You can find a specific person by searching for their username or display name.

You can view all the {{ site.data.variables.product.prodname_ghe_cloud }} organizations and {{ site.data.variables.product.prodname_ghe_server }} instances that a member belongs to, and which repositories an outside collaborator has access to, by clicking on the person's name.

{{ site.data.reusables.enterprise-accounts.access-enterprise }}
{{ site.data.reusables.enterprise-accounts.people-tab }}
3. Optionally, to view a list of outside collaborators rather than the list of members, click **Outside collaborators**. ![Outside collaborators tab on the Organization members page](/assets/images/help/business-accounts/outside-collaborators-tab.png)

### Дополнительная литература

- "[Roles for an enterprise account](/articles/roles-for-an-enterprise-account)"