Python-AVL-Tree
=============

Implementation of [AVL Trees] in Python.
Class AVL Tree supports the following functionality:
 - insertion of a new entry in the tree;
 - allows duplicate value entries (requires a uuid for each element)
 - removal of any entry in the tree;
 - search for any entry in the tree;
 - "sanity check" for the tree (described later);
 - 4 various tree traversals
    - preorder,
    - inorder,
    - postorder,
    - inorder non-recursive.
 
Additional Info on AVL Trees:

1) Wikipedia

1a) http://en.wikipedia.org/wiki/AVL_tree 
    Description of AVL trees.

1b) http://en.wikipedia.org/wiki/Tree_traversal 
    Description of tree traversals in binary search trees and
    sample implementations of traversal algorithms in pseudocode.

2) http://www.cse.ohio-state.edu/~sgomori/570/avlrotations.html
   Rotation algorithms for putting an out-of-balance AVL tree back in balance.

3) http://sourceforge.net/projects/standardavl/
   Implementation of AVL trees in C++. I borrowed an idea of "sanity check" -
   a method, which traverses the tree and checks that tree is in balance, contains 
   no circular references, height for each node is calculated correctly and so on.

4) http://oopweb.com/Algorithms/Documents/AvlTrees/Volume/AvlTrees.htm
   From this page I borrowed the idea how to correctly delete an entry
   from an AVL tree.


This code is available under MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

(c) 2010 Pavel Grafov. The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[AVL Trees]: http://en.wikipedia.org/wiki/AVL_tree
