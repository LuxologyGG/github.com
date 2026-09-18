# MIDEAST 200 map quiz

This separate `map-quiz` branch leaves the repository's existing `main` branch unchanged.

## Complete exported files

- [Website files, editable React source, tests, and offline HTML (ZIP)](https://d2ol7oe51mr4n9.cloudfront.net/user_3HFx6o6vuYL5mZ9Cq923VjpCjEa/5cf62320-8ea5-4a3b-beb7-7b01fbecfce7.zip)
- [Standalone, self-contained quiz](https://d2ol7oe51mr4n9.cloudfront.net/user_3HFx6o6vuYL5mZ9Cq923VjpCjEa/3c6e0254-6b0f-42e6-bfd2-d063dd8e57a1.html)

The ZIP SHA-256 is `0761bc3da1d9fdbfd010facda5ce185f45f8b013ddd9af92bccf95a3978d265a`.

The exported website uses local bundled React, local map images, and browser-local progress. It has no authentication, external runtime, backend, or Higgsfield API. Regional practice targets are approximate label-centered zones rather than exact geographic boundaries.

## Verification

The exported build passed 12 unit tests (228 assertions). An anonymous local browser completed all 30 map-click questions correctly, with no external requests or runtime errors. The self-contained HTML also opened from a file URL and started a quiz without a server.

## GitHub deployment status

The import workflow was created and triggered, but GitHub did not start the job. Its annotation reports: `The job was not started because your account is locked due to a billing issue.`

[Failed run and annotations](https://github.com/LuxologyGG/github.com/actions/runs/35295937793)

The full files are available in the export above; they have not yet been imported into this branch because the workflow was blocked before execution. After resolving the GitHub account lock, rerun the failed import job. It verifies the export checksum and adds `docs`, `map-quiz-source`, and the offline HTML to this branch without replacing existing files.

Then use repository **Settings > Pages > Deploy from a branch > map-quiz > /docs > Save**.

The site is not yet live on GitHub Pages. No billing settings or existing website files were changed.
