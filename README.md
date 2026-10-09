# SF Law Firm Contacts: Union Square & Financial District

`sf_law_firms_contacts.csv` lists law firms in Union Square and the Financial District rated above 4 stars on Yelp, with published attorney emails where they could be found.

## How it was built (Oct 2026)
- **Ratings:** Yelp search snapshots. Google Maps couldn't be reached from the research environment. Ratings and review counts change, so recheck before outreach.
- **Emails:** mostly from State Bar of California attorney profiles (apps.calbar.ca.gov) and directory listings. CalBar pads its email field with decoy addresses, so the address used is the one on the firm's own domain. Each row is marked **Medium** confidence. Confirm on the firm's website before sending.
- **NOT FOUND:** no published email was found. The phone number and website are given so you can use the firm's contact page.
- No email addresses were guessed from naming patterns.

## Gaps
- This is not a complete list. The Financial District has hundreds of firms, including large BigLaw offices that have few or no Yelp reviews.
- Also seen on Yelp at 4.8+ but no contact found: Law Offices of John E. Cowan (100 Pine), Douglas Greenberg (201 Spear), Law Offices of Daniel Vega (201 Spear), Sweet Lawyers (388 Market), Andrei Romanenko (500 Sutter), Cary Schneider (580 California, 4.7).
