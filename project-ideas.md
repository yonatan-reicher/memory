

Simulate an SSD drive in code.
Example code:

```cpp
class Block {
    Page physicalPages[];
};

class SSD {
    Block blocks[];  // Total: 1800 physical pages
    Dictionary<void*, (int, int)> logicalBlockMap; // up to 1500 mapped pages
    // Logical page: void* -> Page
};
```
