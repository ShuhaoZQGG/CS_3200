This is the data model for the Chinook Database, which supports a fictitious music e-commerce site.  Each track is stored in a particular digital format and has an associated genre.  The site also supports playlists, where one single track can be part of multiple playlists but may not be included in any playlist.  Each customer order is memorialized in an Invoice which is composed of one or more InvoiceLines, each representing one track purchased. Note that the Quantity attribute of InvoiceLine indicates the number of copies of the particular track that was purchased as part of the associated invoice. Every customer is assigned an employee representative, and each employee is supervised by another employee.  Since the CEO does not report to another employee, this is stored in the database as the CEO reporting to themselves.

Use the Chinook data model to provide valid relational algebra expressions (not tables of data) for question 3 - 7. The result of your RA expression should only include those attributes that are expressly requested.


3.  Are there any artists in the database with at least one track that does not appear on any playlist?  If so, give a list of the artist Names only. 
Tracks_notonplaylist 

4.  Provide a list of the names of all playlists containing tracks of the ‘Jazz’ genre or the ‘Classical’ genre.


5. Provide the First name and last name of any employee who supports customers that have placed orders billed to MA or CT and order mp3 (a type of media) tracks.      


6. Give a list of the customerid and first & last name of all customers, the names (first and last) and emails of their support representatives, and the first and last name of each support representative’s manager. 


7.  Which employees hired after Jan 1 2020 that also report to the CEO support customers in Belgium? Give the employee last name, first name, hire date, and email. 
