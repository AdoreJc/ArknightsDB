# SandboxV2EnemyRushTrackerState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _enterAnim`

- `SandboxV2EnemyRushTrackerView _view`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `SandboxV2EnemyRushTrackerProperty m_property`


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
public class SandboxV2EnemyRushTrackerState : SandboxV2TrackerState, IValueMsgReceiver
{
	private UIAnimationLocation _enterAnim; // 0x80
	private SandboxV2EnemyRushTrackerView _view; // 0x90
	private Boolean m_isInited; // 0x98
	private Tween m_enterTween; // 0xa0
	private SandboxV2EnemyRushTrackerProperty m_property; // 0xa8
	public const Int32 ON_ITEM_SELECT; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__UpdateData; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnItemSelect; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x25519ec VA: 0x7594b699ec
	protected override Void OnEnter() { }
	// RVA: 0x2551e18 VA: 0x7594b69e18
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2551ae0 VA: 0x7594b69ae0
	private Void _InitIfNot() { }
	// RVA: 0x2551d3c VA: 0x7594b69d3c
	private Void _PlayEnterAnim() { }
	// RVA: 0x2551bd8 VA: 0x7594b69bd8
	private Void _UpdateData() { }
	// RVA: 0x255219c VA: 0x7594b6a19c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x255226c VA: 0x7594b6a26c
	private Void _OnItemSelect(String selectedId) { }
	// RVA: 0x2552a20 VA: 0x7594b6aa20
	public Void .ctor() { }
	// RVA: 0x2552ba4 VA: 0x7594b6aba4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```