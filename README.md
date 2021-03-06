# _Question Impossible_

#### _This webpage allows users to post questions and answers to those questions_

#### By _**Erica Wright**_

## Description

This webpage allows users to post questions that are difficult to answer in a challenge to stump any visitors. Visitors can post answers in an attempt to resolve the question and visitors can vote on answers. If no one can answer a poster's question, the poster is crowned a master Trickster.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Bower](https://bower.io/)
* [Ember CLI](https://ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone https://github.com/ericaw21/question-impossible>` https://github.com/ericaw21/question-impossible
* `cd question-impossible`
* `npm install`
* `bower install`
* `ember install emberfire`
* `ember install ember-bootstrap`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

## Specifications

|*Behavior*|*Output*|
|----------|--------|
|User selects "Add Question"|Question is saved and posted with its own page created: "Why do snakes scare the crap out of me? by scaredy-cat, 2017-03-20"|
|User selects to update question| Question is updated on page and database "Why do snakes freak me out?"|
|User selects to delete a question|Question is deleted from webpage and firebase database|
|User selects to submit an answer|Answer posted on individual question page: "Because you're a mouse, by smarty-pants, 2017-03-21"|
|User selects to update answer| Answer is updated on page and database "Because you're a field mouse"|
|User selects to delete an answer|Answer is deleted from webpage and firebase database|
|User clicks "right" or "wrong" button next to answer|Tally of right and wrong guesses is updated|


## Support and contact details

_Please contact ericaw21@gmail.com for questions or concerns._

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

## Technologies

* _Javascript_
* _jQuery_
* _Node_
* _Ember_
* _CSS_
* _HTML_

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)

## License

*MIT License*

Copyright (c) 2017 Erica Wright All Rights Reserved.
