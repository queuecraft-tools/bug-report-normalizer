# bug-report-normalizer

Normalize incoming bug reports into reproducible issue fields.

## Run

Requires Node.js 20+.

```sh
npm start
```

The tool reads its development gateway settings from `config/staging.env`. Override those values in your deployment environment before production use. Review generated output before applying it to another system.
