# CyberSecurity-lab-2
Firstl, we use target machine(Metasploit2) to find our target ip and we get "inet: 10.0.2.15"
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/89cc8c27928a39aca54ccdc020e2eb97ecdd3a0e/Metasploit2.jpg)
After we get our target, we start our tasks.
1. Host Discovery Using Nmap. "nmap -sn "target ip"/24" command.
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/defaf2fb267f6192abacba10740ae61c0aad4bde/Ping%20Scan/nmap%20-sn%20target%20ip.jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/813fedc14fa7bc7837e86f35aaff86b5b211a748/Ping%20Scan/nmap%20-sn%20target%20ip%20(2).jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/f75ff30a69f75657757d56bb241b9a556ac6d707/Ping%20Scan/nmap%20-sn%20target%20ip%20(3).jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/e6d528b1f6afa8d0e77e77279e8f260dd33d7067/Ping%20Scan/nmap%20-sn%20target%20ip%20(4).jpg)
At the end you see 256 IP Adresses scanned.

3. Port Scanning (SYN Scan). "nmap -sS "target ip" command.
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/a0accbed947b62b551c48ffdb6d5659af14db152/TCP%20SYN%20Scan/nmap%20-sS%20target%20ip.jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/426faf323bd8b4bd219f6b0537223ed7b8befde3/TCP%20SYN%20Scan/nmap%20-sS%20target%20ip%20(1).jpg)

4. Service Version Detection. "nmap -sV "target ip"" command.
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/adf07e603acac6ba721a9d137b47d6d0e49ba418/service%20and%20version%20info/nmap%20-sV%20target%20ip.jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/7569218220a8d014558cd9e3c51f5e0ee8e5196d/service%20and%20version%20info/nmap%20-sV%20target%20ip%20(2).jpg)
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/7e8d776c9c877315ed819da20e284f55600e88b9/service%20and%20version%20info/nmap%20-sV%20target%20ip%20(1).jpg)

4.Operating System Detection. "nmap -o "target ip"" command.
![image alt](https://github.com/AlizadaUlvi/CyberSecurity-lab-2/blob/d243326010ab25c3c13fad38b48616e5e7bc1d7f/OS%20detection/nmap%20-o%20target%20ip.jpg)

