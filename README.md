# download gitter archives

uses the gitter REST API to download archives of public gitter rooms.

Write your gitter API token to the file `token`, and run `./archive-gitter`.

Archives are stored in `archive/room/name.json`.

Subsequent runs check for new messages since last run.

License: CC-0, Public Domain
