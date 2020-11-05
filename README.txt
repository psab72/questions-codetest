***** Comments *****
Overall, Honestly, I think the code structure is ok but leaning a bit on being terrible. I'd say that there are some terrible parts and there are some amazing parts. 
    The amazing part: 
        - It uses a Repository to organize business logic for large scoped methods. I don't usually use Repository if the module is pretty straightforward.
        - The naming convention comply with Laravel standards.
    The terrible parts:
        - The repititions of if else conditions in the distanceFeed method in BookingController is kinda annoying. We could use a ternary operator or the ?? operator(For >= PHP 7) for one code lines instead. 
        - The line spacing is not consistent.
        - The if {, for { conventions are not consistent.
        - The long If ElseIf conditions can be replaced with Switch statements as it is more readable and technically memory efficient. 
        - Based on my experience, a proper and good database design minimizes, if not eliminates, the long and unnecessary codes.
        Eloquent relations for Laravel is a very nice tool to make those long line of codes to be short, straightforward and more readable. 

The codes needs more work. If I will refactor everything, I'll start with a good database design and Implement Eloquent relations to ALL models.





Choose ONE of the following tasks.
Please do not invest more than two hours on this.
Upload your results to a Github Gist, for easier sharing and reviewing.

Thank you and good luck!



Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

Code to write tests
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate




What I expect:

A. A readme with:

1.  Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic.. 
2.  Refactor it if you feel it needs formatting. The more love you put into it. The easier for us to asses.  

Make two commits. First commit with original code. Second with your refactor so we can easily trace changes. 

Vänliga hälsningar / Best regards
Virpal Singh