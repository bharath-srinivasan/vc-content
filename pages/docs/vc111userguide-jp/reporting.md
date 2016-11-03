---
title: レポート
description: レポート
layout: docs
date: 2016-06-03T10:21:23.333Z
priority: 13
---
## はじめに

レポートモジュールは、トップメニューから移動することができます。モジュールは、Virto Commerce ストレージにアップロードされたレポートのリストを参照します。また、レポートプレビューを生成し、印刷・PDF・エクセル・ワードファイルにエクスポートできます。ユーザーは、このモジュール及びレポートリストを表示・生成するための適切なアクセス権を持っている必要があります。（[利用可能アクセス権限](docs/vc111userguide-jp/users-management-roles-and-role-assignment/available-permissions)については、こちらをご参照ください)

![](../../assets/images/docs/report_module_tile.png)

## レポートリストの表示

レポートは、レポートファイルのリストを表示します。ページ右側の部部は、フォルダーのツリーが含まれています。フォルダーを選択することで、選択したフォルダーとサブフォルダーに配置されているレポートが表示されます。リストの一番上に３つのボタンがあります。

* Manage. アセットマネージャーを開きます。詳細については、以下を参照してください。
* Generate. 選択したレポートを生成し、プレビューページを表示します。詳細については、以下を参照してください。
* Refresh. レポート・フォルダーのリストを更新します。

![](../../assets/images/docs/report_list.png)

## レポートの生成

リストのレポートをダブルクリック又は "Generate" ボタンをクリックします。レポートのプレビューが表示されます。パラメーターが必要な場合、ページの右に表示されます。アスタリスクが表示されているパラメーターは、必須項目です。"Clear filters"ボタンでパラメーター値がデフォルトになります。 "Generate" ボタンクリックでパラメーターの値が提供されレポートが準備されます。もし、パラメーターが変更されていない場合でも、再クエリーが行われレポートデータが取得されます。

![](../../assets/images/docs/report_preview.png)

レポートビューのトップにはツールバーがあります。レポートプレビュー上で追加された機能が提供されており、ページ選択・ズーム・印刷・レイアウト変更・ページ設定の変更が選択できます。選択した形式ファイルでエクスポートができます。

## レポートの管理

この機能は、"Manage repots" 権限が必要になります。レポートファイル・フォルダーを管理する為のアセットマネージャーを開きます。

![](../../assets/images/docs/report_manage.png)

アセットマネージャーは、レポートストレージコンテンツを表示します。必要なフォルダーに移動し、レポートファイルをアップロードします。また、フォルダー作成・名前の変更・名前の表示・削除することができます。フォルダーを削除した場合、フォルダーに含まれるファイルとサブフォルダーは自動的に削除されます。