ViewDependancy
==============
Interrogates a collection of Dacpacs and outputs a DGML file.
--------------------------------------------------------------
Objects are organised in a Database.schema.object heirarchy / grouping.

Caveats :  
Default schema is assumed to be dbo.

Presently all sqlcmd vars are stripped and used as the database name.  
ie $(DBNAME) will be assumed to represent the physical database DBNAME

Command Line Options:  
DIR: Path to recursively scan for dacpac files  
DGML: DGML Output File  
