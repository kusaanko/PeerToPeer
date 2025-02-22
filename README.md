# P2P通信ライブラリ
詳しくはドキュメントを御覧ください。

# Release_PPCS_3.1.0 20180524
1. P2Pライブラリを最新版3.1.0に更新しました。
```
2.ListenTester_PPCS: デバイス側のシミュレーションを行うテストプログラム。標準P2Pプラットフォームのデバイス側とRTOS P2Pプラットフォームのデバイス側を含む。
	*標準的なP2Pデバイス側のテストをシミュレート：P2Pのみテスト可能、ハイバネーション・ウェイクアップ・テストはサポートされていません。
	*RTOS P2Pデバイス側のテスト：Wakeupパラメータ（WakeupKey,WakeupServerIP）を持ち込む必要があり、持ち込まない場合はRTOS P2P部分のみのテストが可能です。
PS:	
	*標準的なP2Pプラットフォームはデバイスのハイバネーション起動をサポートしていませんが、RTOS P2Pプラットフォームはデバイスのハイバネーション起動をサポートしています。
	*標準的なP2Pプラットフォームはデバイス転送機能をサポートしていますが、RTOSのP2Pプラットフォームはデバイス転送機能をサポートしていません。
	*標準のP2Pデバイス側パラメータとRTOSデバイス側パラメータは異なるパラメータセットであり、両方のプラットフォームを持っている場合、パラメータを混在させることはできません。
```

3. ConnectionTester：接続テストツール。 機器側との接続の効果を検証・分析するために使用します。
1. ReadWriteTester: 読み書き転送テストツール、ListenTester_PPCSと一緒に使用する。
1. 詳細は、SDK Release_PPCS_3.1.0/Doc/ ディレクトリ内のP2P SDKドキュメントおよびP2Pテクニカルホワイトペーパーを参照してください。

`www.DeepL.com/Translatorで翻訳しました。`

# 原文
```
Release_PPCS_3.1.0 20180524：
1.P2P 库更新为最新版本 3.1.0 版。
2.ListenTester_PPCS：模拟设备端的测试程序，包括模拟标准P2P平台设备端与RTOS P2P平台设备端。
	*模拟标准P2P设备端测试：只能测试P2P，不支持休眠唤醒的测试。
	*模拟RTOS P2P设备端测试：需要带入唤醒参数（WakeupKey,WakeupServerIP），若不带，只能测试RTOS P2P部分。
PS:	
	*标准P2P平台不支持设备休眠唤醒，RTOS P2P平台支持设备休眠唤醒。
	*标准P2P平台支持设备转发功能，RTOS P2P平台不支持设备转发功能。
	*标准P2P设备端参数与RTOS设备端参数为两套不同平台的参数，若同时拥有这两套平台，则参数不能混用。

3.ConnectionTester：连接测试工具。用来测试分析与设备端的连接效果。
4.ReadWriteTester：读写传输测试工具，需配合 ListenTester_PPCS 来测试。
5.更多详细说明请参考SDK Release_PPCS_3.1.0/Doc/目录下 P2P SDK 说明文档与P2P 技术白皮书。
```

