### big O notation
### good code
readable and scalable (time and space)

### why big O?
system clock time depends on the hardware: RAM and processor

### Big O(N)
O(1)<O(log n)<O(n)<O(n log n)<O(n^2)<O(2^n)<O(n!)

### simplifying Big O
1. scalability
take n as a large number
2. consider worst case scenario
3. remove constant
O(a+kn)=O(n)
4. consider different variables for different inputs
O(m+n) != O(n+n)=O(2n)=O(n)
5. remove non-dominants
O(n+n^2)=O(n^2)

### time complexity
### O(1)
constant time
e.g. assigning values

### O(n)
linear time
e.g. for/while loops

### O(n^2) / O(n*m)
e.g. nested loops

### O(n!)
e.g. a nested loop for every item in an array

### space complexity
how much additional memory to run code?
calc not the space required by input, but the extra space

### memory
1 memory slot = 8 bits = 1 byte
8 bits = 1 byte

### 32-bit operating systems
initialize 1 integer -> takes 32 bits
32 bits = 4 bytes -> 4 memory splots

### memory address
represented by hexadecimal (a numbering system with base 16)

### values stored
binary system

### logarithm
always assume binary logarithm
log (n): base=2
n doubles, log increases by 1
O(log n) is a lot better than O(n)
e.g. dividing arrays in half (again and again)
y=k*(2^x) -> x=log(y)
