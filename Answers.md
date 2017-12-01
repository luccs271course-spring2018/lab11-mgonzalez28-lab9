- Try using a `TreeMap` and a `HashMap` instead of `MyHashMap`.
  1. Are the resulting word frequencies any different?
      - The resulting word frequencies are not different
  1. Is the time performance any different? If so, how would you rank the three implementations (in increasing order of time complexity)?
    - Time performance is different. I would rank them as follows:
      - First: HashMap
      - Second: MyHashMap
      - Third: TreeMap
- How are `%` and `Math.floorMod` different? Which works more reliably for computing a hash table index?
  - `Math.floorMod` reduces a number ot the lowest integer while % returns the remainder of two numbers. `Math.floorMod` is more reliable. 
- What is the time complexity of `MyHashMap.size()`, and how could you make it much more efficient?
  - Time complexity is O(n). You could make it more efficient by increasing size everytime you add an item.
- How does this implementation compare to one where you would directly use your linked `Node` class from the earlier assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
  - Both are realiable, but as far as implementation, linked node class was easier to implement. The upside to a more in-depth implementation is that it allows for a better performance in MyHasMap. 
