## Nexus Prover Node

İster Web üzerinden, ister CLI ile, istersek de Chromium sekmelerinde açarak Nexus ekosistemine katkıda bulunup NEX puanları kazanacağız.

# Sistem gereksinimleri 

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4 |
| **RAM**          | 8 GB                     |
| **Storage**      | 50 GB SDD                   |
| **Network**      | 100 Mbps  |

# 

# Nexus Hesabı Açma

- Siteye gidelim https://app.nexus.xyz/
- Mail ile hesap açalım
- Giriş yapalım
- İsterseniz ayarlardan mail ile açılan cüzdanı, kendi cüzdanınızın içine aktarabilirsiniz

# Web ile Katkıda Bulunma
- Aynı hesap ile giriş yapıp, çıkan sayfada "Connect to Nexus"a basarsak Web üzerinden puan kazanma işlemi aktifleşir.

# CLI ile Katkıda Bulunma 
- Docker
```
sudo apt update & sudo apt upgrade -y
sudo apt install screen curl libssl-dev pkg-config build-essential git-all protobuf-compiler -y
sudo apt update
```
- Rust
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
``` 
rustup target add riscv32i-unknown-none-elf
```
- Nexus 
```
curl https://cli.nexus.xyz/ | sh
```

Buradan sonra ekrana gelenlere Y diyelim. Node ID için https://app.nexus.xyz/ sitesine gidip Node ID'yi alıp yapıştıralım.

Eğer ki ``Killed`` hatası alıyorsanız RAM yetmiyor demektir.