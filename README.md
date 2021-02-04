# luci-app-smstools3

Web UI smstools3 for OpenWrt LuCI.
How-to compile:
```
cd feeds/package/net
git clone https://github.com/koshev-msk/luci-app-smstools3.git
cd ../../..
./scripts feeds update -a; ./scripts/feeds install -a
make -j $(($(nproc)+1)) package/feeds/luci/luci-app-smstools3/compile
```
<details>
   <summary>Screenshots</summary>
   ![](https://raw.githubusercontent.com/koshev-msk/luci-app-smstools3/master/screenshots/incoming.png)
   
   ![](https://raw.githubusercontent.com/koshev-msk/luci-app-smstools3/master/screenshots/outcoming.png)
   
   ![](https://raw.githubusercontent.com/koshev-msk/luci-app-smstools3/master/screenshots/push.png)
   
   ![](https://raw.githubusercontent.com/koshev-msk/luci-app-smstools3/master/screenshots/setup.png)
</details>
