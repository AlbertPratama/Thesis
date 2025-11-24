# Thesis


## Sources and scraping commands for X posts and comments related to 17+5 Tuntutan Rakyat


## 1. Menteri Keuangan (Menkeu) Purbaya Yudhi Sadewa menyampaikan permintaan maaf soal pernyataannya yang merespon terkait tuntutan 17+8
```
python3 scrape_quotes_X.py "https://x.com/RadioElshinta/status/1965298846902386728/quotes" \
        --count 896 \
        --cookies cookies.json

python3 scrape_comment_X.py "https://x.com/RadioElshinta/status/1965298846902386728/" \
        --cookies cookies.json \
        --count 473
```


## 2. Anggota Kolektif 17+8 Indonesia Berbenah
```
python3 scrape_quotes_X.py "https://x.com/tempodotco/status/1967037974971109397/quotes" \
        --count 896 \
        --cookies cookies.json

python3 scrape_comment_X.py "https://x.com/tempodotco/status/1967037974971109397/" \
        --cookies cookies.json \
        --out "data_comments_crawled/Anggota Kolektif 17+8 Indonesia Berbenah.csv" \
        --count 473
```

## 3. Menteri Keuangan Purbaya Yudhi Sadewa meminta maaf soal komentarnya mengenai tuntutan 17+8
```
python3 scrape_quotes_X.py "https://x.com/NarasiNewsroom/status/1965371452435399033/quotes" \
        --count 61 \
        --cookies cookies.json

python3 scrape_comment_X.py "https://x.com/NarasiNewsroom/status/1965371452435399033/" \
        --cookies cookies.json \
        --out "data_comments_crawled/Menteri Keuangan Purbaya Yudhi Sadewa meminta maaf soal komentarnya mengenai tuntutan 17+8.csv" \
        --count 101
```



## 4. 17 tuntutan dalam 1 minggu + 8 tuntutan dalam 1 tahun
```
python3 scrape_quotes_X.py "https://x.com/senjatanuklir/status/1962191825768460378/quotes" \
        --count 1000 \
        --cookies cookies.json \
        --out "data_quotes_crawled/17 tuntutan dalam 1 minggu + 8 tuntutan dalam 1 tahun.csv"

python3 scrape_comment_X.py "https://x.com/senjatanuklir/status/1962191825768460378/" \
        --cookies cookies.json \
        --out "data_comments_crawled/17 tuntutan dalam 1 minggu + 8 tuntutan dalam 1 tahun.csv" \
        --count 1000
```

## 5. 7+8 Tuntutan Rakyat dalam seminggu dan setahun (dengan deadline)
```
python3 scrape_quotes_X.py "https://x.com/senjatanuklir/status/1962191687750684956/quotes" \
        --count 1000 \
        --cookies cookies.json \
        --out "data_quotes_crawled/7+8 Tuntutan Rakyat dalam seminggu dan setahun (dengan deadline).csv"

python3 scrape_comment_X.py "https://x.com/senjatanuklir/status/1962191687750684956/" \
        --cookies cookies.json \
        --out "data_comments_crawled/7+8 Tuntutan Rakyat dalam seminggu dan setahun (dengan deadline).csv" \
        --count 1000
```


## 6. 17 tuntutan rakyat dalam satu minggu ke depan, dan 8 tuntutan rakyat dalam satu tahun ke depan
```
python3 scrape_quotes_X.py "https://x.com/Adriandhy/status/1962377503844274592/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/17 tuntutan rakyat dalam satu minggu ke depan, dan 8 tuntutan rakyat dalam satu tahun ke depan.csv"

python3 scrape_comment_X.py "https://x.com/Adriandhy/status/1962377503844274592/" \
        --cookies cookies_2.json \
        --out "data_comments_crawled/17 tuntutan rakyat dalam satu minggu ke depan, dan 8 tuntutan rakyat dalam satu tahun ke depan.csv" \
        --count 1000
```


## 7. Kakak OJOL ini ternyata lebih cerdas, lebih waras daripada influencer yang suka demo dengan tuntutan 17+8
```
python3 scrape_quotes_X.py "https://x.com/G0LIATH87/status/1965648953824911464/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/Kakak OJOL ini ternyata lebih cerdas, lebih waras daripada influencer yang suka demo dengan tuntutan 17+8.csv"

python3 scrape_comment_X.py "https://x.com/G0LIATH87/status/1965648953824911464/" \
        --cookies cookies.json \
        --out "data_comments_crawled/Kakak OJOL ini ternyata lebih cerdas, lebih waras daripada influencer yang suka demo dengan tuntutan 17+8.csv" \
        --count 1000
```

## 8. Di antara tuntutan 17+8 juga menggema “Indonesia reset”.
```
python3 scrape_quotes_X.py "https://x.com/tempodotco/status/1968199206994317522/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/Di antara tuntutan 17+8 juga menggema “Indonesia reset”.csv"

python3 scrape_comment_X.py "https://x.com/tempodotco/status/1968199206994317522/" \
        --cookies cookies.json \
        --out "data_comments_crawled/Di antara tuntutan 17+8 juga menggema “Indonesia reset”.csv" \
        --count 1000
```

## 9. KONFERENSI PERS TUNTUTAN 17+8.
```
python3 scrape_quotes_X.py "https://x.com/barengwarga/status/1963513836599980379/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/KONFERENSI PERS TUNTUTAN 17+8.csv"

python3 scrape_comment_X.py "https://x.com/barengwarga/status/1963513836599980379/" \
        --cookies cookies.json \
        --out "data_comments_crawled/KONFERENSI PERS TUNTUTAN 17+8.csv" \
        --count 1000
```

## 10. DPR to hold meeting with factions today following nationwide protests over 17+8 demands.
```
python3 scrape_quotes_X.py "https://x.com/IndoPopBase/status/1963481988507340806/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/DPR to hold meeting with factions today following nationwide protests over 17+8 demands.csv"

python3 scrape_comment_X.py "https://x.com/IndoPopBase/status/1963481988507340806/" \
        --cookies cookies.json \
        --out "data_comments_crawled/DPR to hold meeting with factions today following nationwide protests over 17+8 demands.csv" \
        --count 1000
```

## 11. ‘17+8 Tuntutan Rakyat’ have been released.
```
python3 scrape_quotes_X.py "https://x.com/IndoPopBase/status/1962361386916577303/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/‘17+8 Tuntutan Rakyat’ have been released.csv"

python3 scrape_comment_X.py "https://x.com/IndoPopBase/status/1962361386916577303/" \
        --cookies cookies.json \
        --out "data_comments_crawled/‘17+8 Tuntutan Rakyat’ have been released.csv" \
        --count 1000
```

## 12. “Saya kira ini masuk akal,” ujar Presiden Prabowo Subianto.
```
python3 scrape_quotes_X.py "https://x.com/NarasiNewsroom/status/1964945538232815871/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/“Saya kira ini masuk akal,” ujar Presiden Prabowo Subianto.csv"

python3 scrape_comment_X.py "https://x.com/NarasiNewsroom/status/1964945538232815871/" \
        --cookies cookies.json \
        --out "data_comments_crawled/“Saya kira ini masuk akal,” ujar Presiden Prabowo Subianto.csv" \
        --count 1000
```

## 13. DPR RI menanggapi 17+8 Tuntutan Rakyat dengan mengeluarkan enam poin keputusan.
```
python3 scrape_quotes_X.py "https://x.com/kompascom/status/1963941370567233651/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/DPR RI menanggapi 17+8 Tuntutan Rakyat dengan mengeluarkan enam poin keputusan.csv"

python3 scrape_comment_X.py "https://x.com/kompascom/status/1963941370567233651/" \
        --cookies cookies.json \
        --out "data_comments_crawled/DPR RI menanggapi 17+8 Tuntutan Rakyat dengan mengeluarkan enam poin keputusan.csv" \
        --count 1000
```

## 14. DPR Rapat Bahas 17+8 Tuntutan Rakyat Hari Ini.
```
python3 scrape_quotes_X.py "https://x.com/CNNIndonesia/status/1963399715590152473/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/DPR Rapat Bahas 17+8 Tuntutan Rakyat Hari Ini.csv"

python3 scrape_comment_X.py "https://x.com/CNNIndonesia/status/1963399715590152473/" \
        --cookies cookies.json \
        --out "data_comments_crawled/DPR Rapat Bahas 17+8 Tuntutan Rakyat Hari Ini.csv" \
        --count 1000
```

## 15. Masalah w sama tuntutan 17+8 cuma satu.
```
python3 scrape_quotes_X.py "https://x.com/anggapph2/status/1962682299256053822/quotes" \
        --count 1000 \
        --cookies cookies_2.json \
        --out "data_quotes_crawled/Masalah w sama tuntutan 17+8 cuma satu.csv"

python3 scrape_comment_X.py "https://x.com/anggapph2/status/1962682299256053822/" \
        --cookies cookies.json \
        --out "data_comments_crawled/Masalah w sama tuntutan 17+8 cuma satu.csv" \
        --count 1000
```