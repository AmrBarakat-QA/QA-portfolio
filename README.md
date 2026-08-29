# Manual Testing – SauceDemo (Login Module)

Manual testing project focused on the login functionality of [saucedemo.com](https://www.saucedemo.com), a demo e-commerce site used for QA practice.

## What I Did
- Designed and executed 10 test cases covering the login flow: valid credentials, invalid username/password, empty fields, locked-out users, and edge cases like whitespace handling
- Compared expected vs. actual results for each test case and logged pass/fail status
- Found 1 bug: entering a username with a trailing space fails login instead of succeeding, with an unclear error message (see TC009)

## Results
- 9 Passed / 1 Failed
- Bug found: **TC009 – Login with trailing space in username** — expected the user to log in successfully, but got a "username and password don't match" error instead

## Skills Demonstrated
- Manual test case design (positive, negative, and edge cases)
- Boundary/edge case testing (whitespace handling)
- Bug identification and documentation
- SDLC/STLC fundamentals

## Files
- `First_Manual_testing_proj.pdf` – Full test case documentation with steps, expected/actual results, and status
