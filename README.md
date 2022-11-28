<h1 align="center" style="text-align: center">
    <img alt="42Lausanne" title="42Lausanne" src="https://github.com/MarJC5/42/blob/main/42_logo.svg" width="140"> </br>
    Project n°14 - ft_containers
    <h4 align="center" style="width: 50%; margin: 2rem auto; font-weight: normal; text-align: center"> 
     The many containers of C++ have various interests. In order to fully understand them, we are going to re-implement them!
    </h4>
</h1>

## What is a container ?

A container is an object that stores other objects. It is a data structure that groups elements together. It is a way to store data in a way that is easy to access and modify. Containers are used to store data temporarily, and are used in many different situations. They are used to store data in memory, to pass data between functions, and to perform operations on data.

## 📝 Table of Contents

- [What is a container ?](#what-is-a-container-)
- [📝 Table of Contents](#-table-of-contents)
- [Where to start to understand the project?](#where-to-start-to-understand-the-project)
- [📦 Vector](#-vector)
  - [Step to implement a vector](#step-to-implement-a-vector)
- [📦 Map](#-map)
  - [Step to implement a map](#step-to-implement-a-map)
- [📦 Stack](#-stack)
  - [Step to implement a stack](#step-to-implement-a-stack)
- [Iterator](#iterator)
- [Others implementations](#others-implementations)

## Where to start to understand the project?

- [C++ Containers](https://www.cplusplus.com/reference/stl/)
- [C++ Iterators](https://www.cplusplus.com/reference/iterator/)

## 📦 Vector

The vector is a container that encapsulates dynamic size arrays. It is very similar to an array, but it can grow and shrink in size.

### Step to implement a vector

- [ ] Create a vector class that encapsulates a dynamic size array
- [ ] Create a vector iterator class (bidirectional)
- [ ] Create a vector reverse iterator class (bidirectional)
- [ ] Create a vector const iterator class 
- [ ] Create a vector const reverse iterator class 
- [ ] Create a vector capacity function
  - [ ] size
  - [ ] max_size
  - [ ] resize
  - [ ] capacity
  - [ ] empty
  - [ ] reserve
- [ ] Create a vector element access function 
- [ ] Create a vector modifiers function
  - [ ] assign
  - [ ] push_back
  - [ ] pop_back
  - [ ] insert
  - [ ] erase
  - [ ] swap
  - [ ] clear
- [ ] Create a vector operations function (non-member function)
- [ ] Create a vector allocator function
- [ ] Create a vector non-member function overloads 
- [ ] Create a vector relational operators overloads
- [ ] Create a vector swap function (non-member)

## 📦 Map

The map is a container that encapsulates a dynamic associative array. It is very similar to a dictionary, where each element has a key and a value.

### Step to implement a map

- [ ] Create a map class (with a binary tree) that encapsulates a dynamic associative array 
- [ ] Create a map iterator class (bidirectional)
- [ ] Create a map reverse iterator class (bidirectional)
- [ ] Create a map const iterator class 
- [ ] Create a map const reverse iterator class 
- [ ] Create a map capacity function 
  - [ ] empty
  - [ ] size
  - [ ] max_size
- [ ] Create a map element access function (operator[]) 
- [ ] Create a map modifiers function 
  - [ ] insert
  - [ ] erase
  - [ ] swap
  - [ ] clear
- [ ] Create a map operations function
  - [ ] find
  - [ ] count
  - [ ] lower_bound
  - [ ] upper_bound
  - [ ] equal_range
- [ ] Create a map allocator function 
- [ ] Create a map non-member function overloads 
- [ ] Create a map relational operators overloads 
- [ ] Create a map swap function (non-member) 
- [ ] Create a map observers function (get_allocator) 

## 📦 Stack

The stack is a container that encapsulates a dynamic stack. It is very similar to a stack of plates, where you can only access the top plate.

### Step to implement a stack

- [ ] Create a stack class that encapsulates a dynamic stack (with a list) 
- [ ] Create a stack capacity function 
  - [ ] empty
  - [ ] size
- [ ] Create a stack element access function 
  - [ ] top
  - [ ] push
  - [ ] pop
  - [ ] empty
  - [ ] size
- [ ] Create a stack allocator function (get_allocator)  
- [ ] Create a stack non-member function overloads (relational operators)  
- [ ] Create a stack relational operators overloads (non-member)  
- [ ] Create a stack swap function (non-member)   
- [ ] Create a stack observers function (get_allocator)  

## Iterator

The iterator is a special type of object that can be used to iterate over other objects. It is similar to the `for` loop in other languages.

## Others implementations

- [ ] std::iterator_traits
  - [Reference](https://en.cppreference.com/w/cpp/iterator/iterator_traits)
- [ ] std::reverse_iterator
  - [Reference](https://en.cppreference.com/w/cpp/iterator/reverse_iterator) 
- [ ] std::enable_if
  - [Reference](https://en.cppreference.com/w/cpp/types/enable_if) 
- [ ] std::is_integral
  - [Reference](https://en.cppreference.com/w/cpp/types/is_integral) 
- [ ] std::equal
  - [Reference](https://en.cppreference.com/w/cpp/algorithm/equal) 
- [ ] std::pair
  - [Reference](https://en.cppreference.com/w/cpp/utility/pair)
- [ ] std::make_pair
  - [Reference](https://en.cppreference.com/w/cpp/utility/make_pair)
