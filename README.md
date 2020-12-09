# sqlsnips
 
attach db with empty .mdf

use [master]
GO
Create DATABASE [adventureWorks] ON
( FILENAME = "D:\db\AdventureWorksSuperLTEF5_Data.mdf")
FOR ATTACH
GO
