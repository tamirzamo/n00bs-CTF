the message saying that the challenge is gone but the admin has kept a backup.</br>
i googled to search in which names backup files are saved in php ,i tried few.</br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-thirteen/13a.png )</br>

and found link to /levelfourteen.php.old ,inside we see  the misc/imadecoy file and downloaded him after view him in notepad its look like pcap file. </br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-thirteen/13b.png )</br>
using wireshark to open it,and search we find a suspicious picture passed named honeyPY.PNG. </br>
![alt text]( https://github.com/tamirzamo/n00bs-CTF/blob/master/level-thirteen/13c.PNG)</br>
then to see the pic go in wireshark to select File -> Export Object -> HTTP and select the picture </br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-thirteen/13d.png )</br>
which is the key</br>
![alt text](  https://github.com/tamirzamo/n00bs-CTF/blob/master/level-thirteen/HoneyPY.PNG)</br>
