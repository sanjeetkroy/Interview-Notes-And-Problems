# Solutions for Sliding Window Problems
1. __Maximum sum subarray of Size k__

```
int maxSubArray(int[] arr, int n, int k) {
    int maxSoFar = 0;
    int currSum = 0;

    if (arr.length < k) {
        return Arrays.stream(arr).reduce(0, (a,b) -> a+b);
    }

    // Find Sum of First Window
    for(int i=0;i<k;i++) {
        currSum += arr[i];
    }
    
    maxSoFar = Math.max(maxSoFar, currSum);

    //Slide Window to right
    for(int i=k;i<n;i++) {
        currSum = currSum + arr[i] - arr[i-k];
        maxSoFar = Math.max(maxSoFar, currSum);
    }
    return maxSoFar;
}
```  
- - - -
2.  __Count Occurrences of Anagram__
```
int anagramCount(String text, String word) {
    /**
     * To Compare the word with window, we will firstly sort the word.
     * then sort each window, to compare with word.
     * After sorting, anagrams will be same.
     * To Further optimize the Performance One can use Frequency array to compare anagrams.
     */
    
    word = Arrays.stream(word.split("")).sorted().collect(Collectors.joining());
    int k = word.length();
    int n = text.length();
    int start = 0;
    int count = 0;

    while(start <= n-k) {
        String currStr = text.substring(start, start + k);
        currStr = Arrays.stream(currStr.split("")).sorted().collect(Collectors.joining());

        if(currStr.equals(word)){
            count++;
        }
        start++;
    }
    return count;
}
```
- - - -
3. __Difference between the maximum and minimum average of all k-length continuous subarrays__
```

```