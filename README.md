<!-- tyhp-readme:start -->
# tyhpdef/justinrainbow-json-schema

Tyhp type definitions for `justinrainbow/json-schema` `6.12.0`.

```bash
composer require --dev tyhpdef/justinrainbow-json-schema:6.12.0
```

This is a metapackage. Composer also installs `tyhpdef/justinrainbow-json-schema-impl` (type files).
Require **this** name, not `tyhpdef/justinrainbow-json-schema-impl`.

See https://tyhplang.com.

## Maintain `justinrainbow/json-schema`? Ship the types yourself

If you are a Packagist maintainer of `justinrainbow/json-schema`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/justinrainbow-json-schema-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `justinrainbow/json-schema` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/justinrainbow-json-schema": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `justinrainbow/json-schema` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `justinrainbow/json-schema` with a real constraint,
   `"replace": { "tyhpdef/justinrainbow-json-schema": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `justinrainbow/json-schema` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/justinrainbow-json-schema` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
