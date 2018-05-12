# Irish resource grammar for Grammatical Framework

This is a partial resource grammar of Irish (ISO 639-1 `ga`, ISO 639-2 `gle`), written in [Grammatical Framework](http://www.grammaticalframework.org/). I would classify it as a "midi" resource grammar: its coverage is larger than the "mini" resource grammar from chapter 9 in the [GF book](http://www.grammaticalframework.org/gf-book/), but not large enough yet to qualify for membership in the GF resource grammar library.

This grammar lives in just a single resource module `ResGle.gf` and provides a more-or-less complete treatment of the "nouny" bits of Irish: nouns, adjectives, pronouns, noun phrases, prepositions. It has many gaps, including the complete absence of any treatment of verbs and clauses. Still, it should serve as a solid base for a full Irish resource grammar in GF, should someone decide to write one in the future.

There is also a concrete module `MiniresourceGle.gf` which "plugs" the resource module into the mini resource grammar found in the [miniresource](https://github.com/GrammaticalFramework/gf-contrib/tree/master/miniresource) folder in GF's GitHub repository. It also contains a quick and dirty workround for the lack of verbs in the resource module.
