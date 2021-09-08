# Archive-Existing-RDS-Files

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

Over the last couple of months, I came to work a lot with RDS files and noticed a crucial shortcoming: The base R saveRDS function does not allow for any kind of archiving of existing same-named files on your hard drive. In this blog post, I will explain why this might be very useful by introducing the basics of serialization first and then showcasing my proposed solution: A wrapper function around the existing base R serialization framework.
