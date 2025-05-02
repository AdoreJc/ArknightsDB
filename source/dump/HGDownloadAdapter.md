# HGDownloadAdapter

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HGDownloadAdapter : Adapter
{


	// RVA: 0x3737c9c VA: 0x7595d4fc9c
	public override String ConfigToJson(HGConfig config) { }
	// RVA: 0x3737d2c VA: 0x7595d4fd2c
	public override HGDownloadTaskInfo JsonToTaskInfo(String json) { }
	// RVA: 0x3737eb0 VA: 0x7595d4feb0
	public override String FileListToJson(IList`1 files) { }
	// RVA: 0x3738020 VA: 0x7595d50020
	public override String GetDecompressFolder() { }
	// RVA: 0x3738028 VA: 0x7595d50028
	public override Boolean NeedDecompress() { }
	// RVA: 0x3738030 VA: 0x7595d50030
	public override HGDownloadLanType GetLanguageType() { }
	// RVA: 0x37380a8 VA: 0x7595d500a8
	public override HGNotificationTitle GetNotificationTitle() { }
	// RVA: 0x3738138 VA: 0x7595d50138
	public override String NotificationTitleToJson(HGNotificationTitle titleConfig) { }
	// RVA: 0x37381d4 VA: 0x7595d501d4
	public override Void OnSDKInternalError(Int32 errorCode) { }
	// RVA: 0x37383d0 VA: 0x7595d503d0
	public override Void LogError(String errorInfo) { }
	// RVA: 0x3738428 VA: 0x7595d50428
	public Void .ctor() { }
}
```