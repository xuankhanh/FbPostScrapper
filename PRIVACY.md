# Privacy Policy

**Facebook Post Scrapper** (the Windows app, and the Facebook app "Auto Post Funny Videos" it signs in with)

Last updated: October 21, 2026

Facebook Post Scrapper is a Windows desktop app. It runs on your own PC. We don't run a server that keeps your data, and
we don't sell or share your data with anyone.

## What the app uses

- **Your Facebook sign-in.** When you press **Sign in to Facebook...**, you sign in on Facebook's own login page; your
  password never goes into the app. Facebook gives the app an access token for the Page you pick. The app uses it only
  to publish posts to that Page, when you have ticked **Post to my Page**.
- **The Pages you follow.** The app reads the public posts of the Pages you list, to find popular content. It doesn't
  read your personal profile, your friends or your messages.
- **Your license.** If you buy a license, we receive the code the app shows and your email address, only to send you
  your key and support.

## Where it is stored

Everything stays on your PC: the Page token (encrypted with Windows, so it only works for your Windows user on that
PC), your settings, the list of Pages, the results file (`results.csv`) and the log files.

To get a Page token that doesn't expire, the app sends the token from Facebook's login and your Page's ID once to our
token service (on Amazon Web Services). The service exchanges it with Facebook, sends the result back to the app and
keeps nothing: tokens are not stored or logged.

## Deleting your data

You can delete everything the app has, at any time:

1. In Facebook, open **Settings & privacy > Settings > Apps and websites** (or
   https://www.facebook.com/settings?tab=applications), find **Auto Post Funny Videos** and press **Remove**. The
   app's token stops working at once.
2. Uninstall Facebook Post Scrapper in Windows (**Settings > Apps**). This also removes its daily schedule.
3. Delete the folder `%LOCALAPPDATA%\FbPostScrapperApp` (logs and license) and the app's folder if it is still there
   (your settings and `results.csv`).

Posts the app published to your Page stay on your Page until you delete them there.

If you want us to delete the email and license details we hold, or you have any question about your data, write to
**khanh1985@gmail.com**. We delete them within 30 days and reply to confirm.

## Contact

- Email: **khanh1985@gmail.com**
- Phone: +84 985 884 764
