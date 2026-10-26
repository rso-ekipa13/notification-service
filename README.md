# notification-service

Wakes up phones that aren't connected. When a message arrives for a device that is offline, this service sends a push through Firebase Cloud Messaging (APNs on iOS). The push carries no content; the app wakes up, downloads the message and decrypts it itself.

Built with .NET 10 and PostgreSQL.

Owner: Eva Vidic. Status: planned.

## Where this fits

This is one of the repositories of [Pretty Good Pigeon](https://github.com/rso-ekipa13), an end-to-end encrypted messenger built by ekipa 13 for the Cloud Computing course at UL FRI (2026/27). The architecture, plan and decisions live in [docs](https://github.com/rso-ekipa13/docs).

`main` only changes through pull requests; day-to-day work goes to `dev`.
