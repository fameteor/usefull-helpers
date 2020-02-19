# usefull-helpers

They are both functions and helpers

### hlp_sessionVar

Get the session variable calle `name`

        {{hlp_sessionVar "name"}}

should work also as a function

        hlp_sessionVar("name")
        
code

        hlp_sessionVar = function(varname)  {
                return Session.get(varname);
        };
        UI.registerHelper('hlp_sessionVar', hlp_sessionVar);

### hlp_count

Counts the number of elemnts of a cursor or an array


### hlp_last

get the last element of an array (see if it would work on a cursor ?)
