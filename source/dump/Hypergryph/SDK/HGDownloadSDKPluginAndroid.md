# HGDownloadSDKPluginAndroid

**Namespace:** `Hypergryph.SDK`


## Fields

- `AndroidJavaClass jc`

- `AndroidJavaObject currentActivity`

- `AndroidJavaClass downloadModule`

- `AndroidJavaObject appController`


## Methods

- `Int32 init(String)`

- `Int64 download(String, String, String, Boolean, Boolean)`

- `Int32 enableMobileData(Int64)`

- `Int32 pause(Int64)`

- `Int32 resume(Int64)`

- `Int32 cancel(Int64)`

- `Int32 cancelAndClear(Int64)`

- `Int32 clearAllTasks()`

- `Int32 finish(Int64)`

- `Int32 getSDKState()`

- `Int32 getTaskState(Int64)`

- `String getTaskInfo(Int64)`

- `Int64 getDownloadSpeed(Int64)`

- `Int64 getDownloadedSize(Int64)`

- `Int64 getTotalDownloadSize(Int64)`

- `Int32 getDecompressedProgress(Int64)`

- `Int32 setLanguageType(Int32)`

- `Int32 setNotificationTitle(String)`

- `Int64 getEstimatedDownloadSize(String, String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGDownloadSDKPluginAndroid : IHGDownloadSDK
{
	private AndroidJavaClass jc; // 0x10
	private AndroidJavaObject currentActivity; // 0x18
	private AndroidJavaClass downloadModule; // 0x20
	private AndroidJavaObject appController; // 0x28


	// RVA: 0x66cf754 VA: 0x7598ce7754
	public Void .ctor() { }
	// RVA: 0x66d05f8 VA: 0x7598ce85f8
	public Int32 init(String config) { }
	// RVA: 0x66d0714 VA: 0x7598ce8714
	public Int64 download(String versionId, String downloadFiles, String decompressPath, Boolean useMobileData, Boolean needCompress) { }
	// RVA: 0x66d0968 VA: 0x7598ce8968
	public Int32 enableMobileData(Int64 taskId) { }
	// RVA: 0x66d0a80 VA: 0x7598ce8a80
	public Int32 pause(Int64 taskId) { }
	// RVA: 0x66d0b98 VA: 0x7598ce8b98
	public Int32 resume(Int64 taskId) { }
	// RVA: 0x66d0cb0 VA: 0x7598ce8cb0
	public Int32 cancel(Int64 taskId) { }
	// RVA: 0x66d0dc8 VA: 0x7598ce8dc8
	public Int32 cancelAndClear(Int64 taskId) { }
	// RVA: 0x66d0ee0 VA: 0x7598ce8ee0
	public Int32 clearAllTasks() { }
	// RVA: 0x66d0fa0 VA: 0x7598ce8fa0
	public Int32 finish(Int64 taskId) { }
	// RVA: 0x66d10b8 VA: 0x7598ce90b8
	public Int32 getSDKState() { }
	// RVA: 0x66d1178 VA: 0x7598ce9178
	public Int32 getTaskState(Int64 taskId) { }
	// RVA: 0x66d1290 VA: 0x7598ce9290
	public String getTaskInfo(Int64 taskId) { }
	// RVA: 0x66d13a8 VA: 0x7598ce93a8
	public Int64 getDownloadSpeed(Int64 taskId) { }
	// RVA: 0x66d14c0 VA: 0x7598ce94c0
	public Int64 getDownloadedSize(Int64 taskId) { }
	// RVA: 0x66d15d8 VA: 0x7598ce95d8
	public Int64 getTotalDownloadSize(Int64 taskId) { }
	// RVA: 0x66d16f0 VA: 0x7598ce96f0
	public Int32 getDecompressedProgress(Int64 taskId) { }
	// RVA: 0x66d1808 VA: 0x7598ce9808
	public Int32 setLanguageType(Int32 type) { }
	// RVA: 0x66d1920 VA: 0x7598ce9920
	public Int32 setNotificationTitle(String title) { }
	// RVA: 0x66d1a04 VA: 0x7598ce9a04
	public Int64 getEstimatedDownloadSize(String versionId, String downloadFiles) { }
}
```