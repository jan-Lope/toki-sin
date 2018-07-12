# toki-sin

## Rationale

Ideas about a new simple language

It is possible to develop a language that is simpler than Esperanto and Toki Pona and yet can serve for simple communication?

To develop this language, it should be done from the beginning and synchronously with one (or more) parser. This can be done in prolog and/or another programming language. Only sentences that pass the parser test are correct sentences.
We could (at the same time) also go the other way: have a semantic representation and parse/generate between that and the language. Eg Conceptual Dependency theory.
We use different ways to build this language. In the first phase we can adopt words and some grammar from Toki Pona. We should compile what are the advantages and disadvantages of Toki Pona (or Esperanto).

## Aims

* This language serves for simple communication without claiming to be a world auxiliary language.
* It is not the aim of this language to describe complex contexts.
* Daily phrases should be possible, such as weather, time, menu, directions, hotel, taxi,...
* This language should not be a dialect or further development to Toki Pona. This language should not compete with Toki Pona. 
* remove inconsistencies from Toki Pona (such as "no _li_ after _mi_ and _sina_"). As a result, the grammar has to be simpler than Toki Pona. 
* Easy analysis and generation by computer.

## Problems with Toki Pona

* Inconsistencies
* Mistakes and inaccuracies in book
* Unnecessary exceptions (no _li_ after _mi_)
* No distinction between quantities and sizes (lili).
* Word types are often not clearly recognizable. This applies in particular to prepositions.
* "Innovations" usually contradict the rules.
* The use of typesetting and other special characters is often incorrect.
* ...

## Problems with Esperanto
* Many special characters, pronunciation not easy
* International words are difficult to integrate, as there are rigid rules for word endings.
* With compound words, the original words are not always easy to recognize.

## Changes/Properties of toki-sin

* Syntax: Fixed constituent order SVO, simple sentences only.
* Equivalent of predicate _to be_. Proposal: _sama_ -- _waso li sama lili_ meaning “the bird is small”?
* The number of words should be limited to less than 500. More like even less. There should be very good reasons to add new words.
* Morphology: Toki Pona does without, Esperanto has very regular morphology. Should be able to do without.
* Prepositions should be clearly visible.
* Clear identification of numbers.
* The use of punctuation marks and other special characters should be clearly defined.

## Strategy
* Create a wortlist with only one (proxy) word for each word type (noun, preposition, trans verb, intr. verb, ...) 
* Create gramars rules and program the parser(s). Beginning with the type of sentences - see also https://github.com/jan-Lope/Toki_Pona-Parser/blob/master/toki-pona-grammar-rules.pro

