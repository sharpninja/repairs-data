# repairs-data

Published data for the [Repairs](https://github.com/sharpninja/repairs) app.

The app reads `marketplace.json` from the **`approved`** branch directly:
`https://raw.githubusercontent.com/sharpninja/repairs-data/approved/marketplace.json`

Community submissions arrive as **pull requests against `approved`**. The submit
service (see the app repo's `server/`) opens and Claude-moderates them; merging a
PR publishes the change to what every app instance reads. Do not hand-edit outside
of reviewed PRs unless you know what you're doing.
