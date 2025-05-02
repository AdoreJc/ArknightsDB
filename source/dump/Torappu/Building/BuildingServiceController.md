# BuildingServiceController

**Namespace:** `Torappu.Building`


## Fields

- `CountDownTask m_updateCountDown`


## Methods

- `Void Tick()`

- `Void Init()`

- `Void NotifyPlayerDataChanged()`

- `Void AddPlayerDataListener(Action`1)`

- `Void RemovePlayerDataListener(Action`1)`

- `Void _UpdateCountDown()`

- `DateTime _GetNextUpdateTime()`

- `Void _SendSyncDataRequest()`

- `Void <SendRequest>b__8_0(ResType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingServiceController
{
	private CountDownTask m_updateCountDown; // 0x10
	private ListSet`1 m_playerDataListeners; // 0x18
	private static DateTime s_beforeServiceTs; // 0x0
	private static DelegateBridge __Hotfix0_Tick; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_NotifyPlayerDataChanged; // 0x18
	private static DelegateBridge __Hotfix0_AddPlayerDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RemovePlayerDataListener; // 0x28
	private static DelegateBridge __Hotfix0_SendRequest; // 0x30
	private static DelegateBridge __Hotfix0__UpdateCountDown; // 0x38
	private static DelegateBridge __Hotfix0__GetNextUpdateTime; // 0x40
	private static DelegateBridge __Hotfix0__PickNextUpdateTime; // 0x48
	private static DelegateBridge __Hotfix0__SendSyncDataRequest; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3797338 VA: 0x7595daf338
	public Void Tick() { }
	// RVA: 0x37973c4 VA: 0x7595daf3c4
	public Void Init() { }
	// RVA: 0x37976e8 VA: 0x7595daf6e8
	public Void NotifyPlayerDataChanged() { }
	// RVA: 0x37977f0 VA: 0x7595daf7f0
	public Void AddPlayerDataListener(Action`1 listener) { }
	// RVA: 0x37978b4 VA: 0x7595daf8b4
	public Void RemovePlayerDataListener(Action`1 listener) { }
	// RVA: 0x VA: 0x0
	public ResultHandler`1 SendRequest(Request request) { }
	// RVA: 0x379743c VA: 0x7595daf43c
	private Void _UpdateCountDown() { }
	// RVA: 0x3797964 VA: 0x7595daf964
	private DateTime _GetNextUpdateTime() { }
	// RVA: 0x3797cb8 VA: 0x7595dafcb8
	private static DateTime _PickNextUpdateTime(DateTime curCandidate, DateTime newCandidate) { }
	// RVA: 0x3797a38 VA: 0x7595dafa38
	private Void _SendSyncDataRequest() { }
	// RVA: 0x3798110 VA: 0x7595db0110
	public Void .ctor() { }
	// RVA: 0x37981e4 VA: 0x7595db01e4
	private static Void .cctor() { }
	// RVA: 0x VA: 0x0
	private Void <SendRequest>b__8_0(ResType _) { }
}
```