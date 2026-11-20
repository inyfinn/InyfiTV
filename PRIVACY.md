### Privacy policy ###

**Last updated:** November 20, 2026

This policy describes how **InyfiTV** (“the application”) handles information. The application is a private build of open-source software; its license is in `LICENSE.md`. The source code is kept in a private repository, releases are published at https://github.com/inyfinn/InyfiTV.

---

#### Information the application collects ####

The application **does not collect personal data**, has **no accounts** and **does not transmit analytics, crash reports or usage data** from your device to its author or to third-party analytics services.

#### Websites you visit ####

InyfiTV is a **web browser**. When you browse the internet:

- **Websites, networks, and services you use** may collect, store, and process data according to **their own** privacy policies and practices.
- **Your device, ISP, DNS provider, and other intermediaries** may see network activity when you load pages or use online services.
- **Using the web can be risky.** You may expose passwords, payment details, location, or other sensitive information if you enter them on untrusted sites or over insecure connections.

You are responsible for choosing which sites you trust and what information you share online.

#### Search suggestions ####

While you type in the address bar, the application sends the typed text to the **search engine chosen in the settings** (Google by default) and shows the searches it suggests. These requests go **from your device directly to the search engine**, not to us, and are handled under that search engine’s privacy policy. The application sends them **without cookies**, so they are not tied to an account you are signed in to; the search engine still sees your network address.

- Text that looks like a **web address** is not sent.
- Nothing is sent in **incognito mode**.
- You can turn this off: **Settings → Search and home page → Search suggestions**.

#### Updates and filter lists ####

- **Update check.** The application asks `raw.githubusercontent.com` (GitHub) for the file `latest_version.json` of the repository https://github.com/inyfinn/InyfiTV, and downloads a new version from GitHub releases when you accept it. GitHub sees your network address. You can turn the check off: **Settings → About → Auto check for updates**.
- **Ad blocking lists.** The lists of the ad blocker are downloaded from the sites that publish them (for example `easylist.to`, `ublockorigin.github.io`, `filters.adtidy.org`, GitHub). Those sites see your network address. Nothing about the pages you visit is sent to them.

#### Typing and sending from a phone ####

The screen **Phone** (the phone button of the TV bar, of text fields and of the start screen) shows a QR code. A phone that scans it opens a page **served by the TV itself** in your home network; from it you type into the fields of the TV, fill a login form, and send addresses and files. **Nothing of it goes through the internet or through any server**: the phone and the TV talk to each other directly, and they must be on the same home network.

- **Passwords travel encrypted, the rest does not.** The connection is plain HTTP inside your home network. A phone that **scanned the QR code** encrypts passwords (AES-256-GCM) with a second key of the QR code that never goes over the network, so another device on the network that captures the traffic cannot read them. A browser connected with the **6-digit code** can type, but cannot send passwords. Everything else you type and send (texts, addresses, files, bookmarks files) still travels **unencrypted**, so another device on the same network could read it. Use it only on a home network you trust.
- The TV answers only devices of the local network, and only those that know the random key of the QR code (both keys change when the app restarts or you choose **New link**); after many wrong keys it stops answering that device for a while.
- The TV **does not save** what you type, nor a password you send from the **Logowanie** tab, and does not write them to its logs. Files you send are saved in its downloads.

#### Passwords you move from another browser ####

**Settings → Przenieś dane** (Move data) brings bookmarks and passwords from another browser. No app can read another browser's data on Android, so you export them yourself (an HTML file of bookmarks, a CSV file of passwords) and choose the file on the phone page of the TV.

- The **CSV file is read on the phone only**; it is never sent. Only the passwords you tick go to the TV, encrypted as above. The page reminds you to delete the CSV file afterwards: it holds all your passwords unencrypted.
- **The TV saves the passwords you moved**, encrypted with a key of the Android Keystore of the TV that cannot be read out of it, in the application's private storage. They are **not included in backups or device transfers** and are never written to logs.
- A saved password is filled in only on an **https** page of the **same site** it was saved for, only into the form of the page itself (never into a frame of another site), and only after you choose it (the menu of the page or **Zaloguj** on the phone). The TV never sends a saved password to the phone.
- You can delete them one by one or all at once in **Settings → Przenieś dane → Zapisane hasła**. Uninstalling the application or clearing its data deletes them too.
- To show which passwords fit, the TV sends the phone the sites of its bookmarks and history, encrypted; the bookmarks file you send is imported into a new folder of bookmarks.

#### Incognito mode ####

The application offers an **incognito** mode that provides a **temporary, isolated space** for **local site data** (such as cookies and storage used by websites while that mode is active). That local data is intended to be **removed when you leave incognito mode**.

**Incognito mode does not guarantee anonymity or privacy.** It does not hide your activity from websites, your network operator, or other parties that may observe traffic. It is not a substitute for careful behavior on the web.

#### Children ####

The application does not knowingly collect personal information from children. Parents and guardians should supervise minors’ use of any web browser.

#### Changes to this policy ####

This policy may be updated from time to time. The **“Last updated”** date at the top will change when it is. Continued use of the application after changes means you accept the revised policy.

#### Contact ####

For privacy-related questions, open an issue at https://github.com/inyfinn/InyfiTV or write to the owner of the `inyfinn` GitHub account.

---

*This document is provided for transparency. It is not legal advice.*
