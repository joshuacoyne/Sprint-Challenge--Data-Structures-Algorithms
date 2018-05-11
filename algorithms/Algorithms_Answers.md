Add your answers to the Algorithms exercises here.

a. O(n)
b. O(log n)
c. O(sqrt(n))
d. O(n log n)
e. O(n^3) 
f. O(n)
g. O(n)

2.
a. function maxDifference(arr) {
  let minVal = arr[0];
  let maxDiff = 0;

  for (let i = 0; i < arr.length; i++) {
    minVal = Math.min(minVal, arr[i]);
    maxDiff = Math.max(maxDiff, arr[i] - minVal);
  }
  return maxDiff;
}

b. Do a binary sort. Go to the middle floor (n/2) and drop an egg. If it breaks halve the floors again(go to floor n / 4). If it doesnt break go up half the remaining floors (floor (n - n/2)/2) and repeat until you find f.

3.
a. O(n2);
b. O(nlog n)