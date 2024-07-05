# Java-Collections-Revision

`Dont forget to give a ⭐star 😆, keep studying !`

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

## String
A `String` in Java is an immutable sequence of characters. Once created, the contents of a `String` cannot be modified.

Key Methods:
- `length()`: Returns the length of the string.
- `charAt(int index)`: Returns the character at the specified index.
- `substring(int beginIndex, int endIndex)`: Returns a new string that is a substring of the original string.
- `contains(CharSequence s)`: Returns true if the string contains the specified sequence of characters.
- `indexOf(String str)`: Returns the index within the string of the first occurrence of the specified substring.
- `lastIndexOf(String str)`: Returns the index within the string of the last occurrence of the specified substring.
- `toLowerCase()`: Converts all characters in the string to lower case.
- `toUpperCase()`: Converts all characters in the string to upper case.
- `trim()`: Removes leading and trailing white spaces.
- `replace(CharSequence target, CharSequence replacement)`: Replaces each occurrence of the target sequence with the replacement sequence.

Example:
```java
public class StringExample {
    public static void main(String[] args) {
        String str = "Hello, World!";
        System.out.println("Length: " + str.length());
        System.out.println("Character at index 1: " + str.charAt(1));
        System.out.println("Substring from index 0 to 5: " + str.substring(0, 5));
        System.out.println("Contains 'World': " + str.contains("World"));
        System.out.println("Index of 'o': " + str.indexOf('o'));
        System.out.println("Last index of 'o': " + str.lastIndexOf('o'));
        System.out.println("To lower case: " + str.toLowerCase());
        System.out.println("To upper case: " + str.toUpperCase());
        System.out.println("Trimmed string: '" + str.trim() + "'");
        System.out.println("Replaced 'World' with 'Java': " + str.replace("World", "Java"));
    }
}
```

## StringBuilder
A `StringBuilder` is a mutable sequence of characters. It is used to create and manipulate strings in an efficient way.

Key Methods:
- `append(String str)`: Appends the specified string to the sequence.
- `insert(int offset, String str)`: Inserts the specified string at the specified position.
- `delete(int start, int end)`: Removes the characters in the specified range.
- `reverse()`: Reverses the sequence.
- `toString()`: Returns a string representing the data in the sequence.

Example:
```java
public class StringBuilderExample {
    public static void main(String[] args) {
        StringBuilder sb = new StringBuilder();
        sb.append("Hello");
        sb.append(", ");
        sb.append("World!");
        System.out.println("StringBuilder content: " + sb.toString());

        sb.insert(7, "Java ");
        System.out.println("After insertion: " + sb.toString());

        sb.delete(5, 7);
        System.out.println("After deletion: " + sb.toString());

        sb.reverse();
        System.out.println("After reversing: " + sb.toString());
    }
}
```

## Parsing Strings to Basic Data Types

### Parsing to int
- `Integer.parseInt(String s)`: Parses the string argument as a signed decimal integer.

Example:
```java
public class ParseIntExample {
    public static void main(String[] args) {
        String str = "123";
        int num = Integer.parseInt(str);
        System.out.println("Parsed integer: " + num);
    }
}
```

### Parsing to double
- `Double.parseDouble(String s)`: Parses the string argument as a double.

Example:
```java
public class ParseDoubleExample {
    public static void main(String[] args) {
        String str = "123.45";
        double num = Double.parseDouble(str);
        System.out.println("Parsed double: " + num);
    }
}
```

### Parsing to boolean
- `Boolean.parseBoolean(String s)`: Parses the string argument as a boolean.

Example:
```java
public class ParseBooleanExample {
    public static void main(String[] args) {
        String str = "true";
        boolean bool = Boolean.parseBoolean(str);
        System.out.println("Parsed boolean: " + bool);
    }
}
```

### Parsing to long
- `Long.parseLong(String s)`: Parses the string argument as a long.

Example:
```java
public class ParseLongExample {
    public static void main(String[] args) {
        String str = "123456789";
        long num = Long.parseLong(str);
        System.out.println("Parsed long: " + num);
    }
}
```

### Parsing to float
- `Float.parseFloat(String s)`: Parses the string argument as a float.

Example:
```java
public class ParseFloatExample {
    public static void main(String[] args) {
        String str = "123.45";
        float num = Float.parseFloat(str);
        System.out.println("Parsed float: " + num);
    }
}
```

### Converting Primitive Data Types to Strings
- `String.valueOf(int i)`: Returns the string representation of the int argument.
- `String.valueOf(double d)`: Returns the string representation of the double argument.
- `String.valueOf(boolean b)`: Returns the string representation of the boolean argument.
- `String.valueOf(long l)`: Returns the string representation of the long argument.
- `String.valueOf(float f)`: Returns the string representation of the float argument.

Example:
```java
public class ValueOfExample {
    public static void main(String[] args) {
        int i = 123;
        double d = 123.45;
        boolean b = true;
        long l = 123456789L;
        float f = 123.45f;

        String intStr = String.valueOf(i);
        String doubleStr = String.valueOf(d);
        String booleanStr = String.valueOf(b);
        String longStr = String.valueOf(l);
        String floatStr = String.valueOf(f);

        System.out.println("String representation of int: " + intStr);
        System.out.println("String representation of double: " + doubleStr);
        System.out.println("String representation of boolean: " + booleanStr);
        System.out.println("String representation of long: " + longStr);
        System.out.println("String representation of float: " + floatStr);
    }
}
```

Keep studying and happy coding! 🌟😆
