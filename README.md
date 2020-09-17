# PressGaneyPatientSatisfactionParserLite (NON-SFTP)
An alternative version of the tiny python program fetches Press Ganey's raw XML data files from a local file system and transforms them into easy-to-use/integrate flat CSV files

FORKED to create a verson of the code that bypasses SFTP and works straight out of file directories. XML files in this scenario are being automatically placed in a specific folder. The goal is to parse these files, save to a new csv file, then move the parsed XML files to an archive folder.

Additional features may be added as needed.
