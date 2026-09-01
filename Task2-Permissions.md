Task 2 — Permissions

Level 2 — Permissions

9. Create "secret.txt"

Inside the "linux_test" directory, I created "secret.txt" using:

touch secret.txt

10. Set permissions

I set the permissions using:

chmod 640 secret.txt

I verified the permissions using:

ls -l secret.txt

The result was:

-rw-r-----

What does 640 mean?

"640" gives:

- Owner → "6" → read and write ("rw-")
- Group → "4" → read only ("r--")
- Others → "0" → no permissions ("---")

Therefore:

640 = rw-r-----

The owner can read and modify the file, the group can read it, and other users have no access.
