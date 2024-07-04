# Java-Collections-Revision

### HashMap
A `HashMap` stores key-value pairs and uses hashing for efficient storage and retrieval.

#### Key Methods:
- `put(K key, V value)`
- `get(Object key)`
- `remove(Object key)`
- `containsKey(Object key)`
- `containsValue(Object value)`
- `size()`
- `isEmpty()`
- `clear()`
- `keySet()`
- `values()`
- `entrySet()`

#### Example:
```java
import java.util.HashMap;

public class HashMapExample {
    public static void main(String[] args) {
        HashMap<String, Integer> map = new HashMap<>();
        map.put("One", 1);
        map.put("Two", 2);
        map.put("Three", 3);

        System.out.println("Value for key 'One': " + map.get("One"));
        System.out.println("Contains key 'Two': " + map.containsKey("Two"));
        System.out.println("Map size: " + map.size());

        map.remove("Three");
        System.out.println("Map after removing 'Three': " + map);

        map.clear();
        System.out.println("Map after clearing: " + map);
    }
}
```

### HashSet
A `HashSet` stores unique elements and is backed by a `HashMap`.

#### Key Methods:
- `add(E e)`
- `remove(Object o)`
- `contains(Object o)`
- `size()`
- `isEmpty()`
- `clear()`
- `iterator()`

#### Example:
```java
import java.util.HashSet;

public class HashSetExample {
    public static void main(String[] args) {
        HashSet<String> set = new HashSet<>();
        set.add("One");
        set.add("Two");
        set.add("Three");

        System.out.println("Set contains 'Two': " + set.contains("Two"));
        System.out.println("Set size: " + set.size());

        set.remove("Three");
        System.out.println("Set after removing 'Three': " + set);

        set.clear();
        System.out.println("Set after clearing: " + set);
    }
}
```

### List
A `List` is an ordered collection that allows duplicates.

#### Key Methods:
- `add(E e)`
- `add(int index, E element)`
- `get(int index)`
- `remove(int index)`
- `remove(Object o)`
- `set(int index, E element)`
- `contains(Object o)`
- `size()`
- `isEmpty()`
- `clear()`
- `indexOf(Object o)`
- `lastIndexOf(Object o)`
- `subList(int fromIndex, int toIndex)`

#### Example:
```java
import java.util.ArrayList;
import java.util.List;

public class ListExample {
    public static void main(String[] args) {
        List<String> list = new ArrayList<>();
        list.add("One");
        list.add("Two");
        list.add("Three");

        System.out.println("Element at index 1: " + list.get(1));
        System.out.println("List size: " + list.size());

        list.remove("Two");
        System.out.println("List after removing 'Two': " + list);

        list.clear();
        System.out.println("List after clearing: " + list);
    }
}
```

### TreeMap
A `TreeMap` stores key-value pairs in a sorted order.

#### Key Methods:
- `put(K key, V value)`
- `get(Object key)`
- `remove(Object key)`
- `firstKey()`
- `lastKey()`
- `ceilingKey(K key)`
- `floorKey(K key)`
- `subMap(K fromKey, K toKey)`

#### Example:
```java
import java.util.TreeMap;

public class TreeMapExample {
    public static void main(String[] args) {
        TreeMap<String, Integer> map = new TreeMap<>();
        map.put("One", 1);
        map.put("Two", 2);
        map.put("Three", 3);

        System.out.println("First key: " + map.firstKey());
        System.out.println("Last key: " + map.lastKey());
        System.out.println("Value for key 'Two': " + map.get("Two"));

        map.remove("Three");
        System.out.println("Map after removing 'Three': " + map);
    }
}
```

### TreeSet
A `TreeSet` stores elements in a sorted order.

#### Key Methods:
- `add(E e)`
- `remove(Object o)`
- `first()`
- `last()`
- `ceiling(E e)`
- `floor(E e)`
- `subSet(E fromElement, E toElement)`

#### Example:
```java
import java.util.TreeSet;

public class TreeSetExample {
    public static void main(String[] args) {
        TreeSet<String> set = new TreeSet<>();
        set.add("One");
        set.add("Two");
        set.add("Three");

        System.out.println("First element: " + set.first());
        System.out.println("Last element: " + set.last());
        System.out.println("Set contains 'Two': " + set.contains("Two"));

        set.remove("Three");
        System.out.println("Set after removing 'Three': " + set);
    }
}
```

### LinkedHashMap
A `LinkedHashMap` maintains a doubly-linked list of entries.

#### Key Methods:
- `put(K key, V value)`
- `get(Object key)`
- `remove(Object key)`
- `containsKey(Object key)`
- `containsValue(Object value)`
- `size()`
- `isEmpty()`
- `clear()`
- `keySet()`
- `values()`
- `entrySet()`

#### Example:
```java
import java.util.LinkedHashMap;

public class LinkedHashMapExample {
    public static void main(String[] args) {
        LinkedHashMap<String, Integer> map = new LinkedHashMap<>();
        map.put("One", 1);
        map.put("Two", 2);
        map.put("Three", 3);

        System.out.println("Value for key 'One': " + map.get("One"));
        System.out.println("Contains key 'Two': " + map.containsKey("Two"));
        System.out.println("Map size: " + map.size());

        map.remove("Three");
        System.out.println("Map after removing 'Three': " + map);

        map.clear();
        System.out.println("Map after clearing: " + map);
    }
}
```

### LinkedHashSet
A `LinkedHashSet` maintains a doubly-linked list of entries.

#### Key Methods:
- `add(E e)`
- `remove(Object o)`
- `contains(Object o)`
- `size()`
- `isEmpty()`
- `clear()`
- `iterator()`

#### Example:
```java
import java.util.LinkedHashSet;

public class LinkedHashSetExample {
    public static void main(String[] args) {
        LinkedHashSet<String> set = new LinkedHashSet<>();
        set.add("One");
        set.add("Two");
        set.add("Three");

        System.out.println("Set contains 'Two': " + set.contains("Two"));
        System.out.println("Set size: " + set.size());

        set.remove("Three");
        System.out.println("Set after removing 'Three': " + set);

        set.clear();
        System.out.println("Set after clearing: " + set);
    }
}
```

### Stack
A `Stack` represents a last-in-first-out (LIFO) stack of objects.

#### Key Methods:
- `push(E item)`
- `pop()`
- `peek()`
- `isEmpty()`
- `search(Object o)`

#### Example:
```java
import java.util.Stack;

public class StackExample {
    public static void main(String[] args) {
        Stack<String> stack = new Stack<>();
        stack.push("One");
        stack.push("Two");
        stack.push("Three");

        System.out.println("Top element: " + stack.peek());
        System.out.println("Stack size: " + stack.size());

        stack.pop();
        System.out.println("Stack after popping: " + stack);

        System.out.println("Search 'One': " + stack.search("One"));
    }
}
```

### Queue
A `Queue` represents a first-in-first-out (FIFO) collection of objects.

#### Key Methods:
- `add(E e)`
- `offer(E e)`
- `remove()`
- `poll()`
- `element()`
- `peek()`

#### Example:
```java
import java.util.LinkedList;
import java.util.Queue;

public class QueueExample {
    public static void main(String[] args) {
        Queue<String> queue = new LinkedList<>();
        queue.add("One");
        queue.add("Two");
        queue.add("Three");

        System.out.println("Head element: " + queue.element());
        System.out.println("Queue size: " + queue.size());

        queue.remove();
        System.out.println("Queue after removing head: " + queue);

        System.out.println("Peek head: " + queue.peek());
    }
}
```

### Deque
A `Deque` (Double Ended Queue) allows elements to be added or removed from both ends.

#### Key Methods:
- `addFirst(E e)`
- `addLast(E e)`
- `offerFirst(E e)`
- `offerLast(E e)`
- `removeFirst()`
- `removeLast()`
- `pollFirst()`
- `pollLast()`
- `getFirst()`
- `getLast()`
- `peekFirst()`
- `peekLast()`

#### Example:
```java
import java.util.Array

Deque;
import java.util.Deque;

public class DequeExample {
    public static void main(String[] args) {
        Deque<String> deque = new ArrayDeque<>();
        deque.addFirst("One");
        deque.addLast("Two");
        deque.addFirst("Three");

        System.out.println("First element: " + deque.getFirst());
        System.out.println("Last element: " + deque.getLast());

        deque.removeFirst();
        System.out.println("Deque after removing first: " + deque);

        deque.removeLast();
        System.out.println("Deque after removing last: " + deque);
    }
}
```

These examples demonstrate the usage of key methods for each type of collection in Java.
