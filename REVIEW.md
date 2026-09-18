# V27 review

Floating thumbnails are 12% wider: 252px desktop, 168px mobile before per-card scaling. Scroll progress now starts at page origin and tracks the current scroll position directly, removing the old dead zone and 150ms smoothing lag. The next content still waits for all cards to disappear. Other section designs are retained.

Original vector moseif wordmark with a geometric S symbol; favicon uses the same symbol. Research references: https://www.alikzehtab.com/ ; https://www.jourdanhinkle.design/work/personal-rebrand ; https://www.matt-kenney.com/work/mkdc . Reference artwork was not copied.

Brief: prepares two matching, URL-encoded drafts addressed to WhatsApp +201044301448 and mhmd828827@gmail.com. Both require the visitor to confirm Send in the respective app. This is not automatic dual delivery, and it does not claim delivery or receipt. The form keeps input, invalidates stale drafts after edits, accepts a blank video link, validates required fields and provides a copy fallback. No backend credentials are stored in the site.

Checks: JavaScript syntax; desktop logo/artwork; scroll changed orbit during the first 108px while later content remained hidden; Arabic and reserved characters encoded in both message links; empty email blocked by native validation; correct submission generates both drafts; edited notes invalidate old links; mobile 390px and 320px modal widths showed no horizontal overflow. Chromium emulation only, not physical iOS/Android testing. No test messages sent. No browser console errors observed.
