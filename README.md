# API Data Scraping www.nomor.net
#### Terdapat 2 API Data Kode POS & Pulau.
## - Base URL:
```bash
https://j4api.my.id
```
## - Menampilkan Semua Data Kode POS

```bash
/web/amp/api/data/nnet/kowil?page=1&limit=15
```
Catatan: ```page``` dan ```limit``` berupa integer.

Response: 
```bash
{
    "total": 83763,
    "per_page": "15",
    "current_page": 1,
    "last_page": 5585,
    "data": [
        {
            "no": 1,
            "kd_pos": "99037",
            "keldes": "Gembileme",
            "kowil": "95.04.32.2006",
            "kec": "Yuneri",
            "kabkot": "Tolikara",
            "prov": "Papua Pegunungan"
        }
    ]
}
```
## - Menampilkan Semua Data Pulau

```bash
/web/amp/api/data/nnet/pulau?page=1&limit=15
```
Catatan: ```page``` dan ```limit``` berupa integer.

Response: 
```bash
{
    "total": 10006,
    "per_page": "15",
    "current_page": 1,
    "last_page": 668,
    "data": [
        {
            "no": 1,
            "nm_pulau": "Pulau Anai",
            "is_bp": "TBP",
            "lintang": "2.4025444",
            "bujur": "140.2327639",
            "kd_pos": "99355",
            "kec": "Yokari",
            "kabkot": "Jayapura",
            "prov": "Papua",
            "kowil": "91.03.40003"
        }
    ]
}
```
