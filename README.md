# How to Get Your API Key for Simple ChatGPT API

To use the **Simple ChatGPT API**, follow these steps to get your API Key from **RapidAPI**:

---

## 1. Create a RapidAPI Account
- Visit [RapidAPI](https://rapidapi.com/).
- Sign up for an account if you don’t have one. You can use your email, Google, or GitHub account to register.

---

## 2. Find the Simple ChatGPT API
- Use the search bar at the top of the page to search for **"Simple ChatGPT API"**.
- Select the appropriate API from the search results.

---

## 3. Subscribe to the API
- On the API page, review the available subscription plans.
- Select a plan (there is typically a Free Tier available for testing purposes).
- Click **Subscribe** to activate the selected plan.

---

## 4. Get Your API Key
- After subscribing, navigate to the **Endpoints** or **Authorization** section of the API page.
- You will see your **API Key** listed under the **Header Parameters** section as `X-RapidAPI-Key`.
- Copy the API Key for use in your project.

---

## 5. Use the API Key in Your Code
Insert the API Key into your project as follows:
```python
headers = {
    "content-type": "application/json",
    "X-RapidAPI-Key": "YOUR_API_KEY_HERE",  # Replace with your actual API key
    "X-RapidAPI-Host": "simple-chatgpt-api.p.rapidapi.com"
}
