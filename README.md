# fix-winscp-permission-denied
there is an error message you may face it in WinSCP , that's: WinSCP Permission denied - Error code 3

how to solve it?

if you sure that you a superuser in your linux server and you can run `sudo -u` in putty follow the instruction:

1- before login to your account in WinSCP, click on `File procol` and choose `SCP`

2- click on `Advanced...` and under `Evvironment` click on `SCP/Shell`

3- under the `Shell` you can find `Shell:` and change the input to `sudo su -`

finish :) enjoy the WinSCP

https://winscp.net/eng/download.php
