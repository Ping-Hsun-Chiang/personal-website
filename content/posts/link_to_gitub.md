---
title: "Link To Github (Local -> Remote)"
date: 2026-04-22
draft: false
---

## 背景

123

---

## Step 1: cd 到 local 端資料夾

```bash
cd /xx/xx/xx/xx
```

## Step 2: 初始化 Git 儲存庫

```bash
git init
```

## Step 3: 將所有檔案加入暫存區並提交

```bash
git add .
git commit -m "Initial commit"
```

## Step 4: 設定主要分支名稱

```bash
git branch -M main
```

## Step 5: 連結 Github repository

```bash
git remote add origin <>
```

## Step 6: Remote 端有檔案 (e.g., README, LICENSE...)

```bash
git pull origin main --allow-unrelated-histories
```

接下來會進入全黑的 Vim，點擊鍵盤中的 "esc" -> 輸入 "wq" -> Enter。

## Step 7: Push 到 remote 端

```bash
git push -u origin main
```