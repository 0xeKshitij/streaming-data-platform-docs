---
sidebar_position: 1
---


# Managing Authorization Headers in Streaming API - Simple Approach

Starting January 9, 2024, access to the V2 APIs will be restricted without the OAuth token.

**Introduction**

There are two primary approaches for managing OAuth2 authorization headers in the Streaming API: Simple Approach and Secure Approach.

![Page](/img/v2Access/tab.png)

**Simple Approach**

This approach is straightforward but less secure since the token remains static and is susceptible to theft or misuse.

**Steps:**

1.  Create a new application record with a validity of a maximum of 1 year.
2.  Generate an access token.
3.  Embed the access token directly into your application.
4.  Utilize the code generation feature in the IDE to obtain the code with the embedded token for your chosen programming language.



**Billing Considerations**

- Billing remains consistent across API v1 and v2.
- Purchase points once and utilize them for either v1 or v2 in any combination.

**Creating an Application**

1.  Go to the **Api-Key** page and click **Create application**.

    ![new](/img/v2Access/newApplication.png)

2.  Enter a name for your application and select an expiration time for the access tokens.
3.  Click **Create**.

**Generating an Access Token**

1.  Go to the **Applications** page and select the application for which you want to generate an access token.

    ![generate](/img/v2Access/generate.png)

2.  Click **Generate Access Token**.
3.  Copy the access token and store it in a secure location.

**Using an Access Token**

To use an access token, include it in the `Authorization` header of your API requests. For example:

```
Authorization: Bearer <access_token>

```

**Revoking an Access Token**

If you believe that your access token has been compromised, you can revoke it by clicking **Revoke** on the **Applications** page.

![revoke](/img/v2Access/revoke.png)

**Deleting an Application**

If you no longer need an application, you can delete it by clicking **Delete** on the **Applications** page.
