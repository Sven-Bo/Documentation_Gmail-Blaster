# Setting Up an App Password in Gmail

To use Gmail Blaster, you'll need to generate an App Password in your Gmail account. This ensures the security of your Gmail account while allowing external apps (like Gmail Blaster) to send emails on your behalf.

Follow these steps to set up your App Password:

#### Step-by-Step Guide:

<details>

<summary><strong>Step 1:</strong>  Enable Two-Step Verification</summary>

To create an App Password, you first need to enable Two-Step Verification in your Gmail account.

* Open your [Google Account Security page](https://myaccount.google.com/intro/security).
* Scroll to the **How you sign in to Google** section.
* Click **2-Step Verification** and follow the instructions to set it up if you haven’t already.

<img src="../.gitbook/assets/image (2).png" alt="" data-size="original">



</details>

<details>

<summary><strong>Step 2:</strong> Generate an App Password</summary>

* On the **Google Account Security** page, in the **Signing in to Google** section, type "App Passwords" into the search bar at the top of the page.
*

    <figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
* Click on **App Passwords** when it appears in the search results.
* You may be prompted to sign in again for security reasons.
*   Type in a name for the app (for example, "Gmail Blaster") and click **Generate**.

    * See screenshots below ⤵️

    <figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

    <figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>



</details>

<details>

<summary><strong>Step 3:</strong> Enter the App Password in Gmail Blaster</summary>

* Open the **SETTINGS** sheet in your Excel file.
* In the **GMAIL\_PASSWORD** field, paste the 16-character App Password.
* Gmail Blaster will now use this password to send emails securely from your Gmail account.

</details>

#### Important Notes:

* Your regular Gmail password **will not work** with Gmail Blaster. You **must use** the App Password for authentication.
* If you change your Google account settings or disable Two-Step Verification, you'll need to generate a new App Password.

#### Troubleshooting:

* If you have issues generating an App Password, make sure that Two-Step Verification is enabled in your Google account.
* Double-check that you've pasted the App Password into the **GMAIL\_PASSWORD** field correctly.
