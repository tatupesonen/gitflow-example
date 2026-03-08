The release branch facilitates the transition from the Develop branch to the Main (Production)
branch. It is branched off from develop once the project has reached the desired state for a new
version. ​

Its primary function is to provide a dedicated environment for release preparation, allowing for final
polish without halting ongoing feature development. No new features are merged into this branch,
and the scope is strictly limited to bug fixes, documentation updates, and minor metadata
adjustments (e.g., version upgrade).​

Once the release branch is deemed stable, it is merged into the main (formerly master) branch and
tagged with a version number (e.g., v1.4) to mark a formal release point. To ensure that any fixes
applied during the release phase are preserved, the branch is also merged back into develop.​
