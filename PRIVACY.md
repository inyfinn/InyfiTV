### Privacy policy ###

**Last updated:** November 19, 2026

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

- **This connection is not encrypted** (plain HTTP inside your home network). What you type, including **passwords**, travels between the phone and the TV unencrypted, so another device on the same network that captures the traffic could read it. Use it only on a home network you trust. An encrypted companion app is planned.
- The TV answers only devices of the local network, and only those that know the random key of the QR code (it changes when the app restarts or you choose **New link**); after many wrong keys it stops answering that device for a while.
- The TV **does not save** what you type or the passwords you send, and does not write them to its logs. Files you send are saved in its downloads.

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
