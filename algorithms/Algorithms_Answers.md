<!-- Add your answers to the Algorithms exercises here. -->

<!-- Again as a precursor to this assignment, I did not fully understand how to analyze this code. I struggle to read it as English so it's hard to know exactly what I should be looking for when analyzing for runtime, therefore I'm not able to explain adequately my answers. -->

1.  a) O(n)
    b) O(log(n))
    c) O
    d) O(n log(n))
    e) O(n^2)
    f) O(n)
    g) O(n)

2.  a)
    function findMaxDiff(arr) {
        let diffs = [];
        let min = arr[0];
        let maxDiff = 0;
        for (let i = 0; i < arr.length; i++) {
            if (arr[i] < min) {
                min = arr[i]
            };
            else if (arr[i] - min > maxDiff) {
                maxDiff = arr[i] - min}
            };
        return maxDiff
    };

    b) Use a binary search algorithm.

3.  a) O(n^2)
    b) O(n log(n))
