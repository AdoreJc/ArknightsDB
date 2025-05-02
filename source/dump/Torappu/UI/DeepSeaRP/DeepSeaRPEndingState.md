# DeepSeaRPEndingState

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _rectBack`

- `DeepSeaRPEndingZoneGroupView _view`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _InitView()`

- `Void _EventOnZoneClick(String)`

- `Void _CloseState(Action)`

- `Void CloseState()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPEndingState : PopupFadeState
{
	private RectTransform _rectBack; // 0x70
	private DeepSeaRPEndingZoneGroupView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__InitView; // 0x18
	private static DelegateBridge __Hotfix0__EventOnZoneClick; // 0x20
	private static DelegateBridge __Hotfix0__CloseState; // 0x28
	private static DelegateBridge __Hotfix0_CloseState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x29d8368 VA: 0x7594ff0368
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29d83cc VA: 0x7594ff03cc
	protected override Void OnEnter() { }
	// RVA: 0x29d8448 VA: 0x7594ff0448
	private Void _InitIfNot() { }
	// RVA: 0x29d854c VA: 0x7594ff054c
	private Void _InitView() { }
	// RVA: 0x29d8a5c VA: 0x7594ff0a5c
	private Void _EventOnZoneClick(String zoneId) { }
	// RVA: 0x29d8d10 VA: 0x7594ff0d10
	private Void _CloseState(Action callbackBeforeDismiss) { }
	// RVA: 0x29d8ffc VA: 0x7594ff0ffc
	public Void CloseState() { }
	// RVA: 0x29d9068 VA: 0x7594ff1068
	public Void .ctor() { }
	// RVA: 0x29d90d8 VA: 0x7594ff10d8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```