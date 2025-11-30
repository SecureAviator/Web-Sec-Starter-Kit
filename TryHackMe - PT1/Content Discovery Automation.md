Using ffuf:
    user@machine$ ffuf -w /usr/share/wordlists/SecLists/Discovery/Web-Content/common.txt -u http://$IP_ADDRESS/FUZZ
Using dirb:
    user@machine$ dirb http://$IP_ADDRESS/ /usr/share/wordlists/SecLists/Discovery/Web-Content/common.txt
Using GoBuster: 
    user@machine$ gobuster dir --url http://$IP_ADDRESS/ -w /usr/share/wordlists/SecLists/Discovery/Web-Content/common.txt