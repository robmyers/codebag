
[LambdaMOO][] is a MUD server.  It is essentially a programmable chat
server.  That simplifies things a bit since one could write non-chat
networked applications on top of LambdaMOO.  "MOO" is just a shorthand
way to refer to LambdaMOO.

   - realms.jhc -- A module for JHCore which permits dividing up a MOO
     into several realms.   Each realm can have its own set of
     builders and realms limit where inter-realm connections may
     happen.   I made it for the educational MOO "Connections", but it
     should work on any JHCore-based MOO.
   - start-stop-moo.sh -- A replacement for the "restart" script that
     ships with the server source.
   - dbbackup/ -- Some scripts for tailing the server log and
     triggering a script when a checkpoint is finished.

[LambdaMOO]: http://www.lambda.moo.mud.org/
