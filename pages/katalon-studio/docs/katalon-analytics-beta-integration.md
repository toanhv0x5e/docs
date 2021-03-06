---
title: "Upload Test Results to Katalon TestOps automatically from Katalon Studio" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-studio/docs/katalon-analytics-beta-integration.html
redirect_from:
    - "/display/KD/Katalon+Analytics+%28Beta%29+Integration/"
    - "/display/KD/Katalon%20Analytics%20%28Beta%29%20Integration/"
    - "/x/KRhO/"
    - "/display/KA/Integration+with+Katalon+Studio/"
    - "/display/KA/Integration%20with%20Katalon%20Studio/"
    - "/katalon-analytics/docs/ka-integration-katalon-studio/"
    - "/katalon-analytics/docs/ka-integration-katalon-studio.html"
    - "/katalon-analytics/docs/view-reports/"
    - "/x/mw3R/"
    - "/katalon-analytics/docs/integration-with-katalon-studio.html"
    - "/katalon-analytics/docs/upload-reports-overview.html"
---

To configure the Katalon TestOps Integration, right after activating:

* Select a team in the configured organization that you have permission to access.

* Select a project under that team you would like to work on or create your own one if you have permission.

## Settings

In Katalon Studio, go to **Project > Settings**.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_project_setting.png)

The window **Project Settings** displays, in the **Project Information**, type the name and description, then click OK.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_pro_set_window.png)

You must enable **Katalon TestOps Integration** (in the **Project Settings**) to submit test execution reports to Katalon TestOps. 

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_enable_katalon_testops.png)

Follow the below steps to set up the integration properly:

1. Check the **Enable Katalon TestOps Integration** checkbox to retrieve all teams and projects that you have permission to access in the organization you are working.

Once Katalon Studio is **successfully connected** to Katalon TestOps, all relevant Katalon TestOps the **Teams** and **Projects** will be retrieved and displayed in the Teams and Projects drop-down menu. You can also **create a new project** in Katalon TestOps if you're a team owner or admin, simply click the **New Project** button and enter a name for it.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_create_new_project.png)

 > If you want to switch to another organization, click on the top right corner of the app.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_main.png)

> Select **Deactivate**.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_main_deactive.png)

> **Katalon Studio Activation** displays, type the email, password, and click **Active**.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_activation.png)

2. In **Project Settings**, select a team and project, in which you will upload your test results. Here you can reload this part by clicking **Fetch Projects**.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_fetch_projects.png)

3. Click **Apply** and then **OK** to finish your configurations.

To verify if you have overridden the authentication successfully. On the top right corner, select your account, click **View Dashboard**.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_view_dashboard.png)

The project, which you have created, will be navigated to you.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/ks_dashboard_project_create.png)

## Automatically upload test results

After configuring TestOps settings in Katalon Studio, starting running a test suite.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/run-test-ks.png)

Your test results will be automatically uploaded to TestOps Center.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/integration-ks/upload-to.png)
