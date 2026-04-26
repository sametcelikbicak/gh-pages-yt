# GitHub Pages Nasıl Kullanılır? - YouTube Videosu Örneği

Bu repo, GitHub Pages'ın nasıl kullanıldığını gösteren bir YouTube videosu için örnek olarak oluşturulmuştur. React ve Vite kullanılarak hazırlanmış basit bir proje ile GitHub Pages'e deploy işlemini adım adım öğrenebilirsiniz.

## İlgili YouTube Videosu

Bu repo'nun anlatıldığı YouTube videosunu aşağıdan izleyebilirsiniz:

[![GitHub Actions kullanarak Projeyi GitHub Pages ile yayına alma](https://img.youtube.com/vi/l6J8xgA7Afg/0.jpg)](https://youtu.be/l6J8xgA7Afg)

## Kurulum ve Çalıştırma

1. Bağımlılıkları yükleyin:

   ```bash
   npm install
   ```

2. Geliştirme sunucusunu başlatın:

   ```bash
   npm run dev
   ```

3. Build almak için:
   ```bash
   npm run build
   ```

## GitHub Pages'e Deploy Etme

Bu proje GitHub Pages için optimize edilmiştir. Deploy etmek için:

1. Repo'yu GitHub'a push edin.
2. Repository ayarlarından **Settings > Pages** bölümüne gidin.
3. **Source** olarak **GitHub Actions** seçin.
4. Eğer GitHub Actions workflow'u yoksa, manuel olarak ekleyebilirsiniz veya Vite'nin build çıktısını `dist` klasöründen `gh-pages` branch'ine push edin.
