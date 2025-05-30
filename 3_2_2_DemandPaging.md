# DEMAND PAGING ?
A memory management technique where pages are loaded into memory only when needed, rather than loading the whole program at once.

| **Page Size** | **Impact**                                    |
| ------------- | --------------------------------------------- |
| Small         | Less fragmentation, more page faults          |
| Large         | Less page faults, more internal fragmentation |
| Too Small     | High page table and disk I/O overhead         |
| Too Large     | Waste of memory and I/O bandwidth             |
