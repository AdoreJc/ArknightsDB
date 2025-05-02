# SandboxV2OtherTrackerState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _enterAnim`

- `SandboxV2OtherTrackerView _view`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `SandboxV2OtherTrackerViewModelProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _UpdateData()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnItemSelect(String)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2OtherTrackerState : SandboxV2TrackerState, IValueMsgReceiver
{
	private UIAnimationLocation _enterAnim; // 0x80
	private SandboxV2OtherTrackerView _view; // 0x90
	private Boolean m_isInited; // 0x98
	private Tween m_enterTween; // 0xa0
	private SandboxV2OtherTrackerViewModelProperty m_property; // 0xa8
	public const Int32 ON_ITEM_SELECT; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnItemSelect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2552ba8 VA: 0x7594b6aba8
	protected override Void OnEnter() { }
	// RVA: 0x2552f60 VA: 0x7594b6af60
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2552c28 VA: 0x7594b6ac28
	private Void _InitIfNot() { }
	// RVA: 0x2552e84 VA: 0x7594b6ae84
	private Void _PlayEnterAnim() { }
	// RVA: 0x2552d20 VA: 0x7594b6ad20
	private Void _UpdateData() { }
	// RVA: 0x2553480 VA: 0x7594b6b480
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2553550 VA: 0x7594b6b550
	private Void _OnItemSelect(String selectedId) { }
	// RVA: 0x255384c VA: 0x7594b6b84c
	public Void .ctor() { }
	// RVA: 0x2553960 VA: 0x7594b6b960
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```