# fraze-finder
Highlight collocations, chunks, idioms, phrasal verbs and semi-fixed lexical phrases in texts. Perfect for building collocation awareness in ESL students. Analyze your text for chunks [here](http://monolithpl.github.io/fraze-finder/)

### features
- highlights chunks in a given text
- very fast lookups using [Steve Hanov's succinct bit string trie implementation](http://www.hanovsolutions.com/trie/Bits.js)
- fully client-side and portable - works offline, too!
- zero framework rubbish - pure vanilla javascript with zero overhead
- tiny code with zero external dependencies (no jquery or react = 15k !)
- responsive mobile-first layout

### demo
[check it out here](http://monolithpl.github.io/multithesaurus/)

### implementation details
Read more about performance-first string lookups in javascript using trie-s here:
- [Succinct Data Structures: Cramming 80,000 words into a Javascript file](http://stevehanov.ca/blog/index.php?id=120)
- [John Resig's Revised JavaScript Dictionary Search](http://ejohn.org/blog/revised-javascript-dictionary-search/)

MIT License
