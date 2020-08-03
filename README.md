# what-I-learned-in-week-11

## node
### __dirname
- return the string of the absolute path
- to target file not in the current directory, use '/..'


## object

### method

- Methods: the actions that can be performed on objects.
- primitive value : a value that has no properties or methods.

- this
1. The value of this is the object "before dot", the one used to call the method.

2. The value of this is evaluated during the run-time, depending on the context.

- method callback for array

1. map: Array.prototype.map() creates a new array populated with the results of calling a provided function on every element in the calling array.

2. filter:Array.prototype.filter() method creates a new array with all elements that pass the test implemented by the provided function.

## From assignment

- when moving all values to a different index, iterate the elements in a reverse direction comparing to the moving direction. Otherwise, the original values will be replaced by a repeating value.  