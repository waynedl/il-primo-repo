# il-primo-repo (the first repo)

Hello. This is my first repo (p.s. it's not really but i wanted to use this repo name.)

I regret that I am not on Twitter but I'm sure you can find some other rando to follow.

Check out **@poetisserie** because that person is prolly all KINDS of next-level.

## Repoetry
### Poem in SQL
```sql
WITH t_uxorious_misery AS 
    (SELECT 
        ' '        AS line0,
        chr(13) || 'Take honest measure ' as line1,
        '        of my first repo '    AS line2,
        '        It''s a damn fine first ' as line3,
        '        with no close equal '  AS line4,
        '    Only to be topped' as line5,
        '        ...by the drop' as line6,
        '        ...of a fan-funded sequel.' AS line7,
        chr(13) || '    Find the directory to which I directly commit'    AS line8,
        '    My timed rhymes'                                AS line9,
        chr(9) || '    ...sublime crimes'               AS line10,
        chr(9) || '    ...and ebullient mimes.'                    AS line11
    FROM 
        dual)
SELECT 
    mad_rows AS "... a SQL poem ..."
FROM 
    (SELECT 
        1 as rid,
        '...' || chr(13) || chr(13) as mad_rows
    FROM dual
    UNION ALL
    SELECT
        2 as rid,
        '   Poem : MISREMEMBERED POEM IN CHUNKS' || chr(13) ||
        '     By : Wagnus D-L' || chr(13) ||
        ' Rating : 800 stars' || chr(13) as titlepg
    from dual
    UNION ALL
    SELECT
        3 as rid,
        chr(13) || chr(9) || line1 || chr(13) ||
        line2 || chr(13) || 
        line3 || chr(13) || 
        line4 || chr(13) || 
        line5 || chr(13) || 
        line6 || chr(13) || 
        line7 || chr(13) ||
        line8 || chr(13) || 
        line9 || chr(13) || 
        line10 || chr(13) || 
        line11
    FROM t_uxorious_misery
    )
WHERE LENGTH(mad_rows) > 2
ORDER BY rid ASC NULLS LAST;
```

### SQL Output

```txt
... a SQL poem ...                                                                                                                                                                                                                                                                                                         
...

                                                                                                                                                                                                                                                                                                                      
   Poem : MISREMEMBERED POEM IN CHUNKS
     By : Wagnus D-L
 Rating : 800 stars
                                                                                                                                                                                                                                           

	
Take honest measure 
        of my first repo 
        It's a damn fine first 
        with no close equal 
    Only to be topped
        ...by the drop
        ...of a fan-funded sequel.

    Find the directory to which I directly commit
    My timed rhymes
	    ...sublime crimes
	    ...and ebullient mimes.  


Elapsed: 00:00:00.012
```
