JEREMY IS THE KILLER
ANNABElS interview help a lot and grep :)

Last login: Tue Feb 21 15:42:52 on ttys000
Alss-MacBook-Pro:command-line-mystery alssandy$ cd ga
-bash: cd: ga: No such file or directory
Alss-MacBook-Pro:command-line-mystery alssandy$ ls
cheatsheet.md hint3   hint6   instructions  solution.md
hint1   hint4   hint7   mystery
hint2   hint5   hint8   readme.md
Alss-MacBook-Pro:command-line-mystery alssandy$ cd mystery
Alss-MacBook-Pro:mystery alssandy$ ls
crimescene  memberships streets
interviews  people    vehicles
Alss-MacBook-Pro:mystery alssandy$ cd crimescene
-bash: cd: crimescene: Not a directory
Alss-MacBook-Pro:mystery alssandy$ cd crimescene
-bash: cd: crimescene: Not a directory
Alss-MacBook-Pro:mystery alssandy$ cat crimescene
*******
Crime Scene Report #262227712435
********
Alss-MacBook-Pro:mystery alssandy$ grep -r 'l337' *
Alss-MacBook-Pro:mystery alssandy$ grep 'L337' vehicle
grep: vehicle: No such file or directory
Alss-MacBook-Pro:mystery alssandy$ grep 'L337' vehicles
Alss-MacBook-Pro:mystery alssandy$ grep 'blue' vehicles
Alss-MacBook-Pro:mystery alssandy$ grep -r 'Jeremy' *
memberships/AAA:Jeremy Bowers
memberships/Delta_SkyMiles:Jeremy Bowers
memberships/Museum_of_Bash_History:Jeremy Bowers
memberships/Terminal_City_Library:Jeremy Bowers
people:Jeremy Bowers  M 34  Dunstable Road, line 284
vehicles:Owner: Jeremy Bowers
Alss-MacBook-Pro:mystery alssandy$
