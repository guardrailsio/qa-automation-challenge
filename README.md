# QA Automation Engineer Challenge

> This repository contains the challenge for QA automation engineers.

- [Cypress Exercise](#cypress-exercise)
- [Integration Testing Exercise](#integration-testing-exercise)

**Note:** Please don't fork this repository, or create a pull request against it. Otherwise other applicants may take inspiration from it. Once the coding challenge is completed, you can submit it via this [Google form](https://forms.gle/f2hekWPJqee6htH28).

## Cypress Exercise

For the Cypress exercise, you will help us testing the [awesome OWASP Juice shop](https://juice-shop.herokuapp.com/).
You will have to test 3 different scenarios:

1. Login with your user, add 1 item to the basket, click on checkout, add a new address, fill in the address form, click on submit.
2. Exact same flow, but this time, add two items to your basket, click on checkout, add a new address, fill in the address form, click on submit.
3. Click on the search button, search for apple, verify that 2 apple products show up and that banana product doesn't show up

Please make sure your tests are running properly and we can easily test your work.

## Integration Testing Exercise

Great, now that you're done with Cypress, we would also want to ensure our APIs are doing their jobs correctly.
Still within the [awesome OWASP Juice shop](https://juice-shop.herokuapp.com/), find the APIs endpoints and test the following scenarios:

1. Sign in the user, add 1 item to the basket, verify that 1 item is in the basket
2. Same as previous scenario but add 2 items instead of 1 to the basket
3. Same as previous scenario but delete 1 item and validate that only 1 item remains in the basket

You can use the tool of your choice (Jest, Postman etc...), just make sure it is easy for us to run your tests.

## Scoring
| Cypress                | Points |
|------------------------|--------|
| ...                    | 0-5    |

| Integration   | Points |
|---------------|--------|
| ...           | 0-3    |
| ...           | 0-5    |

| General             | Points |
|---------------------|--------|
| README.md           | 0-2    |
| Commit messages     | 0-2    |

