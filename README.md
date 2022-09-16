# TopLoader Baseball Data Repository

The TopLoader Baseball Data Repository (TLBDR) was created to provide structured data around baseball trading.  Surprisingly, there seems to be no up-to-date resource online that meets our key criteria:

## 1. Open License

There are other sources of data, but they either explicitly prohibit usage off their website or don't offer any kind of license at all.  TopLoader wants to make sure that this data is available to the whole hobby to make innovation easier.  By licensing the data with [Creative Commons Zero](https://creativecommons.org/share-your-work/public-domain/cc0/) we place no restrictions on how you can use, access, store, publish or copy the data.  Note that this does NOT grant you permission or protection to use the data where it is owned by other sources, like team and player names, and restrictions may vary by jurisdiction.  Consult the license for more information, but rest easy that we will never assert any rights over the data.

## 2. Machine-Readable

If you want to build your own app or spreadsheet or anything else, you need to be able to import the data.  TLBDR offers data in a number of popular formats that should make using it easy in any language or framework.  This includes:

1. CSV
2. TSV
3. XML
4. JSON

We also offer PDF checklists that are designed for printing, and can be handy when sorting cards.  If you have ideas for other useful formats, create an issue on this GitHub repo.

## 3. Well-Structured

The last feature that is lacking in other data sets is a strict and consistent structure.  This may not matter much to humans who are printing out lists or copying them into spreadsheets, but to an application or database, this is critical.  The schemas are documented across all of the formats, and the data itself is normalized.

# FAQ

1. What about other sports?

Other sports are coming, but we want to get things right before we move onto them.  None of our tools or schemas are intended to be baseball-specific, so anything built to use them should carry over.

2. Where are the photos?

Photos are important, and on the roadmap, but will take time to gather, as we are not copying from other sources without permission.  If you have photos to contribute, contact us at contribute@toploader.cards.

3. Where are the prices?

This database is intended to be a reference data source, not a real-time one.  If you want to build a pricing service, you can use this data to establish the cards to track, and then pull in the data from other sources.

4. How can I help?

We're looking for people to contribute data as well as verify the data we have.  We don't have a specific process in place yet, but contact us at contribute@toploader.cards with how you'd like to help and we'll find a way to make it work!
