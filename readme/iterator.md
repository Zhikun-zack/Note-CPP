# Iterator

## Introduction

An **iterator** is an object (like a pointer) that points to an element inside the container. We can use iterators to move through the contents of the container. They can be visualized as something similar to a pointer pointing to some location and we can access the content at that particular location using them.

## Types

Depending upon the functionality of iterators they can be classified into five categories, as shown in the diagram below with the outer one being the most powerful one and consequently the inner one is the least powerful in terms of functionality.

![](<../.gitbook/assets/image (2).png>)

Now each one of these iterators are not supported by all the containers in STL, different containers support different iterators,

![](<../.gitbook/assets/image (1).png>)

## In C++

```
vector<int> ar = { 1, 2, 3, 4, 5 };
      
    // Declaring iterator to a vector
    vector<int>::iterator ptr;
      
    // Displaying vector elements using begin() and end()
    cout << "The vector elements are : ";
    for (ptr = ar.begin(); ptr < ar.end(); ptr++)
        cout << *ptr << " ";
      
    return 0;    
```

Output is:

```
The vector elements are : 1 2 3 4 5 
```
