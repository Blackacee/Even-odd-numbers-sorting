# Even-odd-numbers-sorting

[10, 21, 4, 15, 7, 99, 0, 12].sort(function(a, b) {
 return (a & 1) - (b & 1) || a - b;
});
