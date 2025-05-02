# UsedCardNumChangeTween

**Namespace:** ` `


## Fields

- `UIBattleLegionWidgetsPanel m_closure`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UsedCardNumChangeTween : UISwitchTween
{
	private UIBattleLegionWidgetsPanel m_closure; // 0x38
	private const Single TIPS_MOVE_START; // 0x0
	private const Single TIPS_MOVE_DUR; // 0x0
	private static readonly Vector2 CARD_GET_TIPS_START; // 0x0
	private static readonly Vector2 CARD_GET_TIPS_END; // 0x8
	private static readonly Quaternion CARD_END_REVERSE_ROTATION; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x28
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x30
	private static DelegateBridge __Hotfix0_ResetToState; // 0x38


	// RVA: 0x1dbaef4 VA: 0x75943d2ef4
	public Void .ctor(UIBattleLegionWidgetsPanel closure) { }
	// RVA: 0x1dbcbac VA: 0x75943d4bac
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x1dbcd14 VA: 0x75943d4d14
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x1dbce7c VA: 0x75943d4e7c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x1dbd004 VA: 0x75943d5004
	private static Void .cctor() { }
	// RVA: 0x1dbd078 VA: 0x75943d5078
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```