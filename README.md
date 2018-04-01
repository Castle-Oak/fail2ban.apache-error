# fail2ban.apache-404

Directory brute-forcing tools like Dirbuster enable actors to gather additional information about web host. This tools works by reading potential directories/files from a word list and attempting to perform an HTTP-GET against the web host. If the tool receives 200 or 403 HTTP code, the tool knows the directory exists. One way of combatting these attempts is to block clients that generate excessive HTTP-404 codes.
