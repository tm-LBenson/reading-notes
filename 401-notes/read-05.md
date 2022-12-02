# Implementation: Linked Lists  
  
## Some ideas for how you might want to teach:  
  
- Use an analogy  
- Explain a detail in depth  
- Use WHY, WHAT, HOW structure  
- Tutorial / walk through an example  
- Write a quiz  
- Create a vocabulary/definition list  
- Write a cheat sheet  
- Create a diagram / visualization / cartoon of a topic  
- Anthropomorphize the concepts, and write a conversation between them  
- Build a map of the information  
- Construct a fill-in-the-blank worksheet for the topic  

## Topic chosen to teach:
Linked Lists - WHY, WHAT, HOW

#### Why do we use Linked Lists?  
  
  Linked lists are efficient insertion and deletion. Linked lists are more efficient than arrays especially when dealing with memory alocation. The size for a linked list is not pre-defined allowing for dynamic data sizes. The linked lists can grow and shrink dynamically. 
  
#### What is a linked List?  
  
  A linked list a data structure that stores a collection of ordered data that can only be accessed sequentially with the next, prev, and val properties. 
  
#### How can we implement linked lists into our work flow?  
  
  ```js
  const list = {
    head: {
        value: 'this is a string'
        next: {
            value: 10                                             
            next: {
                value: 'another random string'
                next: {
                    value: 3
                    next: null	
                    }
                }
            }
        }
    }
};
  ```
Another example of linked lists, is the middleware used in express. 
## Resources  

[Read and save for reference: Big O: Analysis of Algorithm Efficiency (Up through the section titled “Linear Complexity Growth”)](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html) 

[Read: Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)  

[Read: What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)  

[Read: What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)  
  
