# Vast.Ai-oBTC-miner

Guide:

1) Make sure you have selected the right image
![image](https://user-images.githubusercontent.com/75716744/158411770-cf57a9e6-e8f3-4923-bb82-e51804cc6588.png)
![image](https://user-images.githubusercontent.com/75716744/158411918-60ab8f65-0997-4d92-9ec0-c2214c756906.png)


2) Bid on a rig and ssh into it

3) Run:
``curl -O https://raw.githubusercontent.com/the-red-eye-studio/Vast.Ai-oBTC-miner/main/zip.zip && apt-get install zip unzip && unzip zip.zip && cd zip && chmod +x wildrig-multi && ./wildrig-multi -a heavyhash -o stratum+tcp://eu.mecrypto.club:7075 -u bc1qw0agkf0py3767h353lg9qz0r6smlsgz6uaq7r5.RIGNAME -p c=OBTC,m=solo``

(Make sure to edit the wallet/pool/rig-name/pass)


Happy mining!
