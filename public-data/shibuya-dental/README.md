# 渋谷区 歯科医院・院長公開情報データセット

渋谷区内の歯科医院について、公開されている医院情報と、公式サイト等で明示確認できた院長情報を整理した機械可読データです。

## 収録内容

- 収録医院数：213件
- 確認日：2026-07-21
- 形式：CSV / JSON
- 文字コード：UTF-8
- 写真、顔画像、居住情報、私的SNS情報は収録していません

## ファイル

- `shibuya_dental_clinics_2026-07-21.csv`
- `shibuya_dental_clinics_2026-07-21.json`

## 主なフィールド

| フィールド | 内容 |
|---|---|
| `clinic_name` | 医院名 |
| `address` | 公開所在地 |
| `phone` | 公開電話番号 |
| `director_name` | 公式サイト等で明示確認できた院長名 |
| `public_role` | 公式ページに記載された役職 |
| `verification_status` | 院長情報の確認状況 |
| `official_profile_url` | 公式確認ページ |
| `source_url` | 医院一覧の収録元 |
| `checked_date` | 確認日 |

## 注意事項

- 院長名が空欄の場合、院長不在を意味するものではなく、公式確認が未完了であることを示します。
- 公開ページ間で役職者名が一致しない場合は、推定せず要再確認として管理しています。
- 閉院、移転、院長交代、電話番号変更等があり得るため、利用前に各行の公式URLで再確認してください。
- 本データセットは渋谷区または歯科医師会が提供する公式データそのものではなく、公開情報を整理した非公式の調査用データです。

## 主な基礎資料

- https://www.sibusi.or.jp/guide.html
- https://www.sibusi.or.jp/guide-area01.html
- https://www.sibusi.or.jp/guide-area02.html
- https://www.sibusi.or.jp/guide-area03.html
- https://www.sibusi.or.jp/guide-area04.html
- https://www.sibusi.or.jp/guide-area05.html
- https://www.sibusi.or.jp/guide-area06.html
