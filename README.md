# strict-predicate

## Presentation

This lib is is primarily about validating untrusted data payload with the use of the `isStructuredData` functions.
The `isStructuredData` functions enforce complete validation of the data based on the expected type.
The type is the source of truth and the validation follow from the type, not the other way.

The lib also provide several functions to help both in building `isStructuredData` descriptor and to discriminate types in your own code.

Because NaN is usually an undesirable value, this lib assimilate NaN to a nullish value along with undefined and null.

## Getting started

```bash
yarn add strict-predicate
# or
npm install strict-predicate
```

## Documentation

- [TypeAssertion](docs/TypeAssertion.md)
- [TypeGuard](docs/TypeGuard.md)
- [TypeHint](docs/TypeHint.md)
- [Helper](docs/Helper.md)
