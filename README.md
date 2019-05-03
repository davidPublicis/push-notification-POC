1, A client app installs a service worker. It is an autonomously working script in your browser which takes more and more functions in recent years. So even if the tab with the application is not currently open, the service worker will accept and show a notification.
2, A user receives a request to display notifications.
3, After receiving permission to display notifications, the browser hands credentials and other service information to the app. This data must be sent to the backend and stored in the db.
4, Using the previously received credentials, the backend makes a request to the service provider, which in turn sends a notification to the service worker.
5, The service worker receives a notification and shows it.
