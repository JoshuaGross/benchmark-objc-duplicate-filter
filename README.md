benchmark-objc-duplicate-filter
===============================

Benchmarks for different ways of filtering duplicates in Objective-C (specifically on iOS).

Benchmark Results (iOS 7, iPhone 5)
===================================
no duplicates
Explicit enumeration, O(n^2) no duplicates: 6.677434
Get first matching object with indexOfObjectPassingTest no duplicates: 5.670303
Get all matching objects with predicate no duplicates: 14.675398
NSSet no duplicates: 0.483276
NSDictionary no duplicates: 0.568170
with duplicates
Explicit enumeration, O(n^2) with duplicates: 5.321357
Get first matching object with indexOfObjectPassingTest with duplicates: 4.540622
Get all matching objects with predicate with duplicates: 14.671595
NSSet with duplicates: 0.449793
NSDictionary with duplicates: 0.539544
