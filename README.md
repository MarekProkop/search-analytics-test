# Search Console API - Search Analytics Data Consistency Test

[Google Search Console API](https://developers.google.com/webmaster-tools/search-console-api-original) and especially it's [Search Analytics](https://developers.google.com/webmaster-tools/search-console-api-original/v3/searchanalytics) is quite popular in marketing world. Some marketers and analysts use it directly and even more of them use it through another tools, such as [Google Data Studio](https://datastudio.google.com/), [Search Analytics for Sheets](https://searchanalyticsforsheets.com/) etc.

People often expect the API provides consistent data that always sum up to the same grand totals, regardless of chosen dimensions, but it is not true. The API has some "special features", which makes results rather inconsistent, and only some of them are properly documented.

The purpose of this Analysis is to examine behavior of Google Search Console API and in particular *search_analytics* function from Mark Edmondson's searchConsoleR package. The reason is to document exact impact of dimension combination on the resulting data.

