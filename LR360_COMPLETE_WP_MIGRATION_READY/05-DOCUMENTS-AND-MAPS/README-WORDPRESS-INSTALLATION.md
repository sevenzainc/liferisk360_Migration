# LifeRisk360 Kadence / WordPress Publishing Guide

This package is designed for publishing page sections inside the Kadence theme using WordPress pages.

## Recommended publishing method

1. In WordPress, create each page using the slug listed in `wp-page-map.csv`.
2. Edit the page with Kadence Blocks or the WordPress block editor.
3. Add a **Custom HTML** block.
4. Paste the matching file from `wp-code/pages/`.
5. Add the CSS from `wp-code/liferisk360-global.css` in **Appearance > Customize > Additional CSS** or in your child theme.
6. Add the JavaScript from `wp-code/liferisk360-global.js` using a safe header/footer code plugin, Kadence custom scripts, or your child theme.

## Forms

All forms now include visible labels, field IDs, names, and placeholders. For production data capture, replace or connect the HTML forms to WPForms, Fluent Forms, Gravity Forms, Formidable Forms, HubSpot, or another approved CRM/form handler.

## Removed public pages

The Technical Architecture, User Management, and Implementation Roadmap pages have been removed from the public publishing package.

Account Dashboard prototype: the included registration/login demo uses browser localStorage for front-end demonstration only. For production, connect to WordPress users, MemberPress, Paid Memberships Pro, TutorLMS, LearnDash, Ultimate Member, Fluent Forms, WPForms, or a secure custom plugin.


## Account Dashboard Test Logins

After adding `account-dashboard-wp-section.html` and the global JavaScript file, use these test logins:

| Role | Username | Password |
|---|---|---|
| Youth User | Youth1 | LifeRisk360 |
| Parent or Guardian | Parent1 | LifeRisk360 |
| School Facilitator | School1 | LifeRisk360 |
| Community Facilitator | Community1 | LifeRisk360 |

For production WordPress use, replace the browser-storage prototype with WordPress Users, a membership plugin, LMS plugin, or a secure custom role-based access plugin.


Risk taxonomy update: the package includes 15 risk groups and 75 risk items, including Political, Gender, Health, Social Media, and Data Privacy.
