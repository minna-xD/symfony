CHANGELOG
=========

6.4
---

 * Mark the component as non experimental
 * Add CSS support to the importmap
 * Add "entrypoints" concept to the importmap
 * Always download packages locally instead of using a CDN
 * Allow relative path strings in the importmap
 * Automatically set `_links` attribute for preload CSS files for WebLink integration
 * Add `PreAssetsCompileEvent` event when running `asset-map:compile`
 * Add support for importmap paths to use the Asset component (for subdirectories)
 * Removed the `importmap:export` command
 * Add a `importmap:install` command to download all missing downloaded packages
 * Allow specifying packages to update for the `importmap:update` command
 * Add a `importmap:audit` command to check for security vulnerability advisories in dependencies
 * Add a `importmap:outdated` command to check for outdated packages

6.3
---

 * Add the component as experimental
