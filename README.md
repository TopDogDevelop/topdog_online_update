# topdog_online_update

GitHub 闈欐€佷粨鍙仛**瀵煎悜**锛氱湡姝ｇ儹鏇磋祫婧愬湪 Hugging Face Bucket銆?
褰撳墠鍐呭鐗堝彿锛?*2026.7.12.v2**

| 鐢ㄩ€?| URL |
|------|-----|
| HF 妗讹紙璧勬簮鏈綋锛?| https://huggingface.co/buckets/liketocode789/topdog_online_update_data |
| 瀹㈡埛绔储鍙栧熀鍧€锛坮esolve锛?| https://huggingface.co/buckets/liketocode789/topdog_online_update_data/resolve/ |
| 鏈粨 version 鎸囬拡 | [version.json](version.json) |

## 鍗忚

1. GET {resolve}/version.json
2. GET {resolve}/manifest.json
3. 鎸夋竻鍗曚笅杞?content/**锛坰ha256 鏍￠獙锛?
鐗堝彿鏍煎紡 `YYYY.M.D.vN`锛涜仈鏈哄弻鏂规湰鍦扮増鍙烽』涓€鑷淬€?
鍙戝竷锛?
`powershell
cd e:\game_dev\top_dog_unity
.\scripts\publish_online_update.ps1 -Version 2026.7.12.v2 -Push
`
