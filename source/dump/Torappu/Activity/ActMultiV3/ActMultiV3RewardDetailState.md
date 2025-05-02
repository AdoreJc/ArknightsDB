# ActMultiV3RewardDetailState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3RewardDetailView _view`

- `StateBean m_stateBean`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void OnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3RewardDetailState : PopupFloatState
{
	private ActMultiV3RewardDetailView _view; // 0x70
	private StateBean m_stateBean; // 0x78
	private Boolean m_inited; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnBackClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30f2800 VA: 0x759570a800
	private Void _InitIfNot() { }
	// RVA: 0x30f28b0 VA: 0x759570a8b0
	protected override Void OnEnter() { }
	// RVA: 0x30f2954 VA: 0x759570a954
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30f29bc VA: 0x759570a9bc
	public Void OnBackClicked() { }
	// RVA: 0x30f2ac0 VA: 0x759570aac0
	public Void .ctor() { }
	// RVA: 0x30f2c18 VA: 0x759570ac18
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```