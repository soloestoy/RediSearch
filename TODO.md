## Upcoming features:

* Deletion support
* Update support
* Drop index support
* Optimize buffer sizes (truncate to actual size at end of indexing)
* Search specific fields
* Custom user flags filtering
* Boolean expression parsing
* Intersect inverted and ZSETs - allowing numeric/geo filtering
* Proper unicode support (currently we assume input is utf-8)
* Query expansion
* Fuzzy matching
* Auto-suggest / speller
* Index HASH values
* Index json values
* Doc Snippets retrieval
* Query Explain

## Known bugs:

* intersect doesn't return last result if it's the end of the index