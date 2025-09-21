# Web-Scraper-CSV
# Python Web Scraper + CSV Export

Bu proje, BeautifulSoup ve Requests kütüphanelerini kullanarak bir web sitesinden (örnek: [Hacker News](https://news.ycombinator.com/)) haber başlıklarını çeker ve verileri CSV dosyasına kaydeder.

## Özellikler
- Web sitesinden haber başlıklarını ve linklerini çeker
- Çekilen verileri `news.csv` dosyasına kaydeder
- UTF-8 desteği ile Türkçe karakterlerde sorun yaşamaz
- Basit ve hızlı çalışır

## Kullanılan Teknolojiler
- Python 3.x
- [Requests](https://pypi.org/project/requests/) → HTTP istekleri
- [BeautifulSoup (bs4)](https://pypi.org/project/beautifulsoup4/) → HTML parsing
- [CSV](https://docs.python.org/3/library/csv.html) → Dosya kaydetme

## Kurulum ve Çalıştırma

1. Python 3 kurulu olduğundan emin olun  
   [Python indir](https://www.python.org/downloads/)

2. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install requests beautifulsoup4
