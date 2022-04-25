How to use the provided .txt files:

1. CreateQueries.txt:  
    This is the first file that needs to be handled. 
    Simply copying and pasting all of the code exactly as it
    is from the file into https://sqliteonline.com/ will 
    result in the creation of all of the tables for the 
    database. After pasting, press run and there should 
    be no errors and all of the tables will appear on the left side. 

2. InsertQueries.txt: 
    This is the file that will insert all of the sample 
    testing data into the tables. Run it the same way as 
    the CreateQueries.txt once all of the tables are 
    created. This should also run without any errors. 
    to see the data, run a select command from any of the 
    tables seen on the left side of the screen. For example, 
    SELECT * FROM PERSON; 

3. InsertDeleteQueries.txt: 
    This file contains both inserts and then delete statements
    that delete what was inserted. This means that copying and 
    pasting the whole file and then running it all at once will 
    result in no changes to the database. To see these inserts 
    work before they are deleted, copy just the insert statements
    from the file and run those. To view just those new inserts, 
    the following select commands can be ran one at a time: 
        SELECT * FROM PERSON WHERE personId > 120; 
        SELECT * FROM PAT_XRAY WHERE patientId = 1;
        SELECT * FROM PAT_MEDS WHERE patientId = 14; 
    Those commands will show the results of the inserts. Now the 
    delete statements can be copied over and all ran at once to 
    delete all of the inserted data. The same select commands
    above that were used to see the results of the inserts can be 
    ran again and will now produce no results. 

4. SimpleQueries.txt: 
    This file contains a collection of queries that can be ran 
    in order to recieve some results from the database. These 
    queries should be ran individually by copying and pasting to 
    the sqliteonline. They will all produce some results after 
    being ran. 

5. ExtraQueries.txt:
    Much like the SimpleQueries.txt, this file contains separate
    select queries that will all return something upon being 
    ran individually. The same steps can be taken as in SimpleQueries.txt
    to see the results of the queries. 
    