Для анализа генома на предмет наличия Z-ДНК был выбран тип *Apicomplexa*, род *Plasmodium*.

Данные по видам *P. falciparum*, *P. vivax*, *P. knowlesi*, *P. gaboni*, *P. yoelii* (INSDC) были скачаны с https://www.ncbi.nlm.nih.gov/genome/browse#!/eukaryotes/refseq_category:representative и https://ftp.ncbi.nlm.nih.gov/genomes/all/GCA. Причём файлы .fasta и .gb были скачаны из браузера NCBI с помощью скрипта на bash, по одному файлу на хромосому: итого 70 .fasta файлов и 70 .gb файлов. Файлы же feature_table.txt были скачаны через ftp.

|Вид|Число хромосом|Длина генома|Количество анн. генов|Доля анн. генов на геном|Число участков со значимым ZH_SCORE*|Длина участков со значимым ZH-SCORE*|
|-|-|-|-|-|-|-|
|*P. falciparum*|14**||||||
|*P. vivax*|14||||||
|*P. gaboni*|14||||||
|*P. knowlesi*|14**||||||
|*P. yoelii*|14**||||||

* А именно с ZH-SCORE >= 500.
** Помимо 14 хромосом имелись также данные по митохондриальному геному и геному апикопласта, однако там нашёлся всего один участок с ZH-SCORE >= 500, поэтому их не рассматривали.
