# 🎮 Hamstrong

Hamstrong, **Java Swing** kullanılarak geliştirilmiş bir 2D shooter oyunudur.  
Okul projesi olarak tasarlanmış, eğlenceli ve aksiyon dolu bir deneyim sunar.  

---

## 🕹️ Oyun Hakkında / About the Game

- Ortadaki karakteri **WASD** ile hareket ettiriyoruz.  
- **Mouse** ile nişan alıp, **sol tık** ile ateş edebiliyoruz (ateş etme cooldown mevcut).  
- Düşmanları öldürdükçe **ulti** doluyor.  
- Toplam **13 level**, her level sonunda **shop** açılıyor.  
- Shop'ta karakter ve mermi özellikleri geliştirilebiliyor:  
  - Mermi hızı  
  - Mermi spawn rate  
  - Karakter hızı  
- Tek seferlik satın alınabilen özel yetenekler:  
  - Işınlanma  
  - Görünmezlik (süreli)  
- Düşmanlar:  
  - **Sinek** → oyuncuya değince ölür  
  - **Bomber** → belli mesafeye gelince bomba fırlatır  
- **13. seviyede boss** var, boss öldüğünde oyun sona eriyor  

**English:**  
Hamstrong is a 2D shooter game developed with Java Swing.  
- Move the central character using **WASD**.  
- Aim with **mouse** and shoot with **left click** (shooting has cooldown).  
- Killing enemies fills your **ulti**.  
- **13 levels** in total, shop opens after each level.  
- Upgradeable stats:  
  - Bullet speed  
  - Bullet spawn rate  
  - Character speed  
- One-time purchasable abilities:  
  - Teleportation  
  - Invisibility (temporary)  
- Enemies:  
  - **Fly** → kills player on contact  
  - **Bomber** → throws bomb when close  
- **Boss in level 13**, defeating boss ends the game.  

---

## 🖼️ Ekran Görüntüleri / Screenshots

![Spawn Marker Animation](gifs/spawnMarker.gif)
![Spawn Marker Animation](gifs/boss.gif)
![Spawn Marker Animation](gifs/bomber.gif)
![Spawn Marker Animation](gifs/bomb.gif)
![Spawn Marker Animation](gifs/fly.gif)
![Spawn Marker Animation](gifs/player.gif)

---

## ⚡ Kurulum ve Çalıştırma / Installation & Run

# 1️⃣ GitHub’dan projeyi klonla
git clone https://github.com/fatihozturk10/JAVA-2D-GAME.git

# 2️⃣ Proje src klasörüne gir
cd .\JAVA-2D-GAME\src\

# 3️⃣ Derleme (out klasörüne .class dosyalarını oluştur)
Get-ChildItem -Path . -Filter *.java | ForEach-Object { javac -d ..\out $_.FullName }

# 4️⃣ Proje köküne çık
cd ..

# 5️⃣ Oyunu çalıştır
java -cp out Main

İyi oyunlar.

