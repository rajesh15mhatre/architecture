
## 16. MInimizing desk latency
- sequencial I/O is fster than ramdon I/O
- Logging is sequencial
- log as much data in one go 
- use asynchonus logging
- create a loggin thread which will store all logs and logs it at the end.ther is a chance of loss of loggs in this method
- Webcontent files latency:
  - web content catching:
  - apply reverse proxy to store static data on web server and to implement page cache and zero copy
- DB Disk Acess latency:
  `- Data catching, Schema optimizartion: Denaormalised can help as all data will be in one/few tables
   - Creating index
   - Query optimization  
  -  Higher hardaware: SSD disk with higher IOPS, RAID disk 
## CPU Latency
- Inefficient algo
- Context switching
  - When a process performs I/O cpu processing is stops and resumes when I/O is complete so avoid too many I/O is program to avoid CPU waste time. As cpu 
## Minimize cpu latency
- Use batch or aSync IO - Async IO using separate thread
- Use Thread Pool size - 
## 19. Common latency tools
- [gist,github.com/jboner/2841832](https://gist.github.com/jboner/2841832)
## Concurrency latency
- we need to kepp processs parellel as much s possible
-
