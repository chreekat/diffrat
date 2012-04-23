diffrat
====

Usage: `$ diffrat <target> <others>`

Results
----

diffrat will list a diff ratio of the target to each of the other files. The
ratio is defined by

    number of changed lines / filesize of target

This is a hack
----

But a useful one!

    $ diffrat exp.js *.js | sort -rn
    3.254   js.js
    1.799   exp_task_menu.js
    1.405   js_lib.js
    1.072   panest.js
    1.053   task_menu.js
    0.121   datatable.js

Here we see datatable.js is pretty dang similar to exp.js. Good to know when
trying to figure out somebody's crappy[1] code.

[1] Never your own code, of course.


