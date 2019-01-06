---
layout: post
title:  "Getting Started"
date:   2018-12-16
comments: true
categories: [rovergo, "getting started"]
---

Welcome to [RoverGo]({{site.rovergo_website}})! Let's create your first task.

- First, login to your account at <https://app.rovergo.io>. If you don't have an account, you can create one here with your email address, or use one of our supported login providers.
- Click the [Create Task](https://app.rovergo.io/Task/Create) button.
- Choose a name for your task.
- Enter the connection information for your database. You can connect to either SQL Server or MySQL. Don't worry, your connection information is encrypted.
- Enter your query.

![create task part 1](/assets/images/create-task-1.PNG)

- You can test your query with the Run SQL button. If your server is IP restricted, you'll need to whitelist the IP addresses next to the button.
- You can optionally add a success or failure email addresses to be notified when your task completes.
- Check the enabled box to enable your task.
- Set a schedule. Your schedule options are based on your plan.
- Click Save.

![create task part 2](/assets/images/create-task-2.PNG)

If your server is IP restricted, you'll need to whitelist RoverGo. The IP addresses are at the top of the [task page](https://app.rovergo.io/Task/Create).

![RoverGo IP addresses](/assets/images/create-task-3.PNG)