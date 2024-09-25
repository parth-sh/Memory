
This File contains code for [[Screen New WR]]

log110924:
1. Deleted CREATE TABLE PROCEDURES from fmdr_mobileSA.sql 

2. Remove CREATE TABLE procedures, Ran Baseline, baseline Db copy in ITAGL, check population of column null

log130924:
1. Debugging Cell Value Listener of Procedure Field [[ProcedureCodeDepLogic]]

log250924:
Inspecting [[ProcedureCodeFilter]] class present in this file for WG filter. 
Contains this code to filter [[Procedures]] 
```java
pcdProc.setFilter(new ProcedureCodeFilter());
```

