# Getting Free Gemini API Key

Getting a free API key for Google Gemini is a straightforward process designed to allow developers and users to experiment with the Gemini models. Google offers a free tier through Google AI Studio, which is suitable for development, testing, and small-scale applications.

Here's a short guide on how to get your free Gemini API key:

**1. Visit Google AI Studio:**

- Open your web browser and navigate to the Google AI Studio website : [aistudio.google.com](https://aistudio.google.com). This is the primary platform for accessing the Gemini API free tier.

![gemini-api-key-1.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-1.png)

**2. Sign in with your Google Account:**

- You will need to sign in using your standard Google account credentials. If you don't have a Google account, you'll need to create one.

**3. Accept the Terms of Service:**

- If this is your first time accessing Google AI Studio or the Gemini API, you will likely be presented with the Google APIs Terms of Service and Gemini API Additional Terms of Service. Read through them and accept the terms to proceed. You may also have an option to opt-in for email updates, which is optional.

**4. Get your API Key:**

- Once you are in Google AI Studio, look for an option like "Get API key". This is usually a prominent button or link on the page.
- Clicking this will take you to a section where you can generate your API key. You may have the option to create an API key in a new project or select an existing Google Cloud project. For most users getting started, creating a key in a new project is sufficient.

![gemini-api-key-2.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-2.png)

If you don't have the option of "Create API key in a new Project" then you need to create a google cloud project first. To do that header over to [console.cloud.google.com](https://console.cloud.google.com/projectcreate?pli=1&inv=1&invt=AbxypQ) to create a new project. If you are prompted to login, please do.

![gemini-api-key-3.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-3.png)

Now go back to Google AI studio, close the create API key modal and refresh the page. Then click on "Create API Key" again and search for it on the "Search Google Cloud projects" input. Note that it might take a few seconds for your project to show up. Then click "Create API key in existing project"

![gemini-api-key-4.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-4.png)

![gemini-api-key-5.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-5.png)

**5. Copy and Securely Store Your API Key:**

- Your newly generated API key will be displayed. It's crucial to copy this key immediately and store it in a secure location. **Do not share your API key publicly or include it directly in your client-side application code**, as this could lead to unauthorized usage.

![gemini-api-key-6.png](https://alxappliedai.github.io/ai_for_devs_module_1_assets/common/gemini-api-key-6.png)

**Understanding the Free Tier:**

The free tier of the Gemini API, accessed through Google AI Studio, provides a limited number of requests and tokens per minute/day. This is ideal for:

- **Experimenting:** Trying out the different Gemini models and their capabilities.
- **Prototyping:** Building and testing small applications or features.
- **Learning:** Understanding how to integrate and use the Gemini API.

For higher usage limits, additional features, and different data handling options, you would need to upgrade to a paid tier, which typically involves linking a billing account to a Google Cloud project.

**Important Considerations:**

- **Rate Limits:** Be aware of the rate limits associated with the free tier (requests per minute, tokens per minute, etc.) to avoid hitting quotas during development and testing.
- **Security:** Always handle your API key securely. Consider using environment variables or secret management systems when deploying applications that use the API.
- **Usage Monitoring:** Monitor your API usage to stay within the free tier limits and understand when you might need to consider upgrading to a paid tier.

By following these steps, you can obtain your free Gemini API key and start exploring the capabilities of the Gemini models for your projects.
