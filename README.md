Expectation Matchers
  equivalence matchers
    will match loose equality with #eq
    will match value equality with #eql
    will match identity equality with #equal
  truthiness matchers
    will match true/false
    will match truthy/falsey
    will match nil
  numeric comparison matchers
    will match less than/greater than
    will match numeric ranges
  collection matchers
    will match arrays
    will match strings
    will match hashes
  other useful matchers
    will match strings with a regex
    will match object types
    will match objects with #respond_to
    will match class instances with #have_attributes
    will match anything with #satisfy
  predicate matchers
    will match be_* to custom methods ending in ?
    will match have_* to custom methods like has_*?
  observation matchers
    will match when events change object attributes
    will match when events change any values
    will match when errors are raised
    will match when output is generated
  compound expectations
    will match using: and, or, &, |
  composing matchers
    will match all collection elements using a matcher
    will match by sending matchers as arguments to matchers
    will match using noun-phrase aliases for matchers
