## Data Structures

### MinPriorityQueue

This is a minimum priority queue. Unity's .NET version predates .NET 6, which introduced `PriorityQueue`.

```csharp
MinPriorityQueue<int> queue = new MinPriorityQueue(); 
queue.Enqueue([2, 1]); // adds 2 and 1 to the queue
int first = queue.Dequeue(); // returns 1
queue.Any(); // returns true
```
