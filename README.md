
# Twitch Follower Bot Farmer (Twitch-Farmer)

Twitch Farmer is a bot that helps you to get more followers.
Twitch Farmer presents the solution, by offering all the needed features, to boost your channel in the ranks, while maintaining a natural look to other real viewers.


---

## Requirements

* **python** version >= **3.7.0** installed

## Installation

```bash
git clone https://github.com/deepsingh132/twitchBot.git

cd Twitch-Farmer

pip3 install selenium pandas

python3 twitch_farmer.py
```

## Usage

In order for the bot to run, you need to add at least one account to the accounts.csv file located in the _data_ folder.

You only need to specify the **username** and **password**, the **following_channel** and **used_proxy** columns are filled by the bot for _log_ purposes.

|**username**|**password**|**following_channel**|**used_proxy**|
|---|---|---|---|
|_root_|_toor_|||

---

Besides accounts.csv file you also need too specify the proxies in the  proxies.csv file located in the _data_ folder.

You only need to specify the **proxy**. The **status** column is filled by the bot for _log_ purposes.

|proxy|status|
|---|---|
|_192.168.0.1:3000_||
