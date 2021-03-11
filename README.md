# Sentry Volume Test

Sentry Volume Test is an application for testing whether [sentry.io](https://sentry.io) is receiving errors and transactions.

You can use this application in one of two ways. You can use it to just test a Sentry account using the **Change DSN** function, without making any changes to the codebase. Or you can fork this repository, change the DSN of the application permanently, and test other changes to the application. The Installation and Usage sections of this readme file cover both options.

## Installation

Test Drive (No Code Changes)

1. Go to [sentry.io](https://sentry.io) and create an account.
1. Create a JavaScript project.
1. Navigate to the **Issues** page of the project and click the gear-wheel icon next to the project name to access the project settings.
1. Locate and copy the DSN.

Choose Your Own Adventure (Fork & Edit)
1. Fork this repository. If you don't have a place to host it, you can do so on your own [GitHub Pages site](https://pages.github.com/).
1. Go to [sentry.io](https://sentry.io) and create an account.
1. Create a JavaScript project.
1. Navigate to the **Issues** page of the project and click the gear-wheel icon next to the project name to access the project settings.
1. Locate and copy the DSN.
1. In the `index.html` file, change the DSN to your own project DSN on lines 21 and 85.

## Usage

Test Drive (No Code Changes)

1. Go to [imatwawana.github.io](https://imatwawana.github.io/).
1. Enter your DSN in the field and click **change**.
1. Click any of the buttons under **Send Errors** or **Send Transactions**.
1. Check the **Issues** or **Performance** page of your Sentry account to see the errors or transactions tracked there.

Choose Your Own Adventure (Fork & Edit)
1. Go to your GitHub Pages site.
1. Click any of the buttons under **Send Errors** or **Send Transactions**. 
1. Check the **Issues** or **Performance** page of your Sentry account to see the errors or transactions tracked there.

```

## Contributing
Please fork this repository to make changes to the codebase for your own Sentry account.
