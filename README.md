# ALR
ALR
There is a command injection vulnerability in ALR-F800.
Attackers can reset passwords by requesting cmd.php through POST.
After resetting the password, use POST to request cgi bin/upgrade.cgi for command injection.
