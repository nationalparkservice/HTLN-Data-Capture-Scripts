# HTLN-Data-Capture-Scripts

Data workflows from Survey123 and other field loggers into MS Access and other relational databases.

# Notes

20231220

Load files with NAs from left outer joins. These affect LocationIDs and
Scientific Names. Review unique cases for herb, woody and big trees.

20231011

Taxon code duplicates leading to many-to-many join warning


20231010

BIG tree categories based on diameter classes. End-to-end to test BIG category counts


20230925

VIBI_woody end-to-end test following pivot_longer

20230919

Set up and moving ongoing wetlands survey 123 project to this repo. Repo layout is

./protocol_name/src                dev folder

./protocol_name/R                  executable scripts



