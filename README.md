# regexquery
Query Language for Regular Expressions


How to use RegexQueryLanguage


    RegexQuery("FIND a IN happy") // returns the matched string
    RegexQuery("REPLACE a WITH b IN happy") // returns the replaced string
    RegexQuery("IS p IN happy") // returns yes, otherwise returns no
    RegexQuery("COUNT p IN happy") // returns 2. I.e. the number of occurrences of p in happy
