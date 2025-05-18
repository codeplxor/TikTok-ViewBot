# TikTok Viewbotting Api (Usage)

Welcome to the TikvuesApi! This guide provides all the information you need to integrate with our service and programmatically manage engagement for your content.

Our service allows you to request views (or other forms of engagement, as per your service plan) for your specified content URLs.
To Viewbot videos we use real user account & data to send views.
Speed : 50k/m

## 1. Accessing the Service

To use our service, you will need:

1.  **Your unique API Endpoint URL:** This is the specific api address where you will send your requests.
2.  **Your Secret API Key:** A unique key that authenticates your requests.

Both your API Endpoint URL and your Secret API Key will be provided to you privately.

**Important:** Your Secret API Key is sensitive. Treat it like a password and keep it confidential. Do not share it in publicly accessible areas such as client-side code, public repositories, etc.

## 2. Making a Request

All requests to our service must be made using the `POST` HTTP method to your provided API Endpoint URL. The request body must be in JSON format.

**Endpoint:** `Your_Provided_API_Endpoint_URL` (e.g., `http://your.service.ip.address:port/api/order_views`)

**Headers:**
* `Content-Type: application/json`

**Request Body Parameters:**

| Parameter    | Type    | Required | Description                                                                 |
| :----------- | :------ | :------- | :-------------------------------------------------------------------------- |
| `secret_key` | String  | Yes      | Your personal Secret API Key provided to you for authentication.            |
| `link`       | String  | Yes      | The direct URL to the content for which you are requesting engagement.      |
| `quantity`   | Integer | Yes      | The number of views/engagements you are requesting for the specified link.  |

**Example Request using `curl`:**

Replace `Your_Provided_API_Endpoint_URL` with the actual URL and `YOUR_PERSONAL_SECRET_KEY` with the key you received.

# Plans

**1M Views Daily** : 10€/Day, 280€/Month or less

**3M Views Daily** : 20€/Day, 330€/Month or less

**5M Views Daily** : 25€/Day, 360€/Month or less

**10M Views Daily** : 40€/Day, 450€/Month or less

Can do even more cheaper and custom plans if you contact me,

Contact / Buy :

Discord : @loscuantesdesinaloa

# Usages for the Api

**Viewbotting Service** Make your own viewbot service
**Discord Bot** Double your money, by making a discord bot with our api and make an premium subscription for it so users can use the premium plan to get more things
**Botting Website** Make an website that users can bot their Videos.
