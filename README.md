# Notation 3 (N3) grammar

The Notation 3 (N3) grammar written in [ANTLR4](https://github.com/antlr/antlr4). If you prefer [Extended Backus-Naur Form (EBNF)](https://www.w3.org/TR/REC-xml/#sec-notation) notation, you can also see [N3 grammar in EBNF](https://github.com/lszeremeta/n3/blob/master/other-notations/N3.ebnf).

[Notation 3 (also known as N3)](https://www.w3.org/TeamSubmission/n3/) is an assertion and logic language which is a superset of RDF. N3 extends the RDF datamodel by adding formulae (literals which are graphs themselves), variables, logical implication, and functional predicates, as well as providing an textual syntax alternative to RDF/XML.

This project based on [ANTLR grammars-v4 project](https://github.com/antlr/grammars-v4).

## Testing grammar

Run tests on files in ``n3/examples``:

```shell
mvn clean test
```

## Contribution

Would you like to improve this project? Great! We are waiting for your help and suggestions. If you are new in open source contributions, read [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/).

## License

Distributed under [BSD license](https://github.com/lszeremeta/n3/blob/master/LICENSE).
