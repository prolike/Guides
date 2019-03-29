# Setup mail-in support from customers

1. In an incognito browser - log in to mail.prolike.io as `support@prolike.io` `
  * Create a label `support-<customer>`  (e.g. `support-reepay`)
  * Create a filter that applies the label to mails, that arrives from the domain in question:
  ```
  Matches: from:(reepay.com)
  Do this: Apply label "support-reepay"
  ```
2. In the same incognito browser - open a new tab, log into github.com as `Prolike`
3. In a third tab - log in using the google account
    * If you want to modify existing Zaps go to [zapier.com/app/dashboard](https://zapier.com/app/dashboard)
4. Select the "Gmail" app - as trigger select "New labeled email" - select the mail account `support@prolike.io` - select the `support-<customer>` label.
  * From _any_ account send  test mail to `support@prolike.io`
  * Go to the mail box and apply the label manually to see that it works.
5. Select the "GitHub" app to create the issue

...Or simply copy one of the zaps that are already thre - and change the settings.
