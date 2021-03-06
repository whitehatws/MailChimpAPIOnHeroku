# MailChimpAPIOnHeroku

This is a newsletter signup form using MailChimp API to collect email addresses for marketing campaigns.<br />

Live demo hosted on Heroku:
https://ancient-oasis-08564.herokuapp.com/<br /><br />

Change these values to your MailChimp information:<br />
const dc = "YOUR_SERVER_LOCATION";<br />
const apiKey = "YOUR_API_KEY";<br />
const list_id = "YOUR_LIST_ID"; <br /><br />

From the MailChimp docs:<br />
Your dc is in your MailChimp URL:<br />
https://{dc}.admin.mailchimp.com/<br /><br />

Your API key is located at:<br />
https://{dc}.admin.mailchimp.com/account/api/<br /><br />

Your list ID is located at:
1) Go to the MailChimp main dashboard.
2) Click Audience.
3) Click All contacts.
4) If you have more than one audience, click the Current audience drop-down and choose the one you want to work with.
5) Click the Settings drop-down and choose Audience name and defaults.
6) In the Audience ID section, you’ll see a string of letters and numbers. This is your audience ID.


![MailChimpAPIOnHeroku](https://github.com/whitehatws/MailChimpAPIOnHeroku/blob/main/mailChimpAPIScreenshot.png)
