### v0.2.2 (in development)

### v0.2.1 (2020-05-10)

- [feature] Added support for embedded schemas.
- [feature] Added support for `:map` fields for json values.
- [enhancement] Use the json library configured for phoenix instead of hardcoding `Jason`.
- [bugfix] Don't crash when the schema has a `has_many` or `has_one` association.
- [bugfix] Don't crash when the schema has a map field or an embedded schema.

### v0.2.0 (2020-05-09)

- [enhancement] Kaffy now supports phoenix 1.4 and higher.
- [breaking] The `:otp_app` config is now required.
- [enhancement] Removed some deprecation warnings when compiling kaffy
- [enhancement] Massively simplified configurations. The only required configs now are `otp_app`, `ecto_repo`, and `router`.
- [feature] Kaffy will now auto-detect your schemas and admin modules if they're not set explicitly. See the README file for more.

### v0.1.2 (2020-05-08)

- [enhancement] Much improved UI.
- [enhancement] Some code cleanups.

### v0.1.1 (2020-05-07)

- [enhancement] Removed the dependency on `:jason`.
- [bugfix] Changed `plug :fetch_live_flash` to `plug :fetch_flash` for the default pipeline.