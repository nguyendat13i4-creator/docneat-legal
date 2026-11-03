# DocNeat legal website — draft, 2026-11-03

Publisher: Nguyễn Hữu Đạt. Public support/privacy contact: datnguyen.appsupport@gmail.com.
Scope: current native iOS app only. English + Vietnamese sections on each page. No JavaScript, site analytics, remote fonts, forms or external resource requests. External links open only when followed. No website publication or app configuration edit was performed.

## Review before publishing

- Confirm the support mailbox exists and receives mail.
- Confirm intended distribution countries, publisher details and any applicable statutory contact/rights requirements. This draft is not an assurance of legal compliance.
- Check Firebase/Google Analytics console retention settings and data-sharing/advertising options. The draft does not invent a project-specific retention period. Finalize the retention description with the verified configuration before publication.
- Review Analytics/Crashlytics consent/withdrawal requirements for target markets. Current source enables collection and has no in-app telemetry opt-out. Text alone does not implement consent or deletion controls.
- Confirm final SDK collection and App Store privacy labels match the released binary/configuration.
- This Terms page is supplementary product-use information, not a custom EULA replacing Apple's standard EULA. Review before choosing a different license arrangement.
- After approving the final text, set a real effective date and remove the draft banner and draft-only wording in HTML. Do not publish this review draft as the final policy.

## GitHub Pages preparation

Use the separate public docneat-legal repository. Do NOT upload the iOS repository or Firebase configuration.
Upload index.html, privacy.html, terms.html, support.html, styles.css and .nojekyll to the repository root. The Pages setting main / (root) matches this layout. Do not upload this README as the landing page, the ZIP itself, or an enclosing legal-site folder.

Expected URLs after YOU publish and verify them (not currently verified live):
- https://nguyendat13i4-creator.github.io/docneat-legal/privacy.html
- https://nguyendat13i4-creator.github.io/docneat-legal/terms.html
- https://nguyendat13i4-creator.github.io/docneat-legal/support.html

Review each URL in a signed-out browser, on mobile, and check HTTPS. Add links to app Settings / App Store Connect only after final approval and live verification.

## Sources checked

- https://developer.apple.com/app-store/review/guidelines/#privacy
- https://developer.apple.com/app-store/app-privacy-details/
- https://firebase.google.com/support/privacy
- https://firebase.google.com/docs/ios/app-store-data-collection
- https://support.google.com/firebase/answer/6318039?hl=en
- https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection

App facts checked in DocNeatIOSApp.swift, AppExperience.swift, DocumentStore.swift and current product/privacy documentation. Local source documents are never uploaded by these pages. OS backups, Files providers and user-initiated sharing are distinct from an app-operated cloud service.
