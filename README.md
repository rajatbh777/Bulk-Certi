# Bulk Certi
I work for ndian Society For Technical Education Students' Chapter MANIT.
Due to covid, we took all our events online and hence had to mail alot of certificates to participants in bulk. So, i came up with this script as a solution.

Using this python script, you can generate e-Certificates in bulk and email them to participants.
I built this script using PIL library to open Certificate Template and draw Name at a specific position in that template using a font. Then for mailing, I
used email & MIME, and imported smtplib for sending mails using SMTP protocol.

## Instructions to Use:

Go through the code and check comments to know better on how to use the script.

Place a certificate template, font file (.ttf) of the font you wish to write text with and an excel sheet(.xlsx) (having the data to be written on the certificate and email addresses to which the certificate will be mailed) in the same directory as that of the script.
