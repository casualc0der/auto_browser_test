what do we need to do to make this work

we need to change the sign ins for all of out lovely users.

slug
email address
password

We could use a rake task for this, or maybe we could just write a little script? Hooking into all of
the active record methods would be ideal though

once we have updated the anon db so we can easily sign in as the users, we will then need to write a selenium script that automatically performs the required actions and reports the results back.

We can then check the state of the back end? Although to be fair we really want to check this from the users perspective to see what they can action while their accounts are a bit messed up?
# auto_browser_test
