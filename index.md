# PicSqueeze Privacy Policy

**Effective date:** 2026-10-21
**Publisher:** Bruno Viet
**Contact:** viettranquocdo311@gmail.com

> This file is the policy text. It is **not** a public web page yet. Microsoft's Store Policy 10.5.1 says Win32 and Desktop Bridge
> products "must always have privacy policies" and that you give users access by entering the policy URL in Partner Center.
> See `MICROSOFT_STORE_PUBLISHING_GUIDE.md` section 7 for two ways to publish it at a stable HTTPS address. Replace every

## Summary

PicSqueeze is an offline Windows app. It works on your computer only. It does not collect, send or sell
your personal information, and it does not connect to the internet.

## What PicSqueeze does with your files

* You choose images or folders (by drag and drop, "Add images" or "Add folder").
* PicSqueeze **reads** those files on your computer, resizes, compresses or converts them, and **writes the results** to the
  output folder you choose (by default `Pictures\PicSqueeze`).
* Your original files are not modified or deleted. If you tick "Replace files with the same name", PicSqueeze asks you to
  confirm before it replaces anything.
* Images are never uploaded anywhere. There is no cloud processing and no account.
* Output files do not carry over the original's embedded metadata (for example camera details or GPS location). This is a side
  effect of how images are re-encoded; it is not a data-collection feature.

## Information PicSqueeze stores on your computer

| What | Where | Why | Contains personal data? |
|---|---|---|---|
| Settings (`settings.json`): your last-used resize, format and quality options, output folder, theme, interface language, saved presets | `%LOCALAPPDATA%\PicSqueeze` | Remember your choices | Only the output-folder path you chose (it may include your Windows user name) |
| Troubleshooting log (`picsqueeze-YYYYMMDD.log`): start/finish events, counts of images processed, error categories | `%LOCALAPPDATA%\PicSqueeze\logs` | Help diagnose problems | No. File names, folder paths and image contents are not written to the log. Exceptions are logged by type only. |

Logs older than 7 days are deleted automatically. This information is never sent to the publisher or anyone else.
When the app is installed from the Microsoft Store, Windows keeps these files in a private per-app location and removes them
when you uninstall the app. You can also use **Settings > Open data folder** and delete the files yourself, or
**Settings > Reset settings**.

## Network access, analytics and advertising

* PicSqueeze does not make network connections. It contains no analytics, telemetry, crash-reporting service, advertising or
  tracking code, and no third-party web services.
* This was checked before release: a source search found no networking or telemetry code, none of the app's dependencies is an
  HTTP or telemetry library, and the running app showed no network connections during start-up and a full batch
  (see `FINAL_REPORT.md`, "Privacy verification").
* Windows and the Microsoft Store (which delivers and updates the app) have their own network activity and privacy
  practices, which are described by Microsoft. They are not controlled by this app.

## Children

PicSqueeze does not collect information from anyone, including children.

## Sharing

PicSqueeze does not share, sell or disclose any personal information, because it does not collect any.

## Your choices and rights

You stay in control of your files: you decide which images are processed and where results are saved. To remove everything
PicSqueeze stored, uninstall the app (Store installs) or delete `%LOCALAPPDATA%\PicSqueeze`.

## Changes to this policy

If a future version adds anything that could involve personal data (for example cloud features, analytics or crash reports),
this policy and the Microsoft Store declarations will be updated **before** that version is released, and the change will be
described in the release notes.

## Contact

[USER ACTION REQUIRED - publisher name, support email and, if you have one, a postal address or website]
