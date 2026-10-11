# Publish this GitHub profile

1. Open the public repository named `the-sparsh-shukla` under your account.
2. Upload `README.md`, the complete `assets/` folder, and `.github/workflows/snake.yml` from this package. Keep the paths unchanged.
3. Commit the changes to your default branch (`main` or `master`).
4. In the repository, open **Settings → Actions → General** and make sure actions are allowed. Under **Workflow permissions**, select **Read and write permissions** if your repository settings expose that option, then save.
5. Open the **Actions** tab, select **Generate contribution snake**, and click **Run workflow**. Wait for the run to finish successfully.
6. After the workflow succeeds, check the `output` branch for `github-contribution-grid-snake-dark.svg`.
7. Visit https://github.com/the-sparsh-shukla and check the rendered profile on desktop and mobile. If the snake image is still missing, open the failed workflow run and read the error log; the image cannot appear until the workflow publishes it.

## Notes
- The contribution grid inside `assets/id-dashboard.svg` is decorative artwork, not live contribution data. Live stats and activity are separate cards below it.
- GitHub may not render every SVG animation exactly as a browser does.
- External stats cards depend on their service being available.
- The generated character is illustrative artwork and is not based on a reference photo.


## Broken activity graph note

The third-party `github-readme-activity-graph.vercel.app` image was removed because it was failing to load in the profile screenshot. The profile keeps the GitHub stats cards and generated contribution snake instead. External stats providers can still have outages or rate limits.
