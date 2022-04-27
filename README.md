# Config-For-Bird2

AS131171的漏油记录

欢迎各位大佬peer！

contact: mirai@evertheless.art

**Usage**

- Git files to local.
```
git clone https://github.com/Evertheless/Config-For-Bird2.git
```
- Modify the files to match the server configuration (like ip, routing, bgp, etc.)
- Change dos newline format to unix format to avoid "unknown character" error.

```
apt install dos2unix
find . -name * | xargs dos2unix
```
- Run bird with config
```
bird -c bird.conf
```
