# Browser regression tests

Install Playwright in your test environment and run `node tests/safe-rendering.cjs`. Set `PLAYWRIGHT_MODULE` and `CHROMIUM_PATH` when using an existing installation. Tests serve the committed Worker assets locally and block third-party requests. Keyboard activation avoids layout dependence when the external CSS CDN is blocked.
