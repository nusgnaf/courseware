https://www.uuidgenerator.net
https://toutyrater.github.io/prep/
https://www.v2ray.com/chapter_02/protocols/http.html

先运行v2ray.sh

```shell
./v2ray.sh
cd /etc/v2ray/

cp config.json config.json.backup

rm config.json

nano config.json

{
  "inbounds": [{        
    "port": 41688,      
    "protocol": "vmess",
    "settings": {
      "clients": [
        {
          "id": "19411e59-1dae-493a-a790-8be59f4d3ffd",
          "alterId": 4
        }
      ]
    }
  },
  {
    "port": 42688,
    "protocol": "vmess",
    "settings": {
      "clients": [
        {
          "id": "8f2ebff4-28e7-48aa-820a-ea2add93f4ab",
          "alterId": 4
        }
      ]
    }
  },
  {
    "port": 43688,
    "protocol": "vmess",
    "settings": {
      "clients": [
        {
          "id": "85fa6571-76fc-463b-8c9e-e3a1f8e345eb",
          "alterId": 4
        }
      ]
    }
  },
  {
    "port": 44688,
    "protocol": "vmess",
    "settings": {
      "clients": [
        {
          "id": "cbad767c-8f74-40c7-9e09-6d9d598053b1",
          "alterId": 4
        }
      ]
    }
  },
  {
    "port": 45688,
    "protocol": "vmess",
    "settings": {
      "clients": [
        {
          "id": "9f547a4e-50f0-454e-b1a3-5c923f34069e",
          "alterId": 4
        }
      ]
    }
  },
  {
      "port": 26688,
      "protocol": "shadowsocks",
      "settings": {
        "method": "chacha20-ietf-poly1305",
        "ota": false,
        "password": "he11o*asdteji"
      }
   },
   {
      "port": 47688,
      "protocol": "shadowsocks",
      "settings": {
        "method": "chacha20-ietf-poly1305",
        "ota": false,
        "password": "htop@4869a.dh#$"
      }
   },
   {
      "port": 48688,
      "protocol": "shadowsocks",
      "settings": {
        "method": "chacha20-ietf-poly1305",
        "ota": false,
        "password": "htop@4869c.^&*"
      }
   },
   {
      "port": 49688,
      "protocol": "shadowsocks",
      "settings": {
        "method": "chacha20-ietf-poly1305",
        "ota": false,
        "password": "@#ahsf.?Y&*"
      }
   },
   {
      "port": 50788,
      "protocol": "shadowsocks",
      "settings": {
        "method": "chacha20-ietf-poly1305",
        "ota": false,
        "password": "he11oJack&*%$}"
      }
   }
  ],
  "outbounds": [{
    "protocol": "freedom",
    "settings": {}
  }
  ]
}
```

