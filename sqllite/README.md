#visualTransactionForType.py INPUT, OUTPUT#

```python
https://www.walletexplorer.com/ < 해당 사이트에서 addr값 찾아서 입력
거래소 / 부정거래 구별 가능
```
![image](https://user-images.githubusercontent.com/33795856/116235415-cc562f80-a798-11eb-98ab-dcdf7360b2ca.png)
![image](https://user-images.githubusercontent.com/33795856/116376632-6971a080-a84b-11eb-8928-5fd67fb931c0.png)

#inputHashOutputGraph.py INPUT, OUTPUT#

```python
해시값을 입력해주세요.
a7d7035bcb69ce61a295aa45b7abbbe5fd39c2f334e4b809ec7730d825546c47

차수를 입력해주세요.
10

트랜잭션이 2개 이상인 경우 BTC 합이 가장 큰 트랜잭션으로 연결됩니다.

트랜잭션별 해시값과 거래대금은 아래와 같습니다.
[ 1] [Tx] : 10000002 [Hash] : a7d7035bcb69ce61a295aa45b7abbbe5fd39c2f334e4b809ec7730d825546c47 [BTC] : 0.534500
[ 2] [Tx] : 10000210 [Hash] : de8747aa87ab0d60e66cbf10219e11e098b880a3a4f54f94b3f4eeaed71caaa5 [BTC] : 0.462280
[ 3] [Tx] : 10000924 [Hash] : 32f9f617064c9c6e455f46401c9829b6de0a7bd2730b6c1b3c45969bd1637b9c [BTC] : 0.810451
[ 4] [Tx] : 10022940 [Hash] : 2d623c7a79b8400fbbd2fbf8aa128f3663922a150e5409a327218d4e210152ac [BTC] : 0.819451
[ 5] [Tx] : 10026417 [Hash] : a52e0d20e0ca02900fa610096f3618ae35463b14dc7c181f61c06f45ca5ab09d [BTC] : 0.832250
[ 6] [Tx] : 10028655 [Hash] : 79add48f53471bd283e4ab342d302a6f74ce4c31ab7d1da04a9d49a4e9a1230a [BTC] : 1.309082
[ 7] [Tx] : 10029971 [Hash] : 293c2eb7299ccd31eb4102d389fd687f675b1055ad2ceac4a3b3ec8018f33ffe [BTC] : 1.000924
[ 8] [Tx] : 10029972 [Hash] : 2fcc99dab65e3990d1fc175763ea82f667840b76331ac9f40132887007498f6a [BTC] : 26.335296
[ 9] [Tx] : 10036732 [Hash] : 21ab262cd947c86d12ff0649b696c1b3e2e2c91c90bb550ee7b5fdd26c2e60d4 [BTC] : 27.805113
[10] [Tx] : 10103957 [Hash] : c081bcd44e64867a1f2a1d7adaeaa10ced77814326ceb37eca5466a36bb4fcfb [BTC] : 284.350771

[Tx]10103957와 연결된 Addr의 주소와 BTC는 아래과 같습니다.
[ 1] [Addr] : 6777005 [Hash] : 12RHj4KivHcT41Qa14fdrhAffCVu23fkaK [BTC] : 282.507740
[ 2] [Addr] : 8059548 [Hash] : 1QLXKVcUh7mCzqYRso2wqPzqjg6fC1QMiY [BTC] : 1.843031
```
![image](https://user-images.githubusercontent.com/33795856/112846349-ed1b5e80-90e0-11eb-939c-94581cc52df7.png)


#firstTransaction.py INPUT, OUTPUT#

``` python
거래소 A를 입력해주세요.
빗썸

거래소 B를 입력해주세요.
빗썸

빗썸와 빗썸의 모든 주소를 검색합니다.
[빗썸] 총 56635개의 주소가 검색되었습니다.
[빗썸] 총 56635개의 주소가 검색되었습니다.

빗썸와 빗썸의 모든 트랜잭션을 검색합니다.
[빗썸] 총 52985개의 트랜잭션이 검색되었습니다.
[빗썸] 총 52985개의 트랜잭션이 검색되었습니다.

주소의 개수가 1개인 트랜잭션을 검색합니다.
주소의 개수가 1개인 트랜잭션을 제외합니다.

빗썸에서 빗썸으로 이동한 트랜잭션을 검색합니다.
총 67개의 트랜잭션이 검색되었습니다.

(1) 주소의 개수가 많고, (2) 총 거래 금액이 높은 트랜잭션부터 내림차순으로 정렬합니다.
[  1] [TxOut]  43826697 [TxIn]  43831011 [Addr Cnt] 101 [BTC] 0.0480900000
[  2] [TxOut]  43831011 [TxIn]  43834481 [Addr Cnt] 101 [BTC] 0.0466900000
[  3] [TxOut]  43834481 [TxIn]  43836910 [Addr Cnt] 101 [BTC] 0.0452900000
[  4] [TxOut]  43836910 [TxIn]  43840542 [Addr Cnt] 101 [BTC] 0.0438900000
[  5] [TxOut]  43840542 [TxIn]  43844287 [Addr Cnt] 101 [BTC] 0.0424900000
[  6] [TxOut]  43844287 [TxIn]  43847942 [Addr Cnt] 101 [BTC] 0.0410900000
[  7] [TxOut]  43847942 [TxIn]  43851427 [Addr Cnt] 101 [BTC] 0.0396900000
[  8] [TxOut]  43851427 [TxIn]  43856001 [Addr Cnt] 101 [BTC] 0.0382900000
[  9] [TxOut]  43856001 [TxIn]  43859317 [Addr Cnt] 101 [BTC] 0.0368900000
[ 10] [TxOut]  43859317 [TxIn]  43861756 [Addr Cnt] 101 [BTC] 0.0354900000
[ 11] [TxOut]  43861756 [TxIn]  43864332 [Addr Cnt] 101 [BTC] 0.0340900000
[ 12] [TxOut]  43864332 [TxIn]  43867756 [Addr Cnt] 101 [BTC] 0.0326900000
[ 13] [TxOut]  43867756 [TxIn]  43870501 [Addr Cnt] 101 [BTC] 0.0312900000
[ 14] [TxOut]  43870501 [TxIn]  43873026 [Addr Cnt] 101 [BTC] 0.0298900000
[ 15] [TxOut]  43873026 [TxIn]  43876021 [Addr Cnt] 101 [BTC] 0.0284900000
[ 16] [TxOut]  43876021 [TxIn]  43878899 [Addr Cnt] 101 [BTC] 0.0270900000
[ 17] [TxOut]  43878899 [TxIn]  43880682 [Addr Cnt] 101 [BTC] 0.0256900000
[ 18] [TxOut]  43880682 [TxIn]  43883274 [Addr Cnt] 101 [BTC] 0.0242900000
[ 19] [TxOut]  43883274 [TxIn]  43885128 [Addr Cnt] 101 [BTC] 0.0228900000
[ 20] [TxOut]  43885128 [TxIn]  43888581 [Addr Cnt] 101 [BTC] 0.0214900000
[ 21] [TxOut]  43823982 [TxIn]  43916828 [Addr Cnt] 101 [BTC] 0.0213843600
[ 22] [TxOut]  43910718 [TxIn]  43916828 [Addr Cnt] 101 [BTC] 0.0213843600
[ 23] [TxOut]  43888581 [TxIn]  43890122 [Addr Cnt] 101 [BTC] 0.0200900000
[ 24] [TxOut]  43916828 [TxIn]  43918764 [Addr Cnt] 101 [BTC] 0.0199843600
[ 25] [TxOut]  43890122 [TxIn]  43892907 [Addr Cnt] 101 [BTC] 0.0186900000
[ 26] [TxOut]  43918764 [TxIn]  43922639 [Addr Cnt] 101 [BTC] 0.0185843600
[ 27] [TxOut]  43803932 [TxIn]  43806764 [Addr Cnt] 101 [BTC] 0.0177000000
[ 28] [TxOut]  43892907 [TxIn]  43896058 [Addr Cnt] 101 [BTC] 0.0172900000
[ 29] [TxOut]  43922639 [TxIn]  43926378 [Addr Cnt] 101 [BTC] 0.0171843600
[ 30] [TxOut]  43806764 [TxIn]  43807886 [Addr Cnt] 101 [BTC] 0.0163000000
[ 31] [TxOut]  43896058 [TxIn]  43900209 [Addr Cnt] 101 [BTC] 0.0158900000
[ 32] [TxOut]  43926378 [TxIn]  43930309 [Addr Cnt] 101 [BTC] 0.0157843600
[ 33] [TxOut]  43807886 [TxIn]  43810640 [Addr Cnt] 101 [BTC] 0.0149000000
[ 34] [TxOut]  43815913 [TxIn]  43818150 [Addr Cnt] 101 [BTC] 0.0148943600
[ 35] [TxOut]  43900209 [TxIn]  43904179 [Addr Cnt] 101 [BTC] 0.0144900000
[ 36] [TxOut]  43810640 [TxIn]  43813331 [Addr Cnt] 101 [BTC] 0.0135000000
[ 37] [TxOut]  43818150 [TxIn]  43821200 [Addr Cnt] 101 [BTC] 0.0134943600
[ 38] [TxOut]  43904179 [TxIn]  43905734 [Addr Cnt] 101 [BTC] 0.0130900000
[ 39] [TxOut]  43813331 [TxIn]  43815913 [Addr Cnt] 101 [BTC] 0.0121000000
[ 40] [TxOut]  43821200 [TxIn]  43823982 [Addr Cnt] 101 [BTC] 0.0120943600
[ 41] [TxOut]  43905734 [TxIn]  43910718 [Addr Cnt] 101 [BTC] 0.0116900000
[ 42] [TxOut] 448754938 [TxIn] 449034492 [Addr Cnt]  51 [BTC] 352.2682318400
[ 43] [TxOut]  43930309 [TxIn]  43936445 [Addr Cnt]  49 [BTC] 0.0145843600
[ 44] [TxOut] 109594572 [TxIn] 109597118 [Addr Cnt]  31 [BTC] 0.9676577000
[ 45] [TxOut] 109597118 [TxIn] 109599289 [Addr Cnt]  31 [BTC] 0.9375366000
[ 46] [TxOut] 109599289 [TxIn] 109601520 [Addr Cnt]  31 [BTC] 0.9074154000
[ 47] [TxOut] 109601520 [TxIn] 109603696 [Addr Cnt]  31 [BTC] 0.8772943000
[ 48] [TxOut] 109605198 [TxIn] 110127736 [Addr Cnt]  31 [BTC] 0.8370731000
[ 49] [TxOut] 110127736 [TxIn] 110129145 [Addr Cnt]  31 [BTC] 0.8069519000
[ 50] [TxOut] 114166934 [TxIn] 114166935 [Addr Cnt]  31 [BTC] 0.4697576000
[ 51] [TxOut] 114166935 [TxIn] 114210527 [Addr Cnt]  31 [BTC] 0.4396364000
[ 52] [TxOut] 110129145 [TxIn] 110419364 [Addr Cnt]  27 [BTC] 0.7768444000
[ 53] [TxOut] 114210527 [TxIn] 114215223 [Addr Cnt]  26 [BTC] 0.4095322000
[ 54] [TxOut] 110419364 [TxIn] 110552980 [Addr Cnt]  15 [BTC] 0.7507444000
[ 55] [TxOut] 109603696 [TxIn] 109605198 [Addr Cnt]  11 [BTC] 0.8471943000
[ 56] [TxOut] 151594893 [TxIn] 152521651 [Addr Cnt]   4 [BTC] 0.9517434500
[ 57] [TxOut]  93484847 [TxIn]  93502673 [Addr Cnt]   4 [BTC] 0.2145458400
[ 58] [TxOut]  31321435 [TxIn]  31322779 [Addr Cnt]   4 [BTC] 0.0756070800
[ 59] [TxOut]  30966840 [TxIn]  30968863 [Addr Cnt]   4 [BTC] 0.0510416000
[ 60] [TxOut] 123503576 [TxIn] 123763721 [Addr Cnt]   3 [BTC] 6.4031892400
[ 61] [TxOut]  36801677 [TxIn]  36802299 [Addr Cnt]   2 [BTC] 10.0125708700
[ 62] [TxOut]  41890415 [TxIn]  41895563 [Addr Cnt]   2 [BTC] 1.5225602500
[ 63] [TxOut]  44024717 [TxIn]  44025299 [Addr Cnt]   2 [BTC] 0.8216000000
[ 64] [TxOut]  43355375 [TxIn]  43357248 [Addr Cnt]   2 [BTC] 0.5099820500
[ 65] [TxOut]  43806867 [TxIn]  43808118 [Addr Cnt]   2 [BTC] 0.5098000200
[ 66] [TxOut]  42932807 [TxIn]  42933135 [Addr Cnt]   2 [BTC] 0.3260308200
[ 67] [TxOut]  31319125 [TxIn]  31321435 [Addr Cnt]   2 [BTC] 0.0380035400

탐색할 트랜잭션의 INDEX를 입력해주세요.
51

51번째의 거래를 출력합니다.
[  1] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147565 [BTC] 0.0010000000
[  2] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147566 [BTC] 0.0010000000
[  3] [TxOut] 114166935 [TxIn] 114210527 [Addr] 110657749 [BTC] 0.0010000000
[  4] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147567 [BTC] 0.0010000000
[  5] [TxOut] 114166935 [TxIn] 114210527 [Addr]  27225300 [BTC] 0.0010000000
[  6] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147568 [BTC] 0.0010000000
[  7] [TxOut] 114166935 [TxIn] 114210527 [Addr]  62590827 [BTC] 0.0010000000
[  8] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147569 [BTC] 0.0010000000
[  9] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147570 [BTC] 0.4096364000
[ 10] [TxOut] 114166935 [TxIn] 114210527 [Addr]  99860668 [BTC] 0.0010000000
[ 11] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147571 [BTC] 0.0010000000
[ 12] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147572 [BTC] 0.0010000000
[ 13] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147573 [BTC] 0.0010000000
[ 14] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147574 [BTC] 0.0010000000
[ 15] [TxOut] 114166935 [TxIn] 114210527 [Addr]  37576918 [BTC] 0.0010000000
[ 16] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147575 [BTC] 0.0010000000
[ 17] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147576 [BTC] 0.0010000000
[ 18] [TxOut] 114166935 [TxIn] 114210527 [Addr] 109397291 [BTC] 0.0010000000
[ 19] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147577 [BTC] 0.0010000000
[ 20] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147578 [BTC] 0.0010000000
[ 21] [TxOut] 114166935 [TxIn] 114210527 [Addr] 130142320 [BTC] 0.0010000000
[ 22] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147579 [BTC] 0.0010000000
[ 23] [TxOut] 114166935 [TxIn] 114210527 [Addr]  35912443 [BTC] 0.0010000000
[ 24] [TxOut] 114166935 [TxIn] 114210527 [Addr]  43101161 [BTC] 0.0010000000
[ 25] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147580 [BTC] 0.0010000000
[ 26] [TxOut] 114166935 [TxIn] 114210527 [Addr]  79668929 [BTC] 0.0010000000
[ 27] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147581 [BTC] 0.0010000000
[ 28] [TxOut] 114166935 [TxIn] 114210527 [Addr] 100905787 [BTC] 0.0010000000
[ 29] [TxOut] 114166935 [TxIn] 114210527 [Addr] 107615766 [BTC] 0.0010000000
[ 30] [TxOut] 114166935 [TxIn] 114210527 [Addr] 132147582 [BTC] 0.0010000000
[ 31] [TxOut] 114166935 [TxIn] 114210527 [Addr] 117990457 [BTC] 0.0010000000
```
