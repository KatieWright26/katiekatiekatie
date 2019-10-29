- Ruby is an Object Orientated language; onjects are created by classes.
- `irb` enables ruby developers to run and test their code, `irb --simple-prompt` keeps the console tidy and slightly easier to read.
- Basic operations in Ruby include arithmetic (+ - / * % etc), assignment (x = "Hello World"), comparison ("10" == 10) and conversion (x = "10".to_i)
- Basic input/ outputs include:
  -  `print`, `puts`, `p` to print values to the `irb` console. Note that `puts` adds a new line to the value, `print` only prints exactly what it is told.
  - `gets` will prompt a user to provide a string in the console. This string can be assigned by doing `string = gets`.
  - Conditional statements `(if x == y return puts 'Hello world')`
- Special Objects and Comments
  - the keyword `self` refers to a default object. Methods that don't specify a "calling object" are called on `self`
  - `#` at the start of a line defines a comment in the code
  - Objects `true`, `false` and `nil` are often used as return values inside conditional statement.

  Ruby Identifiers:
  - Variables
    - local: test_variable
    - instance: @test_variable
    - class: @@test_variable
    - global: $TEST_VARIABLE
  - Constants
  - Keywords
  - Method Names

- Ruby sees all data structures and values as objects.
- "A class defines an objects functionality, and every object is an instance of a class". Ruby comes with many classes already, such as _String_, _Array_ and _Integer_, but developers can create their own classes, or overwrite existing ones. A class _instansiates_ an object, it brings it into existance. However, an object can aquire its own methods and behaviours that were not defined in its class.

- we use the `ruby` interpreter to run programmes, e.g. `ruby well_grounded_rubyist/c2f.rb`
- the `ruby` interpreter can check for syntax errors without running the program by using the `-cw` flag, e.g `ruby -cw well_grounded_rubyist/c2f.rb`
