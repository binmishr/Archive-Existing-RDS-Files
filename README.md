# Archive-Existing-RDS-Files

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

Over the last couple of months, I came to work a lot with RDS files and noticed a crucial shortcoming: The base R saveRDS function does not allow for any kind of archiving of existing same-named files on your hard drive. In this blog post, I will explain why this might be very useful by introducing the basics of serialization first and then showcasing my proposed solution: A wrapper function around the existing base R serialization framework.
