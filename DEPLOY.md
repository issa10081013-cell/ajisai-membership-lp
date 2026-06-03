# 🚀 あじさい LP ワンクリック公開ガイド

---

## **最速 3ステップで本番公開**

### ✅ **STEP 1: GitHub リポジトリ確認**

リポジトリはすでに作成されています：
```
https://github.com/issa10081013-cell/ajisai-membership-lp
```

### ✅ **STEP 2: Vercel にデプロイ（ワンクリック）**

以下のリンクをクリック → GitHub ログイン → デプロイ完了

#### **【方法 A】 Vercel Deploy Button（推奨）**

```
https://vercel.com/new/clone?repository-url=https://github.com/issa10081013-cell/ajisai-membership-lp&project-name=ajisai-membership-lp&repo-name=ajisai-membership-lp
```

**手順:**
1. 上のリンクをクリック
2. "Continue with GitHub" をクリック
3. 「Deploy」をクリック
4. 2-3分で公開完了

**公開 URL 例:**
```
https://ajisai-membership-lp.vercel.app/
```

#### **【方法 B】 Netlify（アカウント不要）**

1. https://app.netlify.com/drop にアクセス
2. **lp-membership フォルダ全体** をドラッグ&ドロップ
3. 30秒で公開 URL が生成される

**公開 URL 例:**
```
https://xxxxxxxxx.netlify.app/
```

---

### ✅ **STEP 3: Google Forms 作成（5分）**

**Google-Forms-セットアップ.md** に従って、Google Forms を作成してください。

完成したら、短いリンク（https://forms.gle/...）をコピー。

---

### ✅ **STEP 4: LP の CTA ボタン設定**

Vercel または Netlify の管理画面から `index.html` を編集:

**編集対象行（約 239行目）:**
```html
<a href="#" class="cta-button">今すぐ会員登録する</a>
```

↓ 以下に変更:

```html
<a href="https://forms.gle/xxxxx" class="cta-button">今すぐ会員登録する</a>
```

（Google Forms の短いリンクに置き換え）

---

### ✅ **STEP 5: SNS 告知投稿**

**SNS告知投稿テンプレート.md** から以下をコピペ:

- **Instagram** 投稿テキスト
- **LINE 公式** メッセージ
- **Facebook** 投稿

**投稿時に設定する LP URL:**
```
【Vercel の場合】 https://ajisai-membership-lp.vercel.app/
【Netlify の場合】 https://xxxxxxxxx.netlify.app/
```

---

## 📋 **完了チェックリスト**

- [ ] Vercel または Netlify にデプロイ完了
- [ ] 公開 URL にアクセス → 正常に表示されることを確認
- [ ] Google Forms 作成完了 → 短いリンク取得
- [ ] index.html の CTA ボタン リンク先を Google Forms URL に変更
- [ ] Instagram / LINE / Facebook 投稿完了
- [ ] プロフURL を LP URL に変更
- [ ] 「今すぐ会員登録」ボタンクリック → Google Forms が開くことを確認

---

## 🎯 **トラブルシューティング**

### Q: Vercel デプロイで「Repository not found」エラー
→ GitHub ログインしてから、アカウントを確認してください

### Q: LP ページは表示されるが、「今すぐ会員登録」ボタンが動作しない
→ `index.html` の CTA ボタン href を Google Forms URL に更新してください

### Q: Google Forms のリンク短くしたい
→ Google Forms の「送信」> リンク > 短いリンクを使用

---

## ⚡ **次のステップ**

LP 公開後:

1. **Google Sheet で申し込み状況をリアルタイム監視**
   - Google Forms > 回答 > 「スプレッドシート」アイコン
   - 自動的に申し込み数を集計

2. **初期 7 日間は毎日 SNS 投稿**
   - Instagram ストーリーズ / リール
   - LINE 公式 配信

3. **メール返信体制を準備**
   - 申し込み者に 24 時間以内に返信

4. **Google Analytics でアクセス状況を追跡**
   - 訪問者数 / 申し込み率 / 離脱率

---

## 📞 **サポート**

質問・トラブルはこちら:
- LINE 公式アカウント: @ajisai
- メール: [your-email@example.com]

---

**🎉 頑張ってください！**
