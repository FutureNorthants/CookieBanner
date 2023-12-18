# Cookie Banner

A cookie banner that uses Google Analytics consent mode to determine whether to store cookies on the user's machine.

It follows the methodology on this tutorial: https://support.google.com/analytics/answer/9976101?hl=en

## Usage

1. Copy the contents of `src/cookie-banner.html` into your page.
1. Find and replace `LINK_TO_COOKIE_POLICY` with a link to your cookie policy url.
1. Find and replace `GOOGLE_ANALYTICS_ID` with your Google Analytics V4 id.
1. When the user clicks Accept, it will store settings in the browsers local storage allowing functionality, security and analytics.
1. When the user clicks Reject, it will store settings in the browsers local storage to deny all.
