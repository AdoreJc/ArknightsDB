# HGGameUpdateInterface

**Namespace:** `Torappu.SDK`


## Methods

- `Int32 Init(String, IHGGameUpdateSDKCallback)`

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
// Dll : Torappu.Common.dll
// Namespace : Torappu.SDK
public class HGGameUpdateInterface : Singleton`1, IGameUpdateInterface
{
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate121 __Hotfix0_Init; // 0x8
	private static __XLua_Gen_Delegate1 __Hotfix0_GetLatestGame; // 0x10
	private static __XLua_Gen_Delegate122 __Hotfix0_Update; // 0x18
	private static __XLua_Gen_Delegate123 __Hotfix0_EnableMobileData; // 0x20
	private static __XLua_Gen_Delegate123 __Hotfix0_GetTaskState; // 0x28
	private static __XLua_Gen_Delegate123 __Hotfix0_Pause; // 0x30
	private static __XLua_Gen_Delegate123 __Hotfix0_Resume; // 0x38
	private static __XLua_Gen_Delegate123 __Hotfix0_CancelAndClear; // 0x40
	private static __XLua_Gen_Delegate123 __Hotfix0_Cancel; // 0x48
	private static __XLua_Gen_Delegate123 __Hotfix0_Install; // 0x50
	private static __XLua_Gen_Delegate10 __Hotfix0_ClearAllTask; // 0x58
	private static __XLua_Gen_Delegate124 __Hotfix0_GetDownloadSpeed; // 0x60
	private static __XLua_Gen_Delegate124 __Hotfix0_GetDownloadedSize; // 0x68
	private static __XLua_Gen_Delegate124 __Hotfix0_GetTotalDownloadSize; // 0x70
	private static __XLua_Gen_Delegate125 __Hotfix0_GetEstimatedDownloadSize; // 0x78
	private static __XLua_Gen_Delegate126 __Hotfix0_SetNotificationTitle; // 0x80


	// RVA: 0x678f9c8 VA: 0x7598da79c8
	private Void .ctor() { }
	// RVA: 0x678fa60 VA: 0x7598da7a60
	public Int32 Init(String config, IHGGameUpdateSDKCallback callback) { }
	// RVA: 0x678faf4 VA: 0x7598da7af4
	public Void GetLatestGame() { }
	// RVA: 0x678fb64 VA: 0x7598da7b64
	public Int64 Update(Int32 updateType, Boolean useMobileData) { }
	// RVA: 0x678fbf8 VA: 0x7598da7bf8
	public Int32 EnableMobileData(Int64 taskId) { }
	// RVA: 0x678fc80 VA: 0x7598da7c80
	public Int32 GetTaskState(Int64 taskId) { }
	// RVA: 0x678fd08 VA: 0x7598da7d08
	public Int32 Pause(Int64 taskId) { }
	// RVA: 0x678fd90 VA: 0x7598da7d90
	public Int32 Resume(Int64 taskId) { }
	// RVA: 0x678fe18 VA: 0x7598da7e18
	public Int32 CancelAndClear(Int64 taskId) { }
	// RVA: 0x678fea0 VA: 0x7598da7ea0
	public Int32 Cancel(Int64 taskId) { }
	// RVA: 0x678ff28 VA: 0x7598da7f28
	public Int32 Install(Int64 taskId) { }
	// RVA: 0x678ffb0 VA: 0x7598da7fb0
	public Int32 ClearAllTask() { }
	// RVA: 0x6790020 VA: 0x7598da8020
	public Int64 GetDownloadSpeed(Int64 taskId) { }
	// RVA: 0x67900a8 VA: 0x7598da80a8
	public Int64 GetDownloadedSize(Int64 taskId) { }
	// RVA: 0x6790130 VA: 0x7598da8130
	public Int64 GetTotalDownloadSize(Int64 taskId) { }
	// RVA: 0x67901b8 VA: 0x7598da81b8
	public Int64 GetEstimatedDownloadSize(Int32 updateType) { }
	// RVA: 0x6790240 VA: 0x7598da8240
	public Int32 SetNotificationTitle(String titleConfig) { }
}
```