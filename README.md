# Balatro Türkçe Yerelleştirmesi
[Türkçe](#türkçe) | [English](#english)

## Türkçe
Bu proje, **Balatro** için hazırlanmış ve bakımı sürdürülen gayriresmî bir Türkçe yerelleştirmedir.

Projenin amacı, Balatro'nun kartlarını, Joker'lerini, açıklamalarını, menülerini, eğitimlerini ve diğer oyun içi metinlerini tutarlı, doğal ve akıcı bir Türkçe ile sunmaktır.

### Proje Bilgileri
- **Dil:** Türkçe
- **Balatro Sürümü:** 1.0.1o
- **Çeviri Durumu:** 100%
- **Platformlar:** Windows ve macOS
- **Proje Sorumlusu:** [sinany2b](https://github.com/sinany2b)

### Yerelleştirme Kuralları
- Oyun genelinde tutarlı terim ve ifade kullanımı
- Oyun arayüzüne uygun, okunabilir metinler
- Türkçe dil bilgisine ve cümle yapısına uygunluk
- Kelime oyunlarının, mizahın ve göndermelerin anlamını koruma

### Kurulum
Uyarı: İşleme başlamadan önce oyun dosyalarının yedeğini alın. Bu kurulum sırasında oyunun orijinal dosyalarında değişiklik yapılacağından, işletim sisteminiz veya güvenlik yazılımlarınız bu değişiklikleri güvenlik riski olarak algılayabilir.

#### Windows
1. Oyunun kurulu olduğu klasörü açın.
2. `Balatro.exe` dosyasını bulun ve sağ tıklayın.
3. **7-Zip → Arşivi aç** seçeneğini seçin. ([7-Zip](https://www.7-zip.org) programınız yok ise ücretsiz kurun.)
4. `game.lua` dosyasını seçerek sağ tıklayın ve Düzenle seçeneğini seçin.
5. Açılan metin düzenleyicisinde `['zh_CN']` kelimesini arayın, üstüne boş bir satır ekleyin ve aşağıdaki kod satırını yapıştırın.
    ```
    ['tr'] = {font = 1, label = "Türkçe", key = 'tr', beta = nil, button = "Dil Geribildirimi", warning = {'Bu dil henüz beta aşamasındadır. Çeviriyi geliştirmemizde','bize yardımcı olmak için lütfen geribildirim tuşunu kullanın.', 'Onaylamak için tuşa tekrar basın'}},
    ```
6. Dosyayı üzerine kaydederek kapatın.
7. 7-zip içindeki localization klasörüne tıklayın.
8. İndirdiğiniz `tr.lua` dosyasını `localization` klasörü içine sürükleyip bırakın.
9. 7-zip programını kapatın ve dosyaların üzerine yazılmasını onaylayın

#### macOS
1. `Balatro` uygulama dosyasına sağ tıklayın.
2. Paket içeriğini göster seçeneğini seçin.
3. `Contents/Resources/game` klasörü içine gidin.
4. `game.lua` dosyasını masaüstünüze kopyalayın ve [CotEditor](https://github.com/coteditor/CotEditor) veya benzeri bir  metin düzenleyicide açın.
5. Açılan metin düzenleyicisinde `['zh_CN']` kelimesini arayın, üstüne boş bir satır ekleyin ve aşağıdaki kod satırını yapıştırın.
    ```
    ['tr'] = {font = 1, label = "Türkçe", key = 'tr', beta = nil, button = "Dil Geribildirimi", warning = {'Bu dil henüz beta aşamasındadır. Çeviriyi geliştirmemizde','bize yardımcı olmak için lütfen geribildirim tuşunu kullanın.', 'Onaylamak için tuşa tekrar basın'}},
    ```
6. Dosyayı üzerine kaydederek kapatın.
7. Düzenlediğiniz `game.lua` dosyasını, oyunun `Contents/Resources/game` klasöründeki orijinal dosyanın üzerine kopyalayın ve değiştirme işlemini onaylayın.
8. Contents/Resources/game/localization klasörü içine girin ve indirdiğiniz tr.lua dosyasını sürükleyip bırakın.

### Geri Bildirim ve Katkıda Bulunma
Bir çeviri hatası mı buldun veya bir önerin mi var? GitHub deposunda bir Issue açabilir ya da resmî Balatro Discord sunucusunun Türkçe dil kanalında geri bildirimde bulunabilirsin.

### Lisans
Bu projede yer alan özgün Türkçe çeviri ve yerelleştirme çalışmaları [sinany2b](https://github.com/sinany2b) tarafından hazırlanmış olup topluluğun kişisel kullanımı için ücretsiz olarak erişime sunulmaktadır.

Bu projedeki çeviri dosyaları ve bunların içerdiği Türkçe çeviri metinleri ticari amaçlarla kullanılamaz veya satılamaz. Çevirinin tamamı ya da bir bölümü, izin alınmadan yeniden yayımlanamaz veya değiştirilerek başka bir proje altında sunulamaz. Proje dosyaları, bu GitHub deposu dışında başka platformlarda veya sunucularda paylaşılamaz.

Bu proje, LocalThunk veya Playstack ile bağlantılı değildir ve onlar tarafından onaylanmamıştır.

Balatro ve oyuna ait özgün içeriklerin tüm hakları ilgili hak sahiplerine aittir.

## English
This is an unofficial Turkish localization for **Balatro**.

The goal of this project is to provide a consistent, natural, and fluent Turkish translation of Balatro's cards, Jokers, descriptions, menus, tutorials, and other in-game text.

### Project Info
- **Language:** Turkish
- **Balatro Version:** 1.0.1o
- **Translation Status:** 100%
- **Platforms:** Windows and macOS
- **Maintainer:** [sinany2b](https://github.com/sinany2b)

### Localization Guidelines
- Consistent terminology and phrasing throughout the game
- Readable text suited to the game's interface
- Adherence to Turkish grammar and sentence structure
- Preserving the meaning of wordplay, humor, and references

### Installation
**Warning:** Back up your game files before proceeding. This installation requires modifying the game's original files, which may cause your operating system or security software to flag these changes as a potential security risk.

#### Windows
1. Open the folder where the game is installed.
2. Find `Balatro.exe` and right-click it.
3. Select **7-Zip → Open archive**. (If you don't have 7-Zip installed, you can download it for free from the [official website](https://www.7-zip.org/).)
4. Right-click `game.lua` and select **Edit**.
5. In the text editor that opens, search for `['zh_CN']`. Insert a blank line above it and paste the following line of code.
    ```
    ['tr'] = {font = 1, label = "Türkçe", key = 'tr', beta = nil, button = "Dil Geribildirimi", warning = {'Bu dil henüz beta aşamasındadır. Çeviriyi geliştirmemizde','bize yardımcı olmak için lütfen geribildirim tuşunu kullanın.', 'Onaylamak için tuşa tekrar basın'}},
    ```
6. Save the file and close the editor.
7. Open the `localization` folder inside 7-Zip.
8. Drag and drop the downloaded `tr.lua` file into the `localization` folder.
9. Close 7-Zip and confirm overwriting the existing files when prompted.

#### macOS
1. Right-click the Balatro application.
2. Select **Show Package Contents**.
3. Navigate to `Contents/Resources/game`.
4. Copy `game.lua` to your Desktop and open it with [CotEditor](https://github.com/coteditor/CotEditor) or a similar text editor.
5. In the text editor, search for `['zh_CN']`. Insert a blank line above it and paste the following line of code.
    ```
    ['tr'] = {font = 1, label = "Türkçe", key = 'tr', beta = nil, button = "Dil Geribildirimi", warning = {'Bu dil henüz beta aşamasındadır. Çeviriyi geliştirmemizde','bize yardımcı olmak için lütfen geribildirim tuşunu kullanın.', 'Onaylamak için tuşa tekrar basın'}},
    ```
6. Save the file and close the editor.
7. Copy the edited `game.lua` file back into the game's `Contents/Resources/game` folder, replacing the original file.
8. Navigate to `Contents/Resources/game/localization` and drag and drop the downloaded `tr.lua` file into the folder.

### Feedback and Contributions
Found a translation error or have a suggestion? You can open an Issue in this GitHub repository or share your feedback in the Turkish language channel on the official Balatro Discord server.

### License
The original Turkish translation and localization work in this project was created by [sinany2b](https://github.com/sinany2b) and is made freely available for the community's personal use.

The translation files and the Turkish text contained within them may not be used for commercial purposes or sold. The translation, in whole or in part, may not be republished without permission or modified and distributed as part of another project. Project files may not be shared on other platforms or servers outside this GitHub repository.

This project is not affiliated with or endorsed by LocalThunk or Playstack.

All rights to Balatro and its original content belong to their respective rights holders.
