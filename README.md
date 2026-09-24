<a href="https://bre.rs/"><img src="media/cover.jpg" alt="Milan Vlasić, home page on a laptop and a phone" width="100%"></a>

# Milan Vlasić

Personal site in Serbian and English for a Sydney real estate agent who also helps owners abroad with property in Belgrade.

**[bre.rs](https://bre.rs/)** · [Case study (in Serbian)](https://svilenkovic.com/radovi/milan-vlasic) · [Srpski](README.sr.md)

> [!NOTE]
> Client project. The source code belongs to the client and stays in a private repository. This page describes what I built and how.

<table>
  <tr><td><b>Client</b></td><td>Milan Vlasić</td></tr>
  <tr><td><b>Industry</b></td><td>Real estate, licensed agent in New South Wales</td></tr>
  <tr><td><b>Location</b></td><td>Sydney, Australia and Belgrade, Serbia</td></tr>
  <tr><td><b>Type</b></td><td>Personal one-page website</td></tr>
  <tr><td><b>My role</b></td><td>Design, development, SEO, hosting and maintenance</td></tr>
  <tr><td><b>Stack</b></td><td>HTML, CSS, JavaScript, JSON-LD</td></tr>
</table>

## About the project

Milan Vlasić is a licensed real estate agent in New South Wales. He works from Sydney and handles property in Belgrade through local associates, so many of the people he helps live in one country and own property in the other. The first screen had to explain that link, the time difference and who to contact.

I put the current times in Sydney and Belgrade on that screen, with the gap between them. The gap is worked out from each zone's current offset, so it stays correct when either side moves to or from daylight saving time. The Serbian and English text live in the same HTML, and one button swaps them in place. The browser remembers the choice, but the site itself sets no cookies and tracks no one.

## What I built

- Live clocks for Sydney and Belgrade with the hour gap between them, built on Intl.DateTimeFormat with no library
- Serbian and English on one page, with the English text in data attributes and the choice kept in localStorage
- A profile section before the offer: the licence, the Sydney suburbs he has worked in and how he works
- Direct contact only, with a note on which channel works better from Australia and which from Serbia
- A line down the page that fills as you scroll, using CSS scroll-driven animation where supported and a small script elsewhere; it stays still under reduced motion
- Static HTML, CSS and JavaScript with no database, plus structured data for the agent and the site

## Results

| | Performance | Accessibility | Best practices | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Mobile | 100 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, lab test of the live site, September 2026. Security headers: 6 of 6. HTML validator: no errors. axe accessibility check: no violations. Structured data: `RealEstateAgent`.

## Screenshots

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Milan Vlasić, home page on a 1440 px screen"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Milan Vlasić, home page on a phone"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="The agent's personal profile, markets and way of working">
<sub>The agent's personal profile, markets and way of working</sub>

<img src="media/inner-2.webp" alt="The Australian side of the business and direct contact">
<sub>The Australian side of the business and direct contact</sub>

---

<sub>Built by [D. Svilenković](https://svilenkovic.com).</sub>
