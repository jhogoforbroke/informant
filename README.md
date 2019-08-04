﻿# Informant

![enter image description here](https://lh3.googleusercontent.com/SrjQSw5ODItBgAylNuAlQo54Q2vT5DPhclMIbKmZfnbPIyJQ41MZ6TNaVO9R4RQFtXckiuTv0GGQ6C4Mhj8tdN2FzaEXhTHv_YNFlljtFJ-TmCTMnYJW1tIy_1QwQMroJnYRCbKUGfAzaC7ZHgPueDxxy0l43BfrgwcH8NWYRLt_6GJnCF4DJu19HpkTvEoGqPhfWBO1CCYTFXrDshx--oFCnRMrvgSd4igO1eAOmiOpprj5q9n4XNrYR_9JXEdIx-Qe7pmSv0gh7Hw_n-eaKXpq9DuWGfgzWifE03cnQY6hjjGomQV324GqNlGZNsVnS628Au-hgRpBoTaCMnRal7mCpByGIVPbeEekNOIXX5dqJCZCZuGUz5EmRQJZoPI-XLFHmLu4YAwm33Q1J4o_FStAM0IMd6kHF06KeMTBYb1gE0yY7JYtkqF4BUvUekRIyWzIU7LkL7s4eLANoW8ONTJ9kiiNI60MoWJTuY5svUwpQPT1nXAzHgOVqzs3J5wU41yLzlKO1r8CED4n77lIBYo29B4d4VITBX0xB2-Mmh9x6JUxnEQsB0pLW-M7366xeJ8t9H46NRwLXOmAKVaPrtmaxHmHpa1du3alIgzkWt61guxLXBiJCMii74AF5zNKIw2LZyvGKp1bvSIfvHUiOBz6Eoj2pZPyszFsODP4kMJcCsggPiHKRGwr0ZvuJPZkuXZDhk9LYtywYQx9enfraKyeKg=w480-h280-no)

## Introdução


**Informant** é uma ferramenta open source desenvolvida em python3 
para  auxiliar na fase de reconhecimento do pentest.
Também em desenvolvimento a função de auditoria para checklist de diretório padrão de instalação.

A ferramenta funciona online e consome as APIs do [Hacker Target](https://hackertarget.com/).
As APIs são de uso limitido a 100 chamadas por dia para cada IP.

## Funções

### Tela Inicial
- **Online Tools**
	* Ferramentas para coleta de informações
		+ _whois_
		+ _geoip_
		+ _portscan_
	
- **Offline Tools** - _IN DEVELOPMENT_ 
	* Ferramenta para auditoria de sistemas
		+ checklist de instalação

## Instalação
```
git clone https://github.com/thaishfmarques/informant.git ./informant
cd informant
pip install -r requirements.txt
python3 informant.py
```


## Author
: @thaishfmarques
> Written with [StackEdit](https://stackedit.io/).

