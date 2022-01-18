# helloworld

Git flow and ci depend on robot

## Instrument

### Cherry-Pick

Add comment in pr like: `/cherry-pick release/1.2 release/1.1 release/1.0`

### Approve

Add comment in pr: `/approve`.

Bot will auto add `approved` label and try to merge continuously until pr can be merged(all checks passed).

### Assign

Add comment in pr like: `/assign @sfwn sfwn effet` (with or without `@` is both supported)

Bot will auto add specified users as pr reviewers.
