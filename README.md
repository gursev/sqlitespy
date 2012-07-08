sqlitespy

---------------------

Ruby script for sqlite database analysis. 

Usage: sqlitespy.rb [options]

Specific Options:

-d, --database DATABASE_PATH, Sqlite database to analyze.

-s, --show-schema, Show database schema

--find x,y,z, Array, Strings to search

-c, --case-sensitive, Perform case sensitive search. Default is case insensitive.

-e, --exact--match, Perform exact match for the search strings

-r, --row-dump, Dump Database Row when a match is found

-m, --metadata, Look for search strings only in DB metadata (table and column names)

-v, --verbose, Verbose output

-h, --help, Show this message
