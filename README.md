# 令和6年能登半島地震 建設型応急仮設住宅GISデータ
## 概要
令和6年能登半島地震に伴い建設中の建設型応急仮設住宅について、自治体の発表資料をもとに位置情報などを付加して、GISデータ化したデータ（GeoJSON形式）を公開しています。  
以下のリンクより、データにアクセス可能です。  
- GeoJSON形式  
[https://github.com/a-masumura/R06-Noto-Peninsula-EQ-temporary-housing/raw/main/令和6年能登半島地震_建設型応急仮設住宅.geojson](https://github.com/a-masumura/R06-Noto-Peninsula-EQ-temporary-housing/raw/main/%E4%BB%A4%E5%92%8C6%E5%B9%B4%E8%83%BD%E7%99%BB%E5%8D%8A%E5%B3%B6%E5%9C%B0%E9%9C%87_%E5%BB%BA%E8%A8%AD%E5%9E%8B%E5%BF%9C%E6%80%A5%E4%BB%AE%E8%A8%AD%E4%BD%8F%E5%AE%85.geojson)
- Google スプレッドシートへのリンク  
[https://docs.google.com/spreadsheets/d/16zO3MmnqDNoG2Dn1got9jTN-4Jiv0w5LaA7Sr9DUPEM/edit?usp=sharing](https://docs.google.com/spreadsheets/d/16zO3MmnqDNoG2Dn1got9jTN-4Jiv0w5LaA7Sr9DUPEM/edit?usp=sharing)

- 「◯月下旬（YYYY/MM/DD）」などの表記はYYYY年MM月DD日時点の石川県のPDF「着工済み団地一覧」に基づくことを示しています。特に（YYYY/MM/DD）がない場合は「出典」列のデータソースによります。

## 更新情報
- 2024/3/15
  - 石川県ウェブサイトの「[応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)」に掲載されたPDF「着工済み団地一覧」（2024年3月12日時点の一覧）に基づきデータを更新しました。合計83箇所（4,345戸）です。（住所が同じ用地は1箇所としてカウントしています。）
- 2024/3/6
  - 石川県ウェブサイトの「[応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)」に掲載されたPDF「着工済み団地一覧」（2024年3月5日時点の一覧）に基づきデータを更新しました。合計72箇所（3,947戸）です。（住所が同じ用地は1箇所としてカウントしています。）
  - 「完成フラグ」列を追加しました。着工日が明記されたものは「着工」、完成日が明記されたものは「完成」、一体の団地のうち一部の住戸が完成したものは「一部完成」と入力しています。
  - 「完成見込み」列を追加しました。従来は「完成日」列に見込みも記入していましたが、完成日と完成見込みを別々の列に格納することとしました。
  - 「出典URL」列を削除しました。既にPDFが削除されており、リンク切れになるためです。
- 2024/3/4
  - 石川県ウェブサイトの「[応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)」に掲載されたPDF「着工済み団地一覧」（2024年2月28日時点の一覧）に基づきデータを更新しました。合計64箇所（3,522戸）です。（住所が同じ用地は1箇所としてカウントしています。）
- 2024/2/20
  - 石川県ウェブサイトの「[応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)」に掲載されたPDF「着工済み団地一覧」（2024年2月20日時点及び2024年2月16日時点の一覧）に基づきデータを更新しました。合計50箇所（2,900戸）です。（住所が同じ用地は1箇所としてカウントしています。）
  - 「建築タイプ」列を追加しました。ただし、値はまだ入力していません。
- 2024/2/11
  - 石川県ウェブサイトの「[応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)」に掲載されたPDF「応急仮設住宅の進捗状況」（2024年2月8日時点）に基づきデータを更新しました。合計34箇所（2,156戸）です。
- 2024/1/31
  - 石川県（2024/1/29）の記者発表資料に基づきデータを更新しました。合計22箇所（1,248戸）です。
  - 「完成日」列を追加しました。
- 2024/1/27
  - 石川県（2024/1/23）の記者発表資料に基づきデータを更新しました。合計14箇所（640戸）です。 

## ライセンスについて  
- 公開しているGeoJSON形式およびGoogle スプレッドシートのデータ: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 参考リンク
- [石川県 応急仮設住宅（建設型）について（災害救助法：令和6年（2024年）能登半島地震）](https://www.pref.ishikawa.lg.jp/kenju/saigai/r6oukyuukasetsujyuutaku.html)
- [石川県 建築住宅課の記者発表資料（令和5年度）](https://www.pref.ishikawa.lg.jp/kisya/r5/kentikuzyuutaku.html)
- [石川県能登町 応急仮設住宅建設情報](https://www.town.noto.lg.jp/www/info/detail.jsp?common_id=20932)
- [石川県七尾市 建設型応急住宅について](https://www.city.nanao.lg.jp/toshikenchiku/oukyuukasetujuutaku.html)
- [石川県珠洲市 応急仮設住宅の入居申込について](https://www.city.suzu.lg.jp/soshiki/5/11680.html)
- [石川県穴水町 応急仮設住宅（建設型）について](https://www.town.anamizu.lg.jp/seibi/jisjin_jyutaku_oukyuujutaku_2.html)
