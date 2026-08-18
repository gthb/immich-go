Repro files for the immich-go issue "from-google-photos: when an `-edited` file is processed before its original, the original is skipped or the edited upload is force-deleted".

- `repro-takeout.zip`: a 4-file Google Takeout (two edited pairs, one per flavour, with their JSON metadata sidecars)
- `immich-go-run.log`: trimmed INFO log of a run of immich-go v0.32.0 on it against Immich v3.1.0
- `api-trace-excerpt.txt`: the relevant requests and responses from `--api-trace` for that run
