# App ID Sanity

App IDs are "[the herpes of iPhone provisioning][so-herpes]". Once you've created one, you're
stuck with it for life. You can't edit it or delete it. By the time I realised this, I had way
more than I needed.

**App ID Sanity** is the cure! It's a simple browser extension that adds the ability to:

  * Rename an App ID
  * Mark an App ID as inactive (hides it from the App ID drop-down when creating a provisioning profile)

App ID Sanity works in Safari and Google Chrome.

## Safari

[Install Now][safari-latest] 

(Downloads the compiled extension from Amazon S3)

## Google Chrome

Install from the [Chrome Web Store][chrome-webstore].

## Release notes

### v1.7

- Inactive App IDs now show minimal information in the App IDs view

### v1.6

- Fixed [issue #3][issue-3]

### v1.5

- Added active/incative indicator to App IDs view

### v1.4

- Fixed [issue #1][issue-1]


[chrome-webstore]: https://chrome.google.com/webstore/detail/dleofkjfblmgcedmhdankbcmhonjndne
[so-herpes]: http://stackoverflow.com/questions/3004833/how-to-remove-app-ids-from-iphone-provisioning-portal/3004867#3004867
[downloads]: https://github.com/simonwhitaker/app-id-sanity/downloads
[safari-latest]: https://s3.amazonaws.com/app-id-sanity/app-id-sanity-1.7.safariextz
[issue-3]: https://github.com/simonwhitaker/app-id-sanity/pull/3
[issue-1]: https://github.com/simonwhitaker/app-id-sanity/issues/1
