# HGGameUpdateSDKPluginAndroid

**Namespace:** `Hypergryph.SDK`


## Fields

- `AndroidJavaClass jc`

- `AndroidJavaObject currentActivity`

- `AndroidJavaClass updateSdk`


## Methods

- `Int32 Init(String)`

- `Void GetLatestGame()`

- `Int64 Update(Int32, Boolean)`

- `Int32 EnableMobileData(Int64)`

- `Int32 GetTaskState(Int64)`

- `Int32 Pause(Int64)`

- `Int32 Resume(Int64)`

- `Int32 CancelAndClear(Int64)`

- `Int32 Cancel(Int64)`

- `Int32 Install(Int64)`

- `Int32 ClearAllTask()`

- `Int64 GetDownloadSpeed(Int64)`

- `Int64 GetDownloadedSize(Int64)`

- `Int64 GetTotalDownloadSize(Int64)`

- `Int64 GetEstimatedDownloadSize(Int32)`

- `Int32 SetNotificationTitle(String)`


## Dump
```C#
// Dll : Hypergryph.GameUpdate.dll
// Namespace : Hypergryph.SDK
public class HGGameUpdateSDKPluginAndroid : IHGGameUpdateSDK
{
	private AndroidJavaClass jc; // 0x10
	private AndroidJavaObject currentActivity; // 0x18
	private AndroidJavaClass updateSdk; // 0x20


	// RVA: 0x5ebf5b4 VA: 0x75984d75b4
	public Void .ctor() { }
	// RVA: 0x5ec0188 VA: 0x75984d8188
	public Int32 Init(String config) { }
	// RVA: 0x5ec02a4 VA: 0x75984d82a4
	public Void GetLatestGame() { }
	// RVA: 0x5ec0350 VA: 0x75984d8350
	public Int64 Update(Int32 updateType, Boolean useMobileData) { }
	// RVA: 0x5ec0504 VA: 0x75984d8504
	public Int32 EnableMobileData(Int64 taskId) { }
	// RVA: 0x5ec061c VA: 0x75984d861c
	public Int32 GetTaskState(Int64 taskId) { }
	// RVA: 0x5ec0734 VA: 0x75984d8734
	public Int32 Pause(Int64 taskId) { }
	// RVA: 0x5ec084c VA: 0x75984d884c
	public Int32 Resume(Int64 taskId) { }
	// RVA: 0x5ec0964 VA: 0x75984d8964
	public Int32 CancelAndClear(Int64 taskId) { }
	// RVA: 0x5ec0a7c VA: 0x75984d8a7c
	public Int32 Cancel(Int64 taskId) { }
	// RVA: 0x5ec0b94 VA: 0x75984d8b94
	public Int32 Install(Int64 taskId) { }
	// RVA: 0x5ec0cac VA: 0x75984d8cac
	public Int32 ClearAllTask() { }
	// RVA: 0x5ec0d6c VA: 0x75984d8d6c
	public Int64 GetDownloadSpeed(Int64 taskId) { }
	// RVA: 0x5ec0e84 VA: 0x75984d8e84
	public Int64 GetDownloadedSize(Int64 taskId) { }
	// RVA: 0x5ec0f9c VA: 0x75984d8f9c
	public Int64 GetTotalDownloadSize(Int64 taskId) { }
	// RVA: 0x5ec10b4 VA: 0x75984d90b4
	public Int64 GetEstimatedDownloadSize(Int32 updateType) { }
	// RVA: 0x5ec11cc VA: 0x75984d91cc
	public Int32 SetNotificationTitle(String titleConfig) { }
}
```