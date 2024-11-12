Linux ommands
1. clear
2. pwd
3. free -l
4. free -h
5. ls
6. cd /
7. date
8. uptime
9. cd home/ubuntu
10. mkdir devops
11. ls -a
12. whoami
13. vim Report.txt
14. cat Report.txt
15. mv Report.txt devops
16. chmod g-rw Report.txt
17. chmod a+rwx Report.txt
18. chmod o-wx Report.txt
19. chmod g-wx Report.txt
20. uname
21. id
22. sudo apt-get install docker.io
23. docker --version
24. sudo apt-get update
25. sudo apt-get upgrade
26. sudo useradd -m Naqib
27. cd home/
28. sudo passwd Naqib
29. sudo userdel Naqib
30. sudo useradd jawad
31. sudo useradd naqib
32. sudo useradd aziz
33. sudo useradd hafeez
34. sudo passwd naqib
35. sudo passwd jawad
36. sudo passwd aziz
37. sudo passwd hafeez
38. sudo groupadd devops
39. sudo groupadd tester
40. sudo gpasswd -a naqib tester
41. sudo gpasswd -m jawad,aziz tester
42. sudo gpasswd -M ubuntu,hafeez devops
43. sudo usermod -aG docker ubuntu && newgrp docker
44. docker ps
45. docker pull mysql:latest
46. docker images
47. docker run -d -e MYSQL_ROOT_PASSWORD=test@123 mysql:latest
48. docker exec -it mysql-container mysql -u root -p
49. sudo apt-get install python3
50. python --version
51. sudo adduser -m naqib
52. cat /etc/passwd
53. sudo adduser AR
54. sudo adduser uzair
55. sudo deluser jawad
56. sudo apt install zip
57. zip -r ldf.zip copyfiles/
58. cp ldf.zip practice
59. mkdir unzipped/
60. unzip -n ldf.zip
61. ping eazywayz.us
62. ping youtube.com
63. netstat
64. sudo apt-get install net-tools
65. ifconfig
66. traceroute youtube.com
67. nslookup google.com
68. nslookup eazywayz.us
69. whois eazywayz.us
70. arp
71. git --version
72. git init
73. git log
74. git add helo-dosto.txt
75. git commit -m "this is first commit"
76. mv nibbi.txt git-for-devops/
77. git restore --staged nibbi.txt
78. git commit -m "adding nibba nibbi"
79. git config --global --edit
80. git commit --amend --reset-author
81. git log
82. history
