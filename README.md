# QAuto Guest Garage Playwright Tests

This repository contains the Playwright tests in `tests/guest-garage.spec.ts`.

## Scenarios

- **Guest opens Garage:** logs in as a guest, then checks that the URL contains `/panel/garage` and the `Garage` heading is visible.
- **Guest adds an Audi TT:** logs in as a guest, adds an Audi TT with mileage `12000`, then checks that `Audi TT` appears in Garage.

## Run the tests

From the repository root, run the test with the Playwright command configured for your project. A typical command is:

```bash
npx playwright test tests/guest-garage.spec.ts
```

## Latest result

The repository owner reported that both tests passed in their latest run. This result is user-reported; no run output is stored in this repository to independently verify it.

## View a trace

If Playwright generated a trace archive for a test, open it in Trace Viewer with the path shown in the test output:

```bash
npx playwright show-trace test-results/<test-name>/trace.zip
```

The archive is usually generated when tracing is enabled in the Playwright configuration.
