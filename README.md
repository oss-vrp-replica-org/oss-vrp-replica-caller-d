# oss-vrp-replica-caller-d

Fourth caller of a replica harness built for an **authorized** bug-bounty report
(Google OSS VRP). Unlike the first three, this one is owned by an **organisation**, not by
the user `ooriime`, so that `repository_owner_id` differs between caller and callee.

It calls a reusable workflow in our own account (`ooriime/oss-vrp-replica-workflows`) and
never calls, forks, or triggers anything in a Google repository.
