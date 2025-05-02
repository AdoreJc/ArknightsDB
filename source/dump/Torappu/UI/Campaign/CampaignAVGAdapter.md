# CampaignAVGAdapter

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String m_waitForSignal`


## Methods

- `Boolean _ExecuteFocusZone(Command)`

- `Boolean _ExecuteRegisterZoneBtn(Command)`

- `Void _ReceiveFocusZoneSignal(Command)`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignAVGAdapter : ExecutorComponent
{
	private String m_waitForSignal; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_GetSignalReceivers; // 0x8
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteFocusZone; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteRegisterZoneBtn; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveFocusZoneSignal; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2dc6f14 VA: 0x75953def14
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x2dc711c VA: 0x75953df11c
	public override Dictionary`2 GetSignalReceivers() { }
	// RVA: 0x2dc7258 VA: 0x75953df258
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2dc72bc VA: 0x75953df2bc
	private Boolean _ExecuteFocusZone(Command command) { }
	// RVA: 0x2dc786c VA: 0x75953df86c
	private Boolean _ExecuteRegisterZoneBtn(Command command) { }
	// RVA: 0x2dc7bdc VA: 0x75953dfbdc
	private Void _ReceiveFocusZoneSignal(Command command) { }
	// RVA: 0x2dc7cf4 VA: 0x75953dfcf4
	private Void Start() { }
	// RVA: 0x2dc7db0 VA: 0x75953dfdb0
	private Void OnDestroy() { }
	// RVA: 0x2dc7e6c VA: 0x75953dfe6c
	public Void .ctor() { }
	// RVA: 0x2dc7edc VA: 0x75953dfedc
	private Dictionary`2 <>xLuaBaseProxy_GetSignalReceivers() { }
}
```