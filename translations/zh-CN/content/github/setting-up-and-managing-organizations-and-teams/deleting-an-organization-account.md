---
title: 删除组织帐户
intro: '删除组织时，所有仓库、私有仓库复刻、wiki、议题、拉取请求和项目或组织页面也被删除。 {% if currentVersion == "free-pro-team@latest" %}The organization name becomes available for use on a new user or organization account, and your billing will end.{% endif %}'
redirect_from:
  - /articles/deleting-an-organization-account
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---

{% if currentVersion == "free-pro-team@latest" %}
{% tip %}

**提示**：如果要取消已付费的订阅，可以[将组织下载到 {% data variables.product.prodname_free_team %}](/articles/downgrading-your-github-subscription) 而非删除组织及其内容。

{% endtip %}

{% endif %}

### 1. 备份组织内容

删除组织后，GitHub **无法恢复内容**。 Therefore, before you delete your organization, make sure you have a copy of all repositories, wikis, issues, and project boards from the account.

### 2. 删除组织

{% data reusables.profile.access_profile %}
{% data reusables.profile.access_org %}
{% data reusables.organizations.org_settings %}
4. 在组织设置页面底部附近，单击 **Delete this Organization（删除此组织）**。 ![删除此组织按钮](/assets/images/help/settings/settings-organization-delete.png)
