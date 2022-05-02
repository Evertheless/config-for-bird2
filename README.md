# config-for-bird2

AS131171的漏油记录
**注意，本repo仅供参考，若不了解原理就盲目复制的话是什么也学不到的**
_Note that this repo is for reference only, please try to avoid blindly copying the content._

欢迎各位大佬peer！

contact: mirai@evertheless.art

## Usage

- Git files to local.
```
git clone https://github.com/Evertheless/config-for-bird2.git
cd config-for-bird2
```

- Modify the files to match the server configuration (like ip, routing, bgp, etc.)

- Change dos newline format to unix format to avoid "unknown character" error.

```
apt install dos2unix
find . -name "*" | xargs dos2unix
```

- Run bird with config.
```
bird -c bird.conf
```
