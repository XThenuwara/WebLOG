# 2025

01.indexing_cardinality_and_composite_index_optimization.md - Indexing, Cardinality and Composite Index Optimization Use Case - Indexing is meant to make queries faster. But if done without understanding the data or the query patterns, it can do the opposite. In this post, I'll walk through a real-world experience where a poorly optimized index on a table with around 500 million records caused daily reports to run painfully slow. The problem involved high cardinality in a timestamp column and how it interacted with a composite index. This case highlights why understanding cardinality, index structure, and query access patterns is critical for performance tuning.

