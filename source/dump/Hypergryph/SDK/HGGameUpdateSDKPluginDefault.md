# HGGameUpdateSDKPluginDefault

**Namespace:** `Hypergryph.SDK`


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
public class HGGameUpdateSDKPluginDefault : IHGGameUpdateSDK
{


	// RVA: 0x5ec12b0 VA: 0x75984d92b0
	public Int32 Init(String config) { }
	// RVA: 0x5ec1320 VA: 0x75984d9320
	public Void GetLatestGame() { }
	// RVA: 0x5ec13cc VA: 0x75984d93cc
	public Int64 Update(Int32 updateType, Boolean useMobileData) { }
	// RVA: 0x5ec1444 VA: 0x75984d9444
	public Int32 EnableMobileData(Int64 taskId) { }
	// RVA: 0x5ec14b4 VA: 0x75984d94b4
	public Int32 GetTaskState(Int64 taskId) { }
	// RVA: 0x5ec1524 VA: 0x75984d9524
	public Int32 Pause(Int64 taskId) { }
	// RVA: 0x5ec1594 VA: 0x75984d9594
	public Int32 Resume(Int64 taskId) { }
	// RVA: 0x5ec1604 VA: 0x75984d9604
	public Int32 CancelAndClear(Int64 taskId) { }
	// RVA: 0x5ec1674 VA: 0x75984d9674
	public Int32 Cancel(Int64 taskId) { }
	// RVA: 0x5ec16e4 VA: 0x75984d96e4
	public Int32 Install(Int64 taskId) { }
	// RVA: 0x5ec1754 VA: 0x75984d9754
	public Int32 ClearAllTask() { }
	// RVA: 0x5ec17c4 VA: 0x75984d97c4
	public Int64 GetDownloadSpeed(Int64 taskId) { }
	// RVA: 0x5ec1834 VA: 0x75984d9834
	public Int64 GetDownloadedSize(Int64 taskId) { }
	// RVA: 0x5ec18a4 VA: 0x75984d98a4
	public Int64 GetTotalDownloadSize(Int64 taskId) { }
	// RVA: 0x5ec1914 VA: 0x75984d9914
	public Int64 GetEstimatedDownloadSize(Int32 updateType) { }
	// RVA: 0x5ec1984 VA: 0x75984d9984
	public Int32 SetNotificationTitle(String titleConfig) { }
	// RVA: 0x5ec19f4 VA: 0x75984d99f4
	public Void .ctor() { }
}
```