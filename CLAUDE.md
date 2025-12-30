# Data Jam Retail Website - Claude Context

## Project Overview
Retail-focused marketing website for Data Jam, targeting **small to medium businesses (SMBs) on the high street** who want to understand their customer footfall.

**Live Site:** https://retail.data-jam.com (planned)
**Based On:** https://data-jam.com (OOH-focused parent site)

## Company Info
- **UK Phone:** +44 7827 813388
- **Email:** hello@data-jam.com
- **Parent Company:** Data Jam (OOH measurement)
- **Retail Tagline:** "Know Your Footfall. Grow Your Business."

## Core Value Proposition
**IMPORTANT: Focus on FOOTFALL for SMBs, not OOH advertising**
- Helps high street businesses understand customer traffic patterns
- Know peak hours, quiet periods, and trends
- Make data-driven decisions about staffing, marketing, and operations
- Privacy-first: no cameras, GDPR compliant
- Affordable for small businesses

## Target Audience
- **Retail Shops** - Boutiques, clothing stores, gift shops
- **Cafes & Restaurants** - Coffee shops, bistros, takeaways
- **Salons & Barbershops** - Hair salons, nail bars, spas
- **Gyms & Studios** - Fitness centers, yoga studios
- **Other High Street** - Galleries, pop-ups, service businesses

## Key Messaging
1. **Know Your Busy Times** - See exactly when customers visit
2. **Understand Quiet Periods** - Identify opportunities for promotions
3. **Measure Marketing Impact** - See if efforts bring more people in
4. **Prove Your Location's Value** - Negotiate rent with real data
5. **Affordable** - Enterprise-level insights at SMB-friendly prices

## Product
**JamBox for Retail** - Same device as OOH, positioned differently:
- Compact footfall counter (no larger than a walnut)
- Plug-and-play: just power + WiFi
- Counts passersby via anonymous device signals
- No cameras, no personal data, GDPR compliant
- Real-time data via online dashboard

## Tech Stack
- Static HTML/CSS/JS (same as parent site)
- Reuses CSS/JS from data-jam.com
- Same design system: dark theme, pink/orange gradient
- Same premium feel: splash screen, custom cursor, particles

## Brand Colors (inherited from Data Jam)
- **White:** #FEFAF9
- **Black:** #0A0C11
- **Pink:** #E62F6E
- **Orange:** #E94B52
- **Gradient:** linear-gradient(135deg, #E62F6E, #E94B52)

## Typography (inherited)
- Headlines: Abeat Regular
- Subheadings: Poppins Medium
- Body: Poppins Light

## Key Files
```
/index.html              - Homepage (retail-focused)
/about.html              - About page (retail focus)
/contact.html            - Contact form (simpler than OOH version)
/contact-success.html    - Form submission success
/css/styles.css          - All styles (copied from parent)
/js/main.js              - Interactions (copied from parent)
/fonts/                  - Abeat font files
/images/                 - Logos, patterns, product images
```

## Differences from Parent Site (data-jam.com)
| data-jam.com | retail.data-jam.com |
|--------------|---------------------|
| OOH media owners | SMB retailers |
| Billboards, transit, DOOH | Shops, cafes, salons |
| Impression counting | Customer counting |
| Advertiser proof of performance | Business decision-making |
| Complex ROI calculator | Simpler messaging |
| Multiple testimonials | Focus on use cases |
| Blog section | No blog (keep simple) |
| API documentation | Not mentioned |

## Content Tone
- **Friendly & Accessible** - Not technical jargon
- **Problem-focused** - "Stop guessing, start knowing"
- **SMB-empathetic** - Understands small business challenges
- **Action-oriented** - Clear CTAs to get started

## Future Considerations
- Add case studies from retail businesses once available
- Consider pricing page with transparent SMB-friendly options
- May add simple blog with retail tips
- Integration with main Data Jam site navigation

## Related Projects
- `/Users/jav/Desktop/data-jam.com/` - Parent OOH website (reference for styling)
- `/Users/jav/Desktop/datajamreports-production/` - PULSE portal (don't modify)

## Deployment
Static site - can be hosted on Netlify, Vercel, or any static host.
Consider same Netlify setup as parent site for consistency.
