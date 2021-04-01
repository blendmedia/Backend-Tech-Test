## Backend Engineer - Technical Test

The following test is used to give us an idea of your technical style and ability. Please use Elixir/Phoenix to complete the test if possible. If you don't know Elixir yet, then any other backend language that you are familiar with is also good. 

### The exercise

The exercise requires you to build a simple web application which fulfils the following criteria:

* **Ingests a few simple CSV files** - Use the URL [here](https://data.police.uk/) to access the open Police Data website. Use the Downloads section to create a reasonable sized data set in the order of 50k-100k rows, which should download in the form of a folder containing several CSV files. We recommend you stick to one police force, and somewhere between 6-9 months; bear in mind that this will be thousands, if not tens of thousands of rows. You should import the generated CSV files into a database of your choice, and store them however you see fit.
* **API that fetches the data** - Create an API that we can use to fetch the data in a json format with support for simple sorting and filtering on one or more of the fields.
* **Shows an understanding of unit/integration testing** - We use TDD on our backed code, so we would also like to see the automated tests for the code that you write.

### Submission

To submit your solution, please either:

* Put the code under source control, publicly host the repository on Github, and provide us a link, or
* Email us a ZIP file including everything we would need to run it (excluding the downloaded data) to work@blend.media.

Once we receive your submission, we will try to re-run it locally, and take a look at your code style so that we can discuss your solution in the interview.

Good luck!
