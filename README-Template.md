# Wise Words Quote Generator

Wise Words is a quote generator application that pulls a random quote from the Type.fit API and displays a single quote on the UI. The user has two buttons available: one button for generating another random quote, and the other button to tweet the quote with the author on the user's Twitter account.

## Description

Wise Words displays a random quote from the API and inserts the quotes into an empty array. The quotes from the API are pulled using an async "try/catch" method, in which the JSON responses are inserted into the empty array. The "New Quote" button generates another random quote from the API's list of quotes using Math.random(), and displayed the author under the quote (displays "Null" if no author is specified). The button to tweet the quote uses is a template literal that uses Twitter's tweet button functional, in which I inserted the quote and author as expressions, so that any random quote and author could be posted to Twitter. Finally, there is a loader SVG that activates anytime there is a loading time between pulling a quote from the API or displaying the quote onto the UI. THe loader is then removed once the quote is displayed onto the UI and is only activated again once there is another loading time.

## Authors

David Ortiz-Alejandre
ortiz.david00@gmail.com

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [dbader](https://github.com/dbader/readme-template)
* [Type.fit Quote API](https://type.fit/api/quotes)
