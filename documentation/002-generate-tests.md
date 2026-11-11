1.
Use the codegen command to run the test generator followed by the URL of the website you want to generate tests for. The URL is optional and can be added directly in the browser window if omitted.

npx playwright codegen demo.playwright.dev/todomvc
----------------
2.
npx playwright test --debug
npx playwright test example.spec.ts --debug
npx playwright test example.spec.ts:10 --debug
-----------------------