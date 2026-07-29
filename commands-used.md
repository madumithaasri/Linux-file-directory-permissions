# Commands Used

```bash
mkdir /company

mkdir /company/developers
mkdir /company/managers
mkdir /company/shared

groupadd managers

chgrp developers /company/developers
chgrp managers /company/managers

chmod 770 /company/developers
chmod 770 /company/managers
chmod 775 /company/shared

touch /company/developers/project.txt
touch /company/managers/report.txt
touch /company/shared/notice.txt

chown employee1:developers /company/developers/project.txt

ls -ld /company/*
ls -l /company/developers
ls -l /company/managers
ls -l /company/shared
