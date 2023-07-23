# Exercise

```python
##Exercise: Circular Linked List
Allowed functions: malloc, free

• Create a function that builds a circular linked list with n nodes and return the first node. A circular linked list is a linked list where all nodes are connected to form a circle (the last node points to the first node).

• Node struct must be the following : 
```
typedef struct  s_node
{
   int data;
   struct s_node *next;
}               t_node;
```
• Then implement a function that receives this linked list and an integer k as parameters and removes every k-th node until there is no more than one node left, returning the final remaining node.

• Here's how the functions should be prototyped:
```
t_node  *build_linked_list(int n);
t_node  *remove_every_k_node(t_node *head, int k);
```

Be mindful of memory management and make sure no memory leaks occur. For an extra challenge, implement these functions without using global or static variables.
```
# Submissions 
 git push your solution in this repo and hit /submit in Discord