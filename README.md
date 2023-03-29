# List attachments from Trac site
A Trac wiki macro that shows all attachments uploaded on a Trac site.

This is a wiki macro that can be used to show all attachments uploaded on a Trac site. 
The attachments are displayed as a list of filenames, showing filesize, author and the source of the attachment (wikipage or ticket).

The following examples show its usage when added to a wiki page:
```
[[AllAttachments()]]		# Show all attachments
[[AllAttachments(ticket)]]	# Show the attachments that are linked to tickets
[[AllAttachments(wiki)]]	# Show the attachments that are linked to wiki pages
[[AllAttachments(milestone)]]	# Show the attachments that are linked to milestones
```
