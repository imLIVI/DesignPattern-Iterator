# DesignPattern-Iterator
## Infinity Iteration
### Description
In this task, we will practice with the Iterator template.

We need to write a class that extends ```Iterable<Integer>```, by which we will integrate. In the iteration process, we will receive random numbers from it in a range of
values. The range is set by two numbers - the minimum and maximum values. They are passed through the constructor parameters. Thus, the iterator over the objects of our
class will iterate over an infinite sequence of random numbers in a given interval.

1. Create the ```Randoms``` class
2. Implement the ```Iterable``` method required by the interface, for which you may need to create an auxiliary class for the iterator (implementing ```Iterator<Integer>```)
for your class.
3. To generate random numbers, use the built-in ```Random```class.
4. Create the ```Main``` class, demonstrate the operability of the class you wrote
5. Test the operation of the program
