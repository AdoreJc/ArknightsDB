# HGDownloadSDKPluginDefault

**Namespace:** `Hypergryph.SDK`


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
public class HGDownloadSDKPluginDefault : IHGDownloadSDK
{


	// RVA: 0x66d1b20 VA: 0x7598ce9b20
	public Void .ctor() { }
	// RVA: 0x66d1b28 VA: 0x7598ce9b28
	public Int32 init(String config) { }
	// RVA: 0x66d1b34 VA: 0x7598ce9b34
	public Int64 download(String versionId, String downloadFiles, String decompressPath, Boolean useMobileData, Boolean needCompress) { }
	// RVA: 0x66d1b40 VA: 0x7598ce9b40
	public Int32 enableMobileData(Int64 taskId) { }
	// RVA: 0x66d1b4c VA: 0x7598ce9b4c
	public Int32 pause(Int64 taskId) { }
	// RVA: 0x66d1b58 VA: 0x7598ce9b58
	public Int32 resume(Int64 taskId) { }
	// RVA: 0x66d1b64 VA: 0x7598ce9b64
	public Int32 cancel(Int64 taskId) { }
	// RVA: 0x66d1b70 VA: 0x7598ce9b70
	public Int32 cancelAndClear(Int64 taskId) { }
	// RVA: 0x66d1b7c VA: 0x7598ce9b7c
	public Int32 clearAllTasks() { }
	// RVA: 0x66d1b88 VA: 0x7598ce9b88
	public Int32 finish(Int64 taskId) { }
	// RVA: 0x66d1b94 VA: 0x7598ce9b94
	public Int32 getSDKState() { }
	// RVA: 0x66d1ba0 VA: 0x7598ce9ba0
	public Int32 getTaskState(Int64 taskId) { }
	// RVA: 0x66d1bac VA: 0x7598ce9bac
	public String getTaskInfo(Int64 taskId) { }
	// RVA: 0x66d1bec VA: 0x7598ce9bec
	public Int64 getDownloadSpeed(Int64 taskId) { }
	// RVA: 0x66d1bf8 VA: 0x7598ce9bf8
	public Int64 getDownloadedSize(Int64 taskId) { }
	// RVA: 0x66d1c04 VA: 0x7598ce9c04
	public Int64 getTotalDownloadSize(Int64 taskId) { }
	// RVA: 0x66d1c10 VA: 0x7598ce9c10
	public Int32 getDecompressedProgress(Int64 taskId) { }
	// RVA: 0x66d1c1c VA: 0x7598ce9c1c
	public Int32 setLanguageType(Int32 type) { }
	// RVA: 0x66d1c28 VA: 0x7598ce9c28
	public Int32 setNotificationTitle(String title) { }
	// RVA: 0x66d1c34 VA: 0x7598ce9c34
	public Int64 getEstimatedDownloadSize(String versionId, String downloadFiles) { }
}
```