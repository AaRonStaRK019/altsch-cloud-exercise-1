# AltSchool Cloud Engineering - Second Semester - Exercise 1

## Solutions

`set up new user with home directory`

![useradd](./img-screenshots/1-new-user-zhuo-setup.png)


`create new directories within the home directory`

![mkdir](./img-screenshots/2-create-new-directories.png)


1. `change directory using the absolute pathname`

![absolute path name](./img-screenshots/a.cd-into-tests-absolute.png)


2. `change directory using the relative pathname`

![relative pathname](./img-screenshots/b.cd-into-tests-relative.png)


3. `create new file with text in specified directory using echo command`

![echo command](./img-screenshots/c.echo-hello-a-misc-fileA.png)


4. `create empty file in the misc directory, then add dummy content.`

![echo command](./img-screenshots/d.dummy-content--empty-fileB.png)


5. `Copy contents of fileA into fileC`

![cp](./img-screenshots/e.copy-fileA--fileC.png)


6. `Move contents of fileB into fileD`

![mv](./img-screenshots/f.move-fileB--fileD.png)


7. `Create a tar archive called misc.tar for the contents of misc directory`

![tar -cvf command](./img-screenshots/g.archive-misc--tar.png)


8. `Compress the tar archive to create a misc.tar.gz file`

![gzip command](./img-screenshots/h.compress-misc.tar--misc.tar.gz.png)


9. `Create a user and force the user to change his/her password upon login`

![passwd -e command](./img-screenshots/i.new-user--nuel--ch-password-immediately.png)


10. `Lock a users password` `unlock user's password to ensure lock worked`

![passwd -l command](./img-screenshots/j.lock-unlock-nuel-password.png)


11. `Create a user with no login shell`

![no login shell](./img-screenshots/k.user-no-login-shell.png)


12. `Disable password-based authentication for ssh`

![edit sshd_config file](./img-screenshots/l.disable-passwd-auth.png)    


13. `Disable root login for ssh`

![edit sshd_config file](./img-screenshots/m.disable-root-login.png)

`restart ssh service`

![service command](./img-screenshots/m(1).restart-ssh-service.png)
