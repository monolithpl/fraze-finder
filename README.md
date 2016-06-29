# fraze finder
Highlight collocations, chunks, idioms, phrasal verbs and semi-fixed lexical phrases in texts. Perfect for building collocation awareness in ESL students. Analyze your text for chunks [here](http://monolithpl.github.io/fraze-finder/)

### features
- highlights and lists chunks in a given text
- very fast lookups using a slightly modified version of [Steve Hanov's succinct bit string trie implementation](http://www.hanovsolutions.com/trie/Bits.js)
- fully client-side and portable - works offline, too!
- zero framework rubbish - pure vanilla javascript with zero overhead - tiny code with zero external dependencies
- responsive mobile-first layout

### demo
[check it out here](http://monolithpl.github.io/fraze-finder/)

### further reading
Read up on the usefulness of teaching chunks / collocations in EFL classrooms here:
- [Why has the lexical approach been so long in coming?](http://www.theguardian.com/education/2013/mar/26/leixical-approach-revolution)
- Seth Lindstromberg: [Teaching Chunks of Language](http://www.hltmag.co.uk/dec08/idea.htm)
- [Lexical Approach](https://en.wikipedia.org/wiki/Lexical_approach)
- [Optimizing a Lexical Approach to Instructed Second Language Acquisition](http://www.victoria.ac.nz/lals/about/oldnews/attachments/VUW_seminar.ppt)

### implementation details
Read more about performance-first string lookups in javascript using trie-s here:
- [Succinct Data Structures: Cramming 80,000 words into a Javascript file](http://stevehanov.ca/blog/index.php?id=120)
- [John Resig's Revised JavaScript Dictionary Search](http://ejohn.org/blog/revised-javascript-dictionary-search/)

MIT License

Copyright 2016 Wiktor Jakubczyc
