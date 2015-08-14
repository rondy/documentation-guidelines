# Documentation

* Use [TomDoc](http://tomdoc.org/) specification.
* Why code documentation matters?
* What to document?
  * Document atypical code.
  * Document decisions that future people will want to know about.
  * Document data that obscure by its own nature (`DateTime` formatters, `Regexp`, ...)
* Good practices.
  * Do not hesitate to provide input/output examples.
    * Avoid generic values or values that don't belong to the business domain. 
    * It will make people to gently get comfortable with the business domain.
    * People will end up getting a real sense of what your system is really about.
  * Stick to the patterns.
    * 80 column size.
    * Description sentence with imperative-capitalized verb.
    * Indentation.
  * Avoid to describe how something was implemented.
    * Plain comments are usually a hint that you should refactor a piece of code.
* Documentation tips.
  * Documenting constants.
  * Documenting object accessors.
  * How to come up with good title sentences.
  * Documenting method purpose.
* I have never written any word of documentation. Where should I start from?
    * In a Rails application, consider documenting your helpers at first.

#### Future topics

* On documenting JavaScript code.
