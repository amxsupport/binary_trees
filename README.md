# C - Binary trees

This was a partner project in which we learned about the details, advantages,
and disadvantages of using trees as data structures. We learned about how to
qualify trees as well as how to traverse them. Throughout the project, we
implemented binary, binary search, AVL, and Max Binary Heap trees.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files for all tasks. Provided by Alx
School.

## Helper File :raised_hands:

* [binary_tree_print.c](./binary_tree_print.c): C function that prints binary
trees in a pretty way.

## Header File :file_folder:

* [binary_trees.h](./binary_trees.h): Header file containing definitions and
prototypes for all types and functions written for the project.

Data Structures
```
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;
```
## Authors :black_nib:

* __Abdelaaziz Amksa__ <[amxsupport](https://github.com/amxsupport)>
* __Ottman Chouqar__ <[Ottman](https://github.com/Otmanbboy)>
