# Flowchart
``` mermaid
flowchart TD
    start((Sstart))
    init[/n <- 0 /]
    check[n <= 10]
    check2[n % 2 = 0]
    increment[n++]
    output[/FizzBuzz/]
    finish(((Finish)))

    start --> init --> check
    check -- YES --> check2
    check2 -- YES --> output
    check2 -- NO --> n[/n/]
    output --> increment --> check
    n --> increment
    check -- NO --> finish
```

# Pseudo-Code
``` pseudo-code
DECLARE n : INTEGER

FOR n <- 0 TO 10 STEP 1
    IF n % 2 = 0 THEN
        OUTPUT "FIZZBUZZ"
    ELSE
        OUTPUT n
    ENDIF
NEXT n
```