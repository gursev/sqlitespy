sqlitespy
=======
Ruby script for sqlite database analysis.<br/>
Usage: sqlitespy.rb [options]<br/>
Specific Options:<br/>
-d, --database DATABASE_PATH, Sqlite database to analyze. <br/>
-s, --show-schema, Show database schema<br/>
    --find x,y,z, Array, Strings to search<br/>
-c, --case-sensitive, Perform case sensitive search. Default is case insensitive.<br/>
-e, --exact--match, Perform exact match for the search strings<br/>
-r, --row-dump, Dump Database Row when a match is found<br/>
-m, --metadata, Look for search strings only in DB metadata (table and column names)<br/>
-v, --verbose, Verbose output<br/>
-h, --help, Show this message<br/>

Additional details available on my blog: http://gursevkalra.blogspot.com/2012/02/sqlitespy-for-sqlite-database-analysis.html