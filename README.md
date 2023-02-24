# misp-docker
Since one doesnt really exist I created a single docker compose file that will bring up a MISP instance.

---

Edit ```docker-compose.yml```

**⁉[Essential]**<br>Change the IP address ```10.0.0.0``` to match your environment.<br><br>
**[Reccomended]**<br>Change the default ***Usernames*** and ***Passwords***.<br><br>
**[Reccomended]**<br>Change the file paths ```/home/user/MISP/data``` to match your environment.<br><br>

---

Then run ```docker compose up -d``` and away you go.

Simple as that!
