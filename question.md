- maybe not mention double and int52 at all?
- background -> google benchmark: Arjun says this is too much detail
- background -> llvm-mca: the requirement says I should not do a journal, and llvm-mca did not work for me. should i still talk about it? 

- Clang use xmm vector vector instructions for scalar operation in a zmm chunk,
  why? maybe flush pipeline when interleaving between vector and scalar? i did
  not find any source or explanation