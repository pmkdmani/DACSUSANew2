# DACS USA Website — Review Build

This is a review build of the DACS website. It is not published and should be reviewed by DACS management before deployment.

## What changed
- Refreshed the home page hero, service cards, industry/application cards, capability overview, About section, careers call-to-action, panel-build section, contact location panel, and footer.
- Replaced photographic industry/customer imagery and manufacturer/partner logo displays with CSS illustrations, neutral icons, and text.
- Removed placeholder project modals and placeholder copy.
- Restored a lazy-loaded Google Maps embed for the DACS Brighton address, with a separate directions link.
- Added a Request a Quote form using FormSubmit, an external form-processing service. The DACS inbox must complete the first-time activation email before submissions will be delivered.
- Added text-only references to Rockwell Automation and Siemens rather than using their logos; included an independent-provider / no-endorsement note.
- Added a text link to UEP's public panel website, without displaying its logo or asserting a formal partnership.
- Updated the About section to mention turnkey project delivery where applicable.
- Added a separate responsive stylesheet at `css/dacs-enhancements.css`.
- Added basic keyboard focus styling and reduced-motion support.

## Visual asset review
The original image folders and unused image files have been moved to `_source-review/assets/img/`. GitHub Pages/Jekyll normally excludes underscore-prefixed directories from the published site. These files are retained in this ZIP for internal review and are not referenced by the active `index.html`.

Do not move any image back into the active website until its source, commercial-use rights, customer/site permission, people consent, confidentiality, and brand authorization have been checked. The DACS wordmark used in the navigation and the favicon should also be confirmed as DACS-approved assets.

## Management verification required
Before publishing, DACS should verify:
1. Every listed service and capability accurately reflects services DACS currently offers and is authorized to advertise.
2. The industry/application categories are appropriate and do not imply specific customer projects or references.
3. The address, phone, fax, email, and business hours in the Contact section are current and approved for public display.
4. The careers email and application process are correct; the page intentionally does not claim that specific vacancies are currently open.
5. The control panel build wording does not imply a certification, listing, partner relationship, or compliance status.
6. The DACS logo, favicon, company name, and all other company identity assets are authorized for this website.
7. Any future manufacturer names, trademarks, certifications, customer names, customer logos, site photographs, staff photographs, and project case studies have the necessary approvals.

## Technical notes
- The website remains a static HTML/CSS/JavaScript site and retains the existing Bootstrap-based structure.
- No paid components or new JavaScript libraries were added.
- The Contact section embeds Google Maps using the DACS address and links to directions. Google Maps may set cookies or collect usage data when loaded; review the applicable privacy notice and consider a consent-gated map if required by DACS policy.

The request form posts to FormSubmit and sends submissions to dacs@dacsusa.com after the first-time activation email is confirmed. DACS must test the form from the actual domain, verify delivery and spam handling, and review FormSubmit's terms/privacy practices before launch. The form currently redirects to https://www.dacsusa.com/ after successful submission; update this if the canonical domain or thank-you page differs.
- Test the site on current desktop and mobile browsers and confirm all contact details before deployment.


## Required before launch
- Confirm that `https://www.dacsusa.com/` is the canonical live domain and update the form redirect if needed.
- Submit a real test inquiry and complete FormSubmit's one-time email activation. Do not publish until DACS confirms that the email arrives in the intended inbox.
- Add a privacy notice explaining that inquiry data is processed by the selected form provider; obtain management approval for the provider and retention practices.
- Confirm the UEP link is the intended destination and that DACS is comfortable linking to it.
- Obtain management/legal approval for any use of Rockwell Automation or Siemens logos. The current page uses plain-text names only.
