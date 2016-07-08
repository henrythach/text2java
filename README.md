# text2java

A quick and dirty online tool that converts multi-line text to a concatenated String to be copied and pasted into your Java source code.

Check it out at http://henrythach.github.io/text2java.

Example:

It will convert this:

```sql
SELECT *
  FROM users
 WHERE first_name = 'Henry'
   AND last_name = 'Thach'
```

into

```java
"SELECT *" +
"  FROM users" +
" WHERE first_name = 'Henry'" +
"   AND last_name = 'Thach'"
```
