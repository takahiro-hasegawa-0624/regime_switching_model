# regime_switching_model
トヨタ自動車と東京電力の株価について、レジームスイッチングモデルを適用。
パラメータの推定はMCMC（MH法）を採用した。

マーケット株価はTOPIXを採用した。
無リスク資産は日本国債（10年）を採用した。

各社の株価は
https://kabuoji3.com/stock/
から入手した。

TOPIXは
http://wakash.com/cgi-bin/get_kabuka/select_meigara.php
から入手した。

国債金利は
https://www.mof.go.jp/jgbs/reference/interest_rate/
から入手した。
