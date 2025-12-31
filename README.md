# rules-us-ca

California statutes and regulations in Akoma Ntoso XML format.

## Structure

```
rules-us-ca/
├── statutes/
│   ├── rtc/           # Revenue and Taxation Code
│   └── wic/           # Welfare and Institutions Code
└── regulations/
    └── ccr/           # California Code of Regulations
```

## Format

All documents are encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML, an OASIS standard for legal documents. This enables:

- Structured representation of legal hierarchies (divisions, chapters, articles, sections)
- Semantic markup of definitions, cross-references, and amendments
- Machine-readable citations and temporal versioning

## Related Repositories

- [arch](https://github.com/CosilicoAI/arch) - Source document archive (downloads and parses official sources)
- [rac-us](https://github.com/CosilicoAI/rac-us) - US federal rules encoded in Cosilico DSL
- rac-us-ca (future) - California rules encoded in Cosilico DSL

## Sources

- **Revenue and Taxation Code**: [California Legislative Information](https://leginfo.legislature.ca.gov/faces/codes.xhtml)
- **Welfare and Institutions Code**: [California Legislative Information](https://leginfo.legislature.ca.gov/faces/codes.xhtml)
- **California Code of Regulations**: [Office of Administrative Law](https://oal.ca.gov/)

## License

Source materials are public domain government documents. XML encoding and tooling are MIT licensed.
