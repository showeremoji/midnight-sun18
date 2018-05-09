## Hashcash

Apparently the intended solution was some buffer overflow attack. However, there is a hash that has enough leadning zeros: `08ni(g0u3ada_JiyongYoun-HLETRD` found on [0xf.kr/md5/](http://0xf.kr/md5/) We can then just search over the nonce, until we get the right one.
