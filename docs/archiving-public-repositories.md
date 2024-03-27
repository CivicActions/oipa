GitHub has an archived repositories feature to indicate and make unmaintained repositories read-only. You can pair this feature with an automated report that gives you a list of the inactive repositories that are in your organization. Check out that action on the [GitHub Marketplace](https://github.com/marketplace/actions/stale-repos).

In order to archive a github organization repository:

1. Edit the README to add a note:

   ```md
   **NOTE**: _This repository is no longer supported or updated by CivicActions. If you wish to continue to develop this code yourself, we recommend you fork it._</code>
   ```

2. Then open a pull request with that change. Here's the text we've been using for the pull request:

   ```md
   This repository is no longer being maintained. This pull request makes it explicit in the `README.md`. Let me know if you have any reservations, otherwise I'm going to archive this repository.

   /cc any relevant teams or recent CivicActions committers
   ```

3. Let it sit until you receive confirmation from a maintainer or an adequate length of time has passed.

4. Close all open issues and pull requests and archive the repository from the repository settings.
