# Databases2
Fall semester 2020.

What I learned in this course:


1st lecture
-----------
Codd's 12 rules.
Architecture of a DBMS. Oracle architecture: instance, database files.
Schema, schema objects, Data dictionary views.
Tablespace, datafile, segment, extent, data block.
(01_Codd_12_rules.docx, 01_Oracle_architecture.pptx, 01_Oracle_storage.pptx, 01_Oracle_concepts.docx)

Practice:
db2_practice1.txt

2nd lecture  
-----------
Physical storage organization; Physical storage media types (memory, disk, tape)
How do disks work? RAID technology; Buffer management;
Page organization, record organization;
(02_storage.pptx, 02_RAID.docx, 02_Select_execution.pptx, 02_Oracle_concepts2.docx, 
 02_UW_file_structure.pptx, UW_Ch_13.pdf)

Practice:
db2_practice2.txt, data_dictionary.txt, db2_help.txt

3rd lecture
-----------
Indexing; Sparse index, dense index, primary index, secondary index;
Multi-level index, B+ tree; Difference between a B tree and a B+ tree.
Bitmap index
(03_UW_Indexing.pptx, 03_B_tree.docx, 03_Bitmap_indexes.pptx)

Practice:
Using dynamic SQL statements in PL/SQL (pl_dynamicSQL.txt)
db2_practice3.txt, db2_help.txt

4th lecture
-----------
Hashing; Static hashing; Dynamic hashing; Linear hashing, Extensible hashing
(04_UW_Hashing.pptx, 04_Dynamic_hashing.docx, 04_Oracle_concepts3.docx, UW_Ch_14*.pdf)
Bitmap index cont. (03_Bitmap_indexes.pptx)

Practice:
db2_practice4.txt, 04_cr_index.txt, db2_oracle_examples.docx

5th lecture
-----------
Query processing and optimization. Cost of operations.
Algorithms based on sorting; Nested-loop joins; Index-based join;
Sort-Merge join; Hash-join;
(05_optimization.pptx, 05_operation_cost_examples.pptx, UW_Ch_15.pdf) 

Practice:
db2_practice5.txt
cr_part_table.txt, cr_cluster.txt, cr_part_index.txt (see 05_special_storage.pptx)

6th lecture
-----------
Query optimization. Relational algebra transformations, size estimation.
Pipeline versus materialization.
(06_UW_query_processing.pptx, UW_Ch_16.pdf)

Practice:
db2_practice6.txt
cr_part_table.txt, cr_cluster.txt, cr_part_index.txt (05_Oracle_concepts4.docx)

7th lecture (till page 58)
-----------
Execution plans and hints in Oracle (07_tuning.pptx)
(07_expl.txt, 07_execution_plans1.txt, 07_execution_plans2.txt, 
07_execution_plans3.txt, 07_execution_plans4.txt, 07_hints.txt)

Practice:
************************************************
Midterm test from practice --> October 20th !!!
************************************************

8th lecture
-----------
execution plans and hints cont.
(07_expl.txt, 07_execution_plans1.txt, 07_execution_plans2.txt, 
07_execution_plans3.txt, 07_execution_plans4.txt, 07_hints.txt)
Statistics in the database and histograms.
(08_Oracle_optimization.docx)
Runtime examples: (runtime_example.txt, runtime_example2.txt)

Practice:
db2_practice7.txt

9th lecture
-----------
Consistency, failures, logging, recovery
(09_UW_Crash_recovery.pptx, UW_Ch_17.pdf)

Practice:
db2_practice8.txt

10th lecture
-----------
Logging, recovery (cont.)
Concurrency control; schedule, serializable, conflict-serializable, precedence graph
(10_UW_Concurrency.pptx)

Practice:
db2_practice9.txt

11th lecture
-----------
Concurrency control (cont.)
(10_UW_Concurrency.pptx pages 26- ..., UW_Ch_18.pdf)

Practice:
db2_practice10.txt
test2_compulsory.txt
Some help for graph drawing in exercises: https://app.diagrams.net/ and graph_draw.svg 

12th lecture
-----------
Concurrency control (cont.)
(10_UW_Concurrency.pptx pages 72-128, UW_Ch_18.pdf)

Practice:
db2_practice10.txt
Some help for graph drawing in exercises: https://app.diagrams.net/ and graph_draw.svg 

13th lecture
-----------
Logging and recovery (undo, redo) in Oracle.
Transactions, isolation levels, locks in Oracle.
(11_Oracle_reansactions.docx)
Summary, help for the exam (Exam_questions.docx)

Practice:
************************************************
Endterm test from practice --> December 8th !!!
************************************************
