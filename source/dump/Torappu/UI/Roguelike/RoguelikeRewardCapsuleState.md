# RoguelikeRewardCapsuleState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeRewardCapsuleShowView _view`

- `RoguelikeMenuAdapter m_menuAdapter`

- `RoguelikeRewardCapsuleStateBean m_stateBean`


## Methods

- `Void OnClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardCapsuleState : PopupFloatState
{
	private RoguelikeRewardCapsuleShowView _view; // 0x70
	private RoguelikeMenuAdapter m_menuAdapter; // 0x78
	private RoguelikeRewardCapsuleStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a8ebd8 VA: 0x75950a6bd8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a8ec40 VA: 0x75950a6c40
	protected override Void OnEnter() { }
	// RVA: 0x2a8ee18 VA: 0x75950a6e18
	public Void OnClick() { }
	// RVA: 0x2a8ee8c VA: 0x75950a6e8c
	public Void .ctor() { }
	// RVA: 0x2a8ef38 VA: 0x75950a6f38
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```