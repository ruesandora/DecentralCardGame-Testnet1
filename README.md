# Crowd Control Testnet Rehberi:

Arkadaşlar ödül hakkında bilgi yok, yakında duyururlar olursa, ücretsiz sunucularada kurulduğu için paylaşıyorum, Katılımı çok basit olduğu için kısa geçiyorum:

# Telegram: https://t.me/CrowdControlTurkish

# Gereksinimler:
```
2 CPU
4GB RAM
30 GB SSD
```

Not: en minimum gereksinimler bunlar, mümkünse min 50 GB SSD kullanın.

# Kurulum:
```
git clone https://github.com/DecentralCardGame/Testnet1 && chmod +x ./Testnet1/Cardchain_install.sh && chmod +x ./Testnet1/Cardchain_remove.sh && ./Testnet1/Cardchain_install.sh
```

# Silmek için:
```
./Testnet1/Cardchain_remove.sh
```

# Tek kurulum komutu ile validator oluşturuyoruz, komutu girdikten sonra Validator ismi soracaktır:

![image](https://user-images.githubusercontent.com/101149671/178354201-a733fce2-9f84-4aef-963c-ad48b7601319.png)

# Sync durumuna bakma:
```
curl -s localhost:26657/status | jq .result.sync_info
```

# Güncel blok: https://cardchain.crowdcontrol.network/tendermint/block?height=

![image](https://user-images.githubusercontent.com/101149671/178354446-53a6d0c2-748d-4f7b-8d12-fb2bdf5fad13.png)


Şimdilil bu kadar.. devamı gelirse güncellerim.

# Hesaplar:

[<img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" width="16px"> Twitter   ](https://twitter.com/Ruesandora0) 

[<img src="https://cdn-icons-png.flaticon.com/512/1336/1336494.png" width="16px"> Forum   ](https://forum.rues.info/index.php)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Announcement   ](https://t.me/RuesAnnouncement)

[<img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="16px"> Telegram Chat   ](https://t.me/RuesChat)

[Discord](https://discord.gg/ruescommunity)
