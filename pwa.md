# PWA

### Questions
* Service worker
    - What is a Web Worker?
    - What is a Service Worker?
    - How is the registration of the service worker? What is the best time to do this?
    - What is scope? Is it possible to install several service workers with different scope?
    - What if in scope pass the same urls for two different service workers?
    - Why there is no access to synchronous browser APIs?
    - What is the life cycle of a service worker? What events can I subscribe to in it? What happens at every event?
    - How can I cache the received data? How can caching SPA applications be implemented?
    - How to reinstall the service worker to a newer one? At what point does the new service worker begin to work? How can I skip the update pending phase?
    - At what points does the browser check the service worker for updates? Is it possible to do this manually?
    - Where is it better to save information when rebooting a service worker?
    - How to implement two-way messaging between a service worker and a client?
    - How can I intercept and process requests?
    - How to see installed service workers?
    - What are dev tools for working with service workers?
* Push notifications
    - What are push notifications?
    - What components are involved in the initialization and sending of notifications? What does each of them do?
    - What is Web Push Protocol?
    - What steps are taken when registering the application on the notification server?
    - What is the purpose of the PushSubscription object?
    - How to implement the receipt and processing of notifications? How to show the received notification to the user? What will happen if we do not show the received notification to the user?
    - Why do I need a service worker in Push Notifications? Is it possible to do without it?
    - How can I customize notifications? What interface elements does he have? How can I control notification behavior?
    - How can I get focus on the window of our application when I click on a notification?
    - Which user cases for displaying the notification subscription window will be useful for UX, and which will not?
    - Is it possible to control the time of sending and the time of receipt of the notification and somehow track it?
    - Do notifications differ in different browsers / different OS?
* Progressive web apps (PWA)
    - What is PWA? What are they used for?
    - What is a web app manifest? How to include a manifest file in your application?
    - Why do I need a service worker in PWA? Why is it impossible to implement a full-fledged PWA without it?
    - What is Application shell? How does this approach affect PWA performance in a cached compartment?
    - What is Background sync? How useful is this technology? How to implement it?
    - What is the difference between PWA and native applications? What are the pros and cons?
    - What are the limitations of PWA when interacting with the OS? And because of what do they arise?
    - Is it possible to customize the PWA application icon on the desktop and its notifications?
* What approaches to the development of web applications, in addition to PWA, appeared with the advent of SW?
* What other workers exist, their distinctive features and purpose?
