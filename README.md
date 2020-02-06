# Design Questions

* Do you know what the SOLID principles are?
   * If so, can you list them?
   * What do each of the principles mean?

* What is coupling?
   * What are some symptoms of coupling?
   * How do you eliminate coupling?

* What are the main three features of Object Oriented Programming?
   * What are the benefits of each?

* What is composition?
   * What are the benefits of composition?

* What is Dependency Injection?
   * How is it different from Dependency Inversion?

* What is the importance of PSRs and the PHP-FIG?
   * What are your favorite PSRs?
   * Can you explain what autoloading is?  (PSR-4)


# Calculator Questions

## Project Requirements/Dependencies

* How much experience do you have working with PHP7?
   * What was the reasoning behind the requirement of PHP 7.1 in your calculator?
   * Why did you depend on phpunit `8.5.x-dev`?

* Should you commit the `composer.lock` file?

## Project Design Questions

* Show us how you would add the modulo operator to your calculator.

* How would you extend your calculator to support a subscription based model
  for operators?  For example, if the business wanted to charge extra for the
  modulo operator, but give addition, subtraction, multiplication, and division
  for free, how would you extend your calculator to support the new
  requirements?
