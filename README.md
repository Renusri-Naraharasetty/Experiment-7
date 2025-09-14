# Experiment-7
## Write a python program for sorting and inspect for failures. 
## Algorithm:

1.Start the program.

2. Get the number of elements from user
   
3. Get the elements to be sorted
  
4. Traverse the array and sort the elements one by one

5. Print the sorted array

6. Stop the program.
   
# Program:
```python
numbers = list(map(int, input("Enter numbers separated by space: ").split()))

n = len(numbers)
for i in range(n):
    for j in range(0, n-i-1):
        if numbers[j] > numbers[j+1]:
            numbers[j], numbers[j+1] = numbers[j+1], numbers[j]

print("Sorted list in ascending order:", numbers)

```

# Output
<img width="1495" height="240" alt="image" src="https://github.com/user-attachments/assets/34184d6f-f1e0-4497-aa47-65e1f79beaa8" />



# Result
Thus the program to perform sorting is successfull and has been implemented.


