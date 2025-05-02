# SDKLoginAccountHistoryState

**Namespace:** `HGSDK.UI`


## Fields

- `Dropdown _list`


## Methods

- `Void _RefreshAccountList()`

- `Void _HandleChangeAccount(Int32)`

- `Void EventOnDelCurCount()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
internal class SDKLoginAccountHistoryState : UIState
{
	private Dropdown _list; // 0x58
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__RefreshAccountList; // 0x10
	private static DelegateBridge __Hotfix0__HandleChangeAccount; // 0x18
	private static DelegateBridge __Hotfix0_EventOnDelCurCount; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override LoginState myState { get; }

	// RVA: 0x35531f8 VA: 0x7595b6b1f8
	public override LoginState get_myState() { }
	// RVA: 0x3553260 VA: 0x7595b6b260
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x35532e8 VA: 0x7595b6b2e8
	private Void _RefreshAccountList() { }
	// RVA: 0x3553860 VA: 0x7595b6b860
	private Void _HandleChangeAccount(Int32 idx) { }
	// RVA: 0x3553910 VA: 0x7595b6b910
	public Void EventOnDelCurCount() { }
	// RVA: 0x35539c8 VA: 0x7595b6b9c8
	public Void .ctor() { }
	// RVA: 0x3553a58 VA: 0x7595b6ba58
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```