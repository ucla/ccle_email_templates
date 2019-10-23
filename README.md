Course creator email templates
====================

Course creator email templates should be name in the following convention:

{subject area}_course_setup_email.txt

Subject area is assumed to be in all caps. If course creator cannot find an 
email template for that subject area it will look for a file called 
DEFAULT_course_setup_email.txt.

Here is an example email template:

    FROM: CCLE <noreply@ccle.ucla.edu>
    SUBJECT: #=nameterm=# #=coursenum-sect=# class site created
    Dear Prof. #=lastname=# (#=to=#)

    Your #=dept=# #=coursenum-sect=# (#=nameterm=#) course site in now available at the following url:
    #=url=#

    - Have questions about using CCLE? -

    Documentation is available at:
    https://docs.ccle.ucla.edu

    CCLE Office Hours | Mon, Wed, Fri 12 pm - 1 pm | Tues & Thurs,  11:30 am - 12:30 pm
    https://ccle.ucla.edu/course/view/ccleofficehours

    - Help us improve CCLE -

    Contact your local CCLE Support staff with suggestions:
    https://ccle.ucla.edu/mod/page/view.php?id=209487

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
