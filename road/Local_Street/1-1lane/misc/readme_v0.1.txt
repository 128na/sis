--------------------------------------------------------------------------------

	　　 システマティックインフラシリーズ　景観一般道路　基本セット
	Systematic Infrastructure Series　The Real Local Street Basic Package

--------------------------------------------------------------------------------


　ダウンロード頂きありがとうございます。Pak128版Simutrans用アドオンです。


　　景観高速道路のリリースから早一年。 SIS道路シリーズの第二弾となる一般道路
　が公開の運びとなりました。今回は基本セットとしてまず市道置き換え用の歩道付
　き50km/h道路、そして都市間道路向けに70・80km/h道路を用意しました。今後リリ
　ース予定のアクセサリーアドオン群を組み合わせ、思い思いの風景作りをお楽しみ
　いただけましたら幸いです。



-----------------------------------　内容物　-----------------------------------

　このZipファイルには以下のデータが含まれています。


■way.SIS_LocalStreet_CityRoad_ds.pak （ダブルスロープ対応 120.0RC～）

	緩急坂に対応する当アドオン全てのものが実装されたpakファイルです。
	緩急坂に対応したSimutrans（120.0RC以上）かつPakSetでない場合使用できま
	せんのでご注意ください。


■way.SIS_LocalStreet_CityRoad_ss.pak （シングルスロープ対応 112.3～）

	ダブルスロープ非対応pakset向けのpakファイルです。
	本体は112.3以降のバージョンに対応。


　※これら２つのファイルを同時に導入した場合、アドオン名が重複するため正しく
　　動作しません。 必ずどちらか一方のpakファイルを導入していただくようお願い
　　いたします。


■ja.tab

	当アドオンの翻訳用ファイルです。
	pak128\text内のja.tabファイルに内容を書き足すことで、 日本語表記にす
	ることが可能です。


■readme.txt

	当アドオンの取扱説明書。


※sourceについて

	ファイル容量が大きくなっておりますので別途ソースファイルのみを配布し
	ています。必要であれば以下のURLよりダウンロードください
。
	https://sourceforge.jp/projects/sis-simutrans/releases/



--------------------------　アドオン命名規則について　--------------------------

　ご参考までにSISでは以下の命名規則を制定しておりますのでご紹介します。


	name=SIS_A_BCD_xxE


	SIS	SIS規格に準拠したアドオンの接頭語

	A	E:高速道路
		L:一般道路
		C:コンクリート橋梁
		ST:新幹線軌道
		A:空港

	B	R:道路(Road)	T:線路(Track)	P:橋脚(Pier)
		M:路面軌道(traM)	A:滑走路・誘導路(Airway)

	C	G:地上(Ground)	E:高架(Elevated)	B:橋梁(Bridge)	
		T:トンネル(Tunnel)		U:地下(Underground)
		O:オブジェクト(way-Object)	S:標識(roadSign)
		Y:滑走路(runwaY)		X:誘導路(taXiway)

	D	1:1車線道路	（2 lane）
		2:2車線道路	（1 lane）
		1-1:片側1車線（対向2車線）道路	（1 and 1 lane）
		2t2-1:分岐路（本線2車線→本線2車線+1車線分岐）	（2 to 2 and 1）
		2-1t2:合流路（本線2車線+1車線→本線に合流）	（2 and 1 to 2）
	
	xx 	製作パーツ番号(00～99)

	E	F:手前側敷設用(Front)	B:奥側(Back)
		S:単独(Single)		C:中間(Center)



　　当初は各要素を基本的に略さず使用する案であったものの、NetSimutransでの読み
　込み速度改善を意図し、極力短い表記としました。改造アドオン、アクセサリーパー
　ツ等製作の際にご参考にしていただければと思います。



-----------------------　謝辞・改変及び公開などについて　-----------------------

■謝辞

　当アドオンを製作するにあたり、 Fabio Gonella氏製作のデフォルト道路アドオン
　より、ベースタイルや白線描画位置等の配置及びコスト設定を、 また598氏製作の
　「軌道セット」 よりdat記述及び手前・奥側等配置方法を参考とさせていただきま
　した。製作者である598氏、Fabio Gonella氏両氏にこの場を借りて深く御礼申し上
　げます。ありがとうございました。

　また当アドオンを製作するにあたり以下のWebsiteを製作の参考とさせていただきま
　した。重ねて深くお礼申し上げます。



■改変、公開について

　改変および改変したアドオンの公開はご自由にどうぞ。
　標識など付属アドオンの開発も歓迎。

　当アドオンのソース、及び製作中のPictbear形式ファイルをSourceForge.JPにて公
　開しています。開発検討時のログ等も残されておりますので宜しければ御覧ください。

	各種ソース、製作中データの配布URL：https://sourceforge.jp/projects/sis-simutrans/releases/
	SourceForge.JP プロジェクトページ：http://sourceforge.jp/projects/sis-simutrans/



■連絡等

　当アドオンに関する不具合等のご指摘・ご意見等ございましたら「Ebi」または「しらかみ」までご連絡下さい。
　Simutrans実験室の特設ページもしくはTwitterにてお願い致します。

	Simutrans実験室・特設ページ：http://wikiwiki.jp/twitrans/?support%2Fproject%2Fsis_road

	Twitter：Ebi		@Ebi_Simu
　      　　　 　しらかみ	@e701pv



■参考文献

　・道路構造令					"http://law.e-gov.go.jp/htmldata/S45/S45SE320.html"
  ・案内標識｜首都高を使う｜首都高で行こう！	"http://www.shutoko.jp/use/convenience/infoboard/guidance/"
  ・路面標示何でもコーナー | KICTEC		"http://www.kictec.co.jp/varieties-road-mark/"
　・STAGEAと走れ！				"http://www33.tok2.com/home/m35rx4/"
　・道路標識、区画線及び道路標示に関する命令	"http://www.mlit.go.jp/road/sign/kijyun/kukaku/ss-kukaku-index.html"
　・国土交通省道路局 | 道路標識			"http://www.mlit.go.jp/road/sign/sign/index.htm"



----------------------------------------　更 新 履 歴　---------------------------------------

2015.02.14	基本セット公開


									2015.02.14作成
								製作：景観道路開発プロジェクト
							　　（しらかみ・Ebi・yuuyarail・tamaina）

									－　以　上　－
