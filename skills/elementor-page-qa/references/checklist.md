# Elementor Page QA Checklist

Mark each item `OK`, `Blocker`, `Should fix`, `Nice to have`, or `Not checked`.

## 1. Content
- Headline is clear and matches the page purpose
- No spelling or grammar errors
- No placeholder text, dummy images or "Lorem ipsum"
- Contact details (phone, email, address) are correct
- Prices, offers and dates are correct and current
- Claims are accurate and can be backed up
- Legal pages linked where needed (privacy policy, terms)

## 2. Layout and design
- Consistent fonts, colors, spacing and button styles across sections
- Primary call to action is visible without scrolling
- Clear visual order: headline, proof, offer, action
- Images are sharp, relevant and not stretched
- Enough contrast between text and background
- Header and footer are consistent with the rest of the site

## 3. Mobile and tablet
- No horizontal scrolling
- Text readable without zooming
- Buttons large enough to tap and not too close together
- Columns stack in a sensible order
- Nothing important hidden on mobile
- Sticky header or floating buttons do not cover content
- Tablet view checked, not only desktop and phone

## 4. Links and buttons
- Every button and link goes to the intended place
- Phone numbers use `tel:` links, emails use `mailto:`
- WhatsApp links open the correct number and message
- External links open in a new tab where appropriate
- No broken links or 404s

## 5. Forms
- All fields work and validate correctly
- Success message or thank-you page appears after submit
- Notification email reaches the right inbox (test only with permission)
- Spam protection in place (honeypot or captcha)
- Privacy or consent text where required

## 6. Speed
- Page loads reasonably on mobile (use PageSpeed numbers if provided)
- Images compressed and sized correctly
- Few or no heavy sliders, videos or animation on first screen
- Caching active

## 7. SEO basics
- Page title and meta description set
- One H1, logical heading order
- Alt text on key images
- Page is indexable (no accidental noindex) unless it is intentionally hidden
- Clean URL slug
- Canonical URL correct

## 8. Accessibility basics
- Links and buttons have clear text (not just "click here")
- Form fields have labels
- Focus is visible when tabbing
- Text size and contrast acceptable

## 9. Tracking
- Analytics, ad pixels or conversion tracking installed if required
- Form submit or button click events fire (if the user can confirm)
- Cookie banner present where required
