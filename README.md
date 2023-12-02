# WebCord
Finally, a Discord web client requiring only a token and a channel ID
# About this project
WebCord comes with exciting features.

• Automatic refreshing

• Support emojis

• Support for attached images

• Viewing all your servers

# ToDo list

• Support files

• Parse links

• Support multiple images

# For use at work/school

This will only work if Discord is blocked with an extension and not through the internet network itself. If Discord is blocked through the internet, this will NOT work!

If you are blocked through a router firewall, use a VPN.

First, to begin using this, I'd advise you to begin creating your own "Contacts Spreadsheet", containing your token and people to contact. First you need your token. I will not be explaining how to do this. There are many ways to find your token. For the contacts you just click on your DM history with them and copy the numbers at the end of the url (eg. 454092365167198229).

# IFrame bookmark

DMS:

javascript:var body = document.getElementsByTagName("body")[0]; var newHx = document.createElement("iframe"); newHx.src = "https://hotpizzayt.github.io/webcord/dms/"; newHx.width = screen.width; newHx.height = screen.height; body.appendChild(newHx);

Normal

javascript:var body = document.getElementsByTagName("body")[0]; var newHx = document.createElement("iframe"); newHx.src = "https://hotpizzayt.github.io/webcord"; newHx.width = screen.width; newHx.height = screen.height; body.appendChild(newHx);

# The iFrame bookmark doesn't work!

This is unfortunate news to people who use Securly, because Securly blocks all iFrame requests. Fortunately there is a solution! Go in this repository and open `bookmarklets.md` for information on how to get WebCord embedded on any site! Note that these will have to be updated every API change. (ex. update from v9 to v10) This is also assuming that Securly doesn't also block network request too. I don't go to school so I don't know.
