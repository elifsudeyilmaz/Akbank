Metro Ağı Rota Bulucu

Bu proje, bir metro ağı üzerinde en az aktarmalı ve en hızlı rotayı bulmak için geliştirildi.

Kullanılan Teknolojiler ve Kütüphaneler

Python 3 kullanıldı ve collections kütüphanesinde defaultdict ile hatlar ve istasyonlar organize edilirken, deque BFS algoritmasında kuyruk olarak kullanıldı. heapq, A* algoritmasında öncelikli kuyruk olarak yer aldı ve typing tip belirtimleri için kullanıldı.

Algoritmaların Çalışma Mantığı

En Az Aktarmalı Rota (BFS Algoritması)

BFS (Breadth-First Search) algoritması kullanılarak başlangıç istasyonundan komşu istasyonlara genişleyerek ilerlenir ve en az aktarmalı rota garanti edilir, ancak en hızlı rota olmayabilir.

En Hızlı Rota (A* Benzeri Dijkstra Algoritması)

A* ve Dijkstra algoritmalarının birleşimi kullanılarak en kısa sürede gidilecek rota bulunur, fakat BFS'ye göre hesaplama süresi daha uzun olabilir.

Örnek Kullanım ve Testler

AŞTİ'den OSB'ye

En Az Aktarmalı Rota: AŞTİ -> Kızılay -> Ulus -> Demetevler -> OSB

En Hızlı Rota: AŞTİ -> Kızılay -> Ulus -> Demetevler -> OSB (20 dk)

Batıkent'ten Keçiören'e

En Az Aktarmalı Rota: Batıkent -> Demetevler -> Gar -> Keçiören

En Hızlı Rota: Batıkent -> Demetevler -> Gar -> Keçiören (21 dk)

Proje Geliştirme Fikirleri

Harita desteği eklenebilir, trafik ve yoğunluk bazlı tahminler yapılabilir, ayrıca mobil ve web uygulaması geliştirilebilir.
