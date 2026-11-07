# Nameštaj Parametric — Manual QA Portfolio

Manual testing of a bilingual furniture e-commerce website built with WordPress and WooCommerce.

Website: https://namestajparametric.com/

## Project Background

I designed and developed this website based on requirements gathered directly from the client. I clarified the purpose of the website, product presentation, shopping functionality, language versions, and delivery timeline.

Alongside development, I manually tested the website to check functionality and consistency across the Serbian and English versions.

This repository documents that practical experience and contains QA documentation being prepared for my portfolio.

## My Role

- Clarified client requirements and translated them into website functionality.
- Designed and developed the Serbian and English versions of the website.
- Manually checked approximately 20 products and their available colour options.
- Tested navigation, shopping cart functionality, language switching, and catalogue links.
- Investigated issues, implemented fixes, and repeated checks after changes.

## Testing Scope

- Homepage and navigation
- Product pages and colour selection
- Shopping cart functionality
- Serbian and English language versions
- Currency display and conversion
- Catalogue links
- Desktop and mobile layouts

## Example of an Issue Found and Resolved

### Incorrect price conversion when switching languages

During testing, I found that a product priced at EUR 400 on the English version appeared as RSD 400 after switching to Serbian. The currency label changed, but the price was not converted.

**Expected behaviour:** The price should be converted using the configured exchange rate and displayed in the appropriate currency.

**Action taken:** I configured currency-conversion plugins and repeated checks across both language versions.

**Outcome:** After the fix, the prices converted correctly during my follow-up testing.

This is a retrospective description of an issue resolved during website development, rather than a currently open defect.

## Portfolio Documentation

Documentation is being added to this repository:

- Test cases with steps and expected results
- Test execution results
- A retrospective bug report for the currency-conversion issue
- Screenshots supporting newly executed tests
- A test summary describing coverage, findings, and limitations

## Technologies and Platform

WordPress, WooCommerce, Elementor, GitHub

## Author

Jelena Milovanović
