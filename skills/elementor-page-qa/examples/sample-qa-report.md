# Page QA Report (sample, fictional)

**Page:** https://example.com/service-landing (staging)
**Reviewed:** 15 Oct 2026
**Purpose:** Lead generation for a local service business

## Launch verdict

**Ready after blockers are fixed.** The page is clear and well structured, but the enquiry form does not confirm submission and one button points to the wrong place.

## Blockers

1. **Enquiry form, all devices:** no success message after submit, so visitors may submit repeatedly or leave unsure. Add a thank-you message or redirect.
2. **Hero section, "Call now" button:** links to the home page instead of a `tel:` link. Replace with the business phone number.
3. **Mobile, hero section:** heading wraps to four lines and pushes the main button below the first screen. Reduce heading size on mobile.

## Should fix

1. **Pricing section, mobile:** columns stack in the wrong order (price appears above the plan name). Reorder on mobile.
2. **Images:** two gallery images are very large files. Compress them.
3. **Footer:** privacy policy link is missing.

## Nice to have

1. Button color differs slightly between hero and footer. Use the global button style.
2. Add alt text to the team photo.

## Not checked

- Notification email delivery: form test was not permitted.
- Analytics and conversion tracking: no access provided.
