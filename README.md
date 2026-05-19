sp26-cse110-lab7

1. I would choose 'Within a GitHub Action that runs whenever code is pushed" because it picks up on regressions early on. It also allows the whole team immediate feedback, and keeps main stable without depending on everyone remembering to run tests locally.

2. No because unit tests are better for returning the correct output than E2E. Since E2E tests are for full user workflows across the UI, browser, and app behavior.

3. Navigation mode: audits page load from a navigation and measures load-time performance metrics.
   Snapshot mode: audits the current page state at one moment. It is good for accessibility but not full load behavior.

4a. Minify and reduce unused JavaScript to shrink the JS bundle
4b. Improve caching and loading strategy for static files by using longer cache lifetimes and reducing render-blocking requests
4c. Fix basic accessibility / SEO metadata by adding a lang attribute on <html> and a meaningful <metaname="description">.
   