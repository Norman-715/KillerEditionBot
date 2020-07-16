![LukheleBot](https://telegra.ph/file/920497dd2f2333fd15e7a.jpg)
          𝐵𝑜𝑡 𝑝𝑜𝑤𝑒𝑟𝑑 𝑏𝑦 𝑙𝑢𝑘ℎ𝑒𝑙𝑒
# Installing
### The Easy Way37

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### The Normal Way

Simply clone the repository and run the main file:
For make Telegram-String in termux

If First time then you need to install some just copy this , hit enter in termux
(tap to copy)

**Commands by lukhele copy n paste**

`$ termux-setup-storage`

`$ cd $RK`

`$ apt update -y`

`$ apt upgrade -y`

`$ apt install git -y`

`$ git clone https://github.com/Norman-715/KillerEditionBot`

`$ apt install git python -y`

`$ pip install telethon`

**After adding those commands add these**

`$ cd $RK`

`$ cd KillerEditionBot`

`$ python string_session.py`

**Then done..**


__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```

### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Check [Line 111](https://github.com/mredition/raynaldbot/blob/master/userbot/uniborgConfig.py#L111) and start adding your vars there.
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.
