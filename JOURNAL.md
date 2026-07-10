## Week 7 — Issue selection

**Issue link:** https://github.com/jamjamgobambam/pathreview/issues/104

**Issue title:** ProfileForm submission test doesn't assert that the loading state is shown

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
The existing test for the ProfileForm submission verifies that the form submits correctly, but it does not check whether the loading state is displayed during the submission process. This means the test could miss regressions where users receive no visual feedback while waiting for the request to complete. A successful fix will add assertions to verify that the loading state appears during form submission, improving the reliability of the test.

**Selection reasoning ("Is this right for me?"):**
I chose this issue because it has a well-defined scope, focuses on improving an existing test, and is appropriate for a first contribution. It only requires understanding the ProfileForm component and its tests rather than making broad changes across the codebase.

**Branch name:** fix/104-profileform-loading-test

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger