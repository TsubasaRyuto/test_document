|  **理論名** | **物理名** | **備考** |
| --- | --- | --- |
| アクセス解析サマリー（日毎データ） | [access_batch_summaries](/application-documents/careecon/design_books/database/entity_definitions/access_batch_summaries.md) | マイページで表示するアクセス解析のサマリー(日毎のデータ) |
| 足跡履歴バッチ処理失敗 | [access_foot_failovers](/application-documents/careecon/design_books/database/entity_definitions/access_foot_failovers.md) | 足跡履歴のバッチ処理が失敗したときに保存するテーブル |
| 足跡履歴 | [access_foot_hists](/application-documents/careecon/design_books/database/entity_definitions/access_foot_hists.md) |     |
| プロジェクトアクセスPVパッチ処理失敗 | [access_pv_failovers](/application-documents/careecon/design_books/database/entity_definitions/access_pv_failovers.md) | PV履歴のバッチ処理が失敗したときに保存するテーブル  |
| プロジェクトアクセスPV | [access_pv_hists](/application-documents/careecon/design_books/database/entity_definitions/access_pv_hists.md) |     |
| 最寄りアクセス情報（駅から徒歩何分） | [access_stations](/application-documents/careecon/design_books/database/entity_definitions/access_stations.md) | 最寄りのアクセス情報(駅から徒歩何分) |
| 管理ユーザー（Branu） | [admin_users](/application-documents/careecon/design_books/database/entity_definitions/admin_users.md) |     |
| ブログコメント | [article_comments](/application-documents/careecon/design_books/database/entity_definitions/article_comments.md) |     |
| ブログ画像 | [article_photos](/application-documents/careecon/design_books/database/entity_definitions/article_photos.md) |     |
| ブログ | [articles](/application-documents/careecon/design_books/database/entity_definitions/articles.md) |     |
| メッセージ添付ファイル | [attachments](/application-documents/careecon/design_books/database/entity_definitions/attachments.md) | メッセージ機能での添付されたファイル管理 |
| メッセージチャンネル | [channels](/application-documents/careecon/design_books/database/entity_definitions/channels.md) | メッセージ機能のチャンネル(部屋) |
| コメント管理（管理者） | [comments](/application-documents/careecon/design_books/database/entity_definitions/comments.md) | 管理画面でのコメントを保存するためだけに使ってるテーブル |
| 会社 | [companies](/application-documents/careecon/design_books/database/entity_definitions/companies.md) |     |
| 登録会社（国交相サイトに掲載されている会社 | [company_banks](/application-documents/careecon/design_books/database/entity_definitions/company_banks.md) |     |
| 中間（会社と建設機材） | [company_construction_machines](/application-documents/careecon/design_books/database/entity_definitions/company_construction_machines.md) |     |
| お気に入り会社 | [company_favorites](/application-documents/careecon/design_books/database/entity_definitions/company_favorites.md) |     |
| 会社が属する業界 | [company_industries](/application-documents/careecon/design_books/database/entity_definitions/company_industries.md) |     |
| 会社加入保険 | [company_insurances](/application-documents/careecon/design_books/database/entity_definitions/company_insurances.md) |     |
| 中間（会社と許認可情報） | [company_licensed_industries](/application-documents/careecon/design_books/database/entity_definitions/company_licensed_industries.md) |  会社と許認可情報(業種)の中間テーブル |
| 会社いいね | [company_likes](/application-documents/careecon/design_books/database/entity_definitions/company_likes.md) | 会社にいいね！するやつ |
| ミッション詳細 | [company_mission_details](/application-documents/careecon/design_books/database/entity_definitions/company_mission_details.md) | ミッション詳細 |
| ミッションステータス | [company_missions](/application-documents/careecon/design_books/database/entity_definitions/company_missions.md) |     |
| 中間（会社対応可能都道府県） | [company_prefectures](/application-documents/careecon/design_books/database/entity_definitions/company_prefectures.md) | 会社と都道府県の中間テーブル |
| 会社所有資格 | [company_qualifications](/application-documents/careecon/design_books/database/entity_definitions/company_qualifications.md) |     |
| 不使用 | [company_suspensions](/application-documents/careecon/design_books/database/entity_definitions/company_suspensions.md) | 会社の停止ステータス(退会、規約違反、その他等) |
| 建設機材 | [construction_machines](/application-documents/careecon/design_books/database/entity_definitions/construction_machines.md) |     |
| お問い合わせ | [contacts](/application-documents/careecon/design_books/database/entity_definitions/contacts.md) |     |
| 特徴 | [features](/application-documents/careecon/design_books/database/entity_definitions/features.md) |     |
| slug管理 | [friendly_id_slugs](/application-documents/careecon/design_books/database/entity_definitions/friendly_id_slugs.md) | idではなく任意の文字列でアクセスするための管理テーブル。詳しくは、こちら参照( https://github.com/norman/friendly_id ) |
| 業界 | [industries](/application-documents/careecon/design_books/database/entity_definitions/industries.md) |     |
| サービスインフォーメーション | [infos](/application-documents/careecon/design_books/database/entity_definitions/infos.md) |     |
| 会社CSVデータ | [legacy_companies](/application-documents/careecon/design_books/database/entity_definitions/legacy_companies.md) | 会社をcsvから登録するためのテーブル。多分、初期段階で会社を入れるために作ったかも？(推測) |
| 許認可業種テーブル | [licensed_industries](/application-documents/careecon/design_books/database/entity_definitions/licensed_industries.md) | 許認可業種テーブル |
| メッセージ定型文 | [message_templates](/application-documents/careecon/design_books/database/entity_definitions/message_templates.md) |     |
| メッセージ | [messages](/application-documents/careecon/design_books/database/entity_definitions/messages.md) |     |
| 通知 | [notifications](/application-documents/careecon/design_books/database/entity_definitions/notifications.md) |     |
| 施工事例お気に入り | [project_case_favorites](/application-documents/careecon/design_books/database/entity_definitions/project_case_favorites.md) |     |
| 施工事例工事種類 | [project_case_industries](/application-documents/careecon/design_books/database/entity_definitions/project_case_industries.md) |     |
| 施工事例いいね | [project_case_likes](/application-documents/careecon/design_books/database/entity_definitions/project_case_likes.md) |     |
| 施工事例画像 | [project_case_photos](/application-documents/careecon/design_books/database/entity_definitions/project_case_photos.md) |     |
| 成功事例ランキング | [project_case_rankings](/application-documents/careecon/design_books/database/entity_definitions/project_case_rankings.md) |     |
| 施工事例 | [project_cases](/application-documents/careecon/design_books/database/entity_definitions/project_cases.md) |     |
| 案件お気に入り | [project_favorites](/application-documents/careecon/design_books/database/entity_definitions/project_favorites.md) |     |
| 案件特徴 | [project_features](/application-documents/careecon/design_books/database/entity_definitions/project_features.md) |     |
| 案件工事種類 | [project_industries](/application-documents/careecon/design_books/database/entity_definitions/project_industries.md) |     |
| 案件いいね | [project_likes](/application-documents/careecon/design_books/database/entity_definitions/project_likes.md) |     |
| 案件 | [projects](/application-documents/careecon/design_books/database/entity_definitions/projects.md) |     |
| 資格 | [qualifications](/application-documents/careecon/design_books/database/entity_definitions/qualifications.md) |     |
| Q&Aカテゴリー | [question_categories](/application-documents/careecon/design_books/database/entity_definitions/question_categories.md) |     |
| Q&A | [questions](/application-documents/careecon/design_books/database/entity_definitions/questions.md) |     |
| リクルートページ画像 | [recruit_photos](/application-documents/careecon/design_books/database/entity_definitions/recruit_photos.md) |     |
| リクルートページ | [recruits](/application-documents/careecon/design_books/database/entity_definitions/recruits.md) |     |
| 不使用 | [regions](/application-documents/careecon/design_books/database/entity_definitions/regions.md) | 使ってないやつ |
| 不使用 | [reviews](/application-documents/careecon/design_books/database/entity_definitions/reviews.md) | 使ってないやつ |
| ユーザーの通知 | [user_notifications](/application-documents/careecon/design_books/database/entity_definitions/user_notifications.md) |     |
| ユーザー　（利用会社社員（担当者） | [users](/application-documents/careecon/design_books/database/entity_definitions/users.md) |     |
