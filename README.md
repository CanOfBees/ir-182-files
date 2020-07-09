## files, etc ##
for IR-182.

### sort `check_these` ###
e.g. `$ sort < check_these.txt > check_test_std.txt`

### running the query ###
1. Navigate to your local RISearch endpoint
2. Set up your query:
   1. Under the "Find Tuples" tab,
   2. Copy/Pasta the risearch-summer2019-with-status.rq into the "Query Text or URL" box, and,
   3. Select "sparql" for the Language,
   4. Select your preferred Response format (I used "CSV"), and
   5. Lastly select "Unlimited" for your Limit.
3. Select the "Launch" button (buckle your seatbelt, please, and return your tray to the upright position).

### diff the results ###
I used the IntelliJ built-in diff utility
1. In the Project Pane, select both files using Ctrl + mouse click.
2. With both files highlighted, Ctrl + D to diff.

There are lots of other fun ways to do this. You might enjoy
`± diff -y --suppress-common-lines check_these_std.txt risearch-results-std.txt`, or some other approach.
