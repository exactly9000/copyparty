a living list of upcoming features / fixes / changes, very roughly in order of priority

* download accelerator
  * definitely download chunks in parallel
  * maybe resumable downloads (chrome-only, jank api)
  * maybe checksum validation (return sha512 of requested range in responses, and probably also warks)

* [github issue #37](https://github.com/9001/copyparty/issues/37) - upload PWA
  * or [maybe not](https://arstechnica.com/tech-policy/2024/02/apple-under-fire-for-disabling-iphone-web-apps-eu-asks-developers-to-weigh-in/), or [maybe](https://arstechnica.com/gadgets/2024/03/apple-changes-course-will-keep-iphone-eu-web-apps-how-they-are-in-ios-17-4/)

* [github issue #57](https://github.com/9001/copyparty/issues/57) - config GUI
  * configs given to -c can be ordered with numerical prefix
  * autorevert settings if it fails to apply
  * countdown until session invalidates in settings gui, with refresh-button

