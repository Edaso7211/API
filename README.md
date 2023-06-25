# API

⚫ What is an API?
An API is an application’s gateway to the world. It is the interface that allows other systems to interact with the application.

The application can expose as much as it wants and keep its remaining parts abstracted.

APIs are usually a collection of endpoints that clients can call to communicate with the system. This communication is done via request methods such as GET or POST, and may carry some information related to the action the client is willing to perform.

⚫ How webhooks differ from APIs
Webhooks make calls to APIs. An API provides webhooks with the entry point to push data to an application.

When an event occurs in a source application, a webhook request is triggered to one of the API endpoints. This endpoint is known as the webhook URL.

When to use webhooks
Now that you have a good understanding of how webhooks and other communication systems work, in what scenarios is it then appropriate to go with webhooks?

Webhooks are a simplified model of communication thus, you should use webhooks when you require the following:
➡ Real-time one-way communication (from source to destination)

➡ A non-persistent connection between the two systems’ communication

➡ You want to respond immediately to an event from a SaaS application that supports webhooks

➡ You want to use the push model to immediately push updates

➡ The communication is one-to-one

A lot of SaaS applications use webhooks for communication — for example, Shopify uses webhooks to communicate events like when a shopping cart is updated or a sale is made.

Stripe uses webhooks to communicate events like account updates, payments, etc.

https://media.licdn.com/dms/image/D5622AQFWGkh5kWb0Ug/feedshare-shrink_2048_1536/0/1687621820164?e=1690416000&v=beta&t=d1zEIQAfLpUVjkKihu5LD60uUcfkaXq_glgO8GMwBx8![image](https://github.com/Edaso7211/API/assets/126200469/9a82695f-c95d-47f7-a4af-5933570ffb1a)
