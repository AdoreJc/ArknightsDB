# CardSelectPopTween

**Namespace:** ` `


## Fields

- `UICardLegionSelectItem m_closure`


## Methods

- `Void <>xLuaBaseProxy_AfterHideEffect()`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CardSelectPopTween : UISwitchTween
{
	private UICardLegionSelectItem m_closure; // 0x38
	private static readonly Vector2 SELECT_CARD_START_POS; // 0x0
	private static readonly Vector2 SELECT_CARD_END_POS; // 0x8
	private const Single SELECT_CARD_DUR; // 0x0
	private const Single SHOW_SELECT_PART_DUR; // 0x0
	private const Single HIDE_SELECT_PART_DUR; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x18
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x20
	private static DelegateBridge __Hotfix0_AfterHideEffect; // 0x28
	private static DelegateBridge __Hotfix0_ResetToState; // 0x30


	// RVA: 0x1dc14e8 VA: 0x75943d94e8
	public Void .ctor(UICardLegionSelectItem closure) { }
	// RVA: 0x1dc1f7c VA: 0x75943d9f7c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x1dc21cc VA: 0x75943da1cc
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x1dc241c VA: 0x75943da41c
	protected override Void AfterHideEffect() { }
	// RVA: 0x1dc24ac VA: 0x75943da4ac
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x1dc2634 VA: 0x75943da634
	private static Void .cctor() { }
	// RVA: 0x1dc2690 VA: 0x75943da690
	private Void <>xLuaBaseProxy_AfterHideEffect() { }
	// RVA: 0x1dc2698 VA: 0x75943da698
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```