# Archmorrow website — prepared for publication

Plain HTML and CSS for Rarchie2/archmorrow-site. No dependencies, JavaScript, external fonts, analytics, forms, cookies set by site code, deployment workflow or DNS configuration.

## Files
- index.html — Archmorrow homepage
- streets-wont-forget/privacy.html — app-specific privacy policy
- streets-wont-forget/support.html — app support and FAQs
- assets/styles.css — shared responsive styling
- .nojekyll — serve static files without Jekyll

## Confirmed by the operator
- Ryan Archell trading as Archmorrow, United Kingdom.
- Intended public website: archmorrow.com. Domain configuration has not been changed or verified here.
- Live, tested support/privacy email: support@archmorrow.com (operator-confirmed).
- Routine support-data retention: up to 12 months after resolution, subject to normal provider backup/security processes.
- Porkbun email forwarding to Gmail; only Ryan accesses support messages on behalf of Archmorrow. No helpdesk, CRM, AI support tool, mailing list or other support system. Attachments are voluntary.
- No website analytics, forms, advertising pixels, cookies added by Archmorrow or third-party fonts.
- GitHub Pages hosting target; policy effective date 12 September 2026.
- General football quiz; not intended for Apple's Kids Category. Child-access assessment remains separate.

## Publication checks (not public policy wording)
- Website content is prepared for the confirmed current Build 2; no public placeholders remain.
- Review existing repository contents and explicitly authorise copying/committing/pushing, GitHub Pages/custom-domain configuration and DNS work separately. No publication work was performed.
- The public hosting description assumes the confirmed GitHub Pages target; publish these files on that service or revise the description before using another host.
- Intended privacy URL: https://archmorrow.com/streets-wont-forget/privacy.html
- Intended support URL: https://archmorrow.com/streets-wont-forget/support.html
- Verify HTTPS, redirects, contact links and routes after setup. Relative links also support the GitHub project subpath. No CNAME or workflow added.

## Separate production-ad and App Store release checks
- Confirm actual published regional UMP messages, vendors, personalisation/tracking settings, age treatment, reporting/export practices and release territories before production advertising. Kids Category intent does not settle likely child access.
- Current Build 2 uses test units. Re-review policy and App Store privacy declarations before switching to production. No ATT is implemented; absence alone does not prove no tracking.
- Check in-app privacy-policy access, AdMob app-ads.txt root placement/verification and EU trader requirements where applicable. No Xcode changes made.
- Operational record: ordinary support is described under legitimate interests in answering enquiries/resolving issues; statutory privacy requests under legal obligation. Maintain the corresponding lawful-basis assessment and ensure mailbox deletion practices follow the confirmed retention policy. Provider-specific account terms and transfer safeguards should be kept on record; no UK-only storage or specific contractual safeguard is asserted.

## Local preview
From this directory: python3 -m http.server 8080
Open http://localhost:8080/. No build step.

## Source audit
Read-only inspection of /Users/arch/Documents/App design/Streets Wont Forget at commit a0baadb55c3caddb38aabd3985d445cf3b631f69.
- ContentView, StatsView, SettingsView, GameView: local AppStorage for personal best, total runs, correct totals, trophy and sound/music/vibration preferences.
- QuizRun: in-memory answers/order/score/allowances and run UUID; RewardedGrantGate: temporary presentation UUIDs. No app backend upload code found.
- QuestionBank: bundled Questions.json.
- RewardedAdManager: Google Mobile Ads + UMP, consent update on startup, conditional form and Privacy Options, canRequestAds gate, preloading, local reward callbacks.
- AdConfiguration: usesProductionAdUnits = false.
- Info.plist/source: no ATT usage key or ATT request implemented.
- Package.resolved: Google Mobile Ads 13.9.0, UMP 3.1.0.
- No app account, custom networking backend, separate analytics/crash SDK or access to contacts/camera/microphone/photos/location found in app source.
- Source review does not establish Google account-side configuration, actual network payloads or unconfirmed support operations. Operator-confirmed details are listed above.

Primary documentation consulted:
https://developers.google.com/admob/ios/privacy/data-disclosure
https://developers.google.com/admob/ios/privacy
https://policies.google.com/technologies/partner-sites

