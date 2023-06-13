# hello_flutter

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## メモ
初めてのflutterアプリ  
https://codelabs.developers.google.com/codelabs/flutter-codelab-first?hl=ja#0

開発ターゲットは開発デバイスのオペレーティングシステムを選択を推奨  

flutterではウェブアプリのホットリロードはできない  

pubspec.yaml  
	現在のバージョン、依存関係、同梱するアセットなどアプリの基本情報を指定

analysis_opsions.yaml  
	Flutterがコードを解析する際の厳格さを指定

ステートフルホットリロード  
	変更をソースファイルに保存したときにトリガー

main関数  
	定義したアプリの実行  
ウィジェット  
	すべてのFlutterアプリを作成する際のもとになる要素  
ChangeNotifier  
	状態クラス  
	アプリ全体に提供される  

行末のカンマはつけておくことを推奨  

notifyListeners()  
	監視しているクラスに変更を通知  
Theme.of(context)  
	アプリの現在のテーマをリクエスト  
them.textTheme  
	アプリのフォントテーマにアクセス  
	displayMedium  
		ディスプレイテキスト用の大きなスタイル  
		copyWith()  
			定義した変更されたテキストスタイルのコピーを返却  
	!をつける  
		nullを承知で使用  
		
SafeArea  
	子がハードウェア　ノッチやステータスバーで隠れないようにするもの  
Expanded  
	欲張りなウィジェット  
	残りのスペースをできる限り埋める  
ステートレス  
	自身の変更可能状態を含まない  
	
「_」が頭につくクラスは非公開クラス  

onDestinationSelected  
	ナビゲーションレールのデスティネーションが選択されたときに起きるイベントを定義  

フェイルファストの原則  
	障害を示す可能性のある状態をインターフェイスで即座に報告するシステムのこと  
LayoutBuilder  
	利用可能なスペースに応じてウィジェットツリーを変更  

ステップアップ  
https://dartpad.dev/?id=e7076b40fb17a0fa899f9f7a154a02e8