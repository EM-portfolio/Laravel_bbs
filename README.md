﻿### Laravelで作成した掲示板
 ポートフォリオ：LaravelBBS

### プロジェクトの概要
Laravelの学習の一環としてBBSを作成しました

#### 使用技術
**バックエンド**
- フレームワーク: Laravel
- データベース: MySQL
- API設計: RESTful API
- 認証: Laravel Passport
**フロントエンド**
- マークアップ: HTML5
- スタイリング: BootStrap


### 工夫したポイント（技術的にこだわった点、苦労した点など）

1. **ユーザーインターフェースの工夫**
- レスポンシブデザイン: Bootstrapを用いて、どのデバイスでも美しく表示されるようにレスポンシブデザインを実現しました。
2. **セキュリティ対策**
- ユーザー認証: Laravel Passportを用いて、セキュアなトークンベースの認証を実装しました。
- 入力バリデーション: フロントエンドとバックエンドで厳密な入力バリデーションを行い、不正データの入力を防ぎました。
3. **MVCの学習**
- モデル: 
  - データベースと連携してデータの操作を行う役割としてのモデルを学習しました。データの保存、取得、削除などの操作を効率的に行う方法を理解しました。

- ビュー: 
  - ユーザーにデータを表示するためのビューの役割を学びました。HTMLとCSSを用いて、ユーザーインターフェースを美しく整える方法を習得しました。

- コントローラー: 
  - ユーザーのリクエストを受け取り、適切なモデルとビューを呼び出す役割としてのコントローラーを理解しました。ルーティングの設定やビジネスロジックの実装について学びました。

統合: MVCの各コンポーネントがどのように連携して機能するかを学び、実際のプロジェクトでこれらの知識を適用しました。
