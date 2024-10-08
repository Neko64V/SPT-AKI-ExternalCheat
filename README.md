## 概要
SPT-AKI/Escape from Tarkov(PvE) 向けの外部チートです。チート開発に対する興味を失ったので公開しておきます。  
肥大化しましたが最低限の機能は備えています。改修するのがめんどくさかったので現状のまま提供されます。

## 機能
* ESP
* NoRecoil
* Infinit Stamina
* NoFall Damage
* MenuKey : INSERT

## 備考
* メニューにImGuiを採用、ESP等のレンダリングもImGuiのDrawListを使用。
* ImGuiに最低限のカスタムを施しているので参考にすることも可。（ImGui/Custom.cpp）
* ある程度フレームワーク化を行ったので、他のゲームのチートへ比較的簡単に転用可能。
* OpenProcessやショボいオーバーレイを採用しているのでEACやBEのようなアンチチートには対策が必要。
* パフォーマンスやコード類の最適化を一切行っていません。このプロジェクトは現状のまま提供されます。
 
## 実行
必要なライブラリは全て揃っているので、VisualStudioでビルドすれば普通に動くはずです。  
https://learn.microsoft.com/ja-jp/cpp/build/vscpp-step-0-installation?view=msvc-170

## 免責事項
このプロジェクトは学習や研究・教育用としてアップロードされました。  
これらの用途以外で使用した場合に発生した如何なる損害についても、製作者(Neko64V)は一切の責任を負いません。  

## 使用したライブラリ
* Microsoft DirectXTK->SimpleMath  
https://github.com/microsoft/DirectXTK  
* ImGui  
https://github.com/ocornut/imgui  
* FreeType  
https://github.com/freetype/freetype  

## スクリーンショット
![image](https://github.com/user-attachments/assets/798c5a36-b1c6-417f-a943-ac869f510018)
