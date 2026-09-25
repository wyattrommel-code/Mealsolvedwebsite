# Android testing landing page

Prepared September 25, 2026. Local draft; do not treat as deployed.

The index update removes stale May/June/September release promises, replaces removed Home actions, explains invitation-based Android testing, removes an unsupported time-saving statistic, and restores native email validation and an accessible label. Existing Mailchimp destination and honeypot are preserved.

Mailchimp audience 714664 now has optional SOURCE, FEEDBACK and MARKETING fields, verified against the generated embed code. All three were enabled in embedded form 52724; adding audience fields alone did not enable collection. The website sends a single MARKETING value, No by default, synchronized to Yes only when the separate unchecked checkbox is selected. General marketing campaigns must target MARKETING exactly Yes; blank and No are not consent. Mailchimp's broad subscription status alone is not sufficient.

The owner-approved first test reached the audience, but the fields were ignored by the old embed configuration. Its hosted thank-you response still advertises June 15 and incorrectly asks for confirmation despite the audience being single opt-in. The embed configuration is now corrected, but a second submission needs owner approval before verifying stored values. Do not claim end-to-end field verification yet.

The new Mailchimp system-form editor opened a migration draft and then failed while dismissing duplicate onboarding overlays. No system-form migration was published. Correct the old confirmation copy or finish and verify the replacement before driving traffic. Do not change opt-in/security settings merely to address the wording.

Verify receipt with a consenting test address, confirmation behavior, and mobile layout. Do not advertise immediate access. Invitations must be granted manually in Play Console first.

Hosting config is Netlify, publish directory is the repository root. Verify the live hosting connection before pushing main; pushing may deploy automatically. No hosting plan change is authorized.
