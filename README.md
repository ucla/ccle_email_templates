Course creator email templates
====================

Course creator email templates should be name in the following convention:

{subject area}_course_setup_email.txt

If course creator cannot find an email template for that subject area it 
will look for a file called DEFAULT_course_setup_email.txt.

Here is an example email template:

    FROM: CCLE <ccle@ucla.edu>
    Bcc: Kearney, Deborah (dkearney@oid.ucla.edu)
    SUBJECT: #=nameterm=# #=coursenum-sect=# class site created
    Dear Prof. #=lastname=# (#=to=#)

    Your #=nameterm=# CCLE course web site for #=dept=# #=coursenum-sect=# is:
    #=url=#

    You can now login to your course with your UCLA Logon ID and password, just as you would access your
    My.UCLA. Your course will be populated with students over the next 24 hours. For help:

        * Contact your CCLE local support listed at https://ccle.ucla.edu/about/contact.html .
        * Find CCLE help documentation at https://ccle.ucla.edu/course/view.php?name=cclehelp .

    Thank you,

    The CCLE Team
    ccle@ucla.edu

Notes:
* The first three lines are headers. They are used to specify the from, bcc, and subject area fields
* Available email template replacement values are:
 * lastname
 * to (instructor's email address)
 * coursenum-sect
 * dept
 * url
 * term
 * nameterm