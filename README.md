# telegram-pm-bot
Ruang Chat perbualan antara Kita sebagai BOT dengan Pengguna biasa

Berdasar Ciptaan [telegram-pm-chat-bot](https://github.com/Netrvin/telegram-pm-chat-bot).


## KEMASUKAN FILE DATA
PERSEDIAAN PERTAMA:KATA ARAH
- python 3
- pip

 JANAKAN KEMASUKAN DATA:
```bash
pip install python-telegram-bot --upgrade
```


## Config
modify those on `/config.json` :
```c
{
    "Admin": 0,       // ID of admin account (number id)
    "Token": "",      // Token of bot
    "Lang": "en"      // name of the lang file
}
```


## Start
```bash
python main.py
```


## Directive
| command         | function                                   | parameter                                  |
| :---            | :---                                       | :---                                       |
| say             | start conversation                         | /say                                       |
| done            | end conversation                           | /done                                      |
| receipt_switch  | enable or disable receipt                  | /receipt_switch                            |
| messege_info    | info of the messege you point (admin only) | /messege_info                              |
| version         | version of bot                             | /version                                   |
