# PendingCardNumChangeTween

**Namespace:** ` `


## Fields

- `UIBattleLegionWidgetsPanel m_closure`


## Methods

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PendingCardNumChangeTween : UISwitchTween
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


	// RVA: 0x1dbae50 VA: 0x75943d2e50
	public Void .ctor(UIBattleLegionWidgetsPanel closure) { }
	// RVA: 0x1dbc6d4 VA: 0x75943d46d4
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x1dbc83c VA: 0x75943d483c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x1dbc9a4 VA: 0x75943d49a4
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x1dbcb2c VA: 0x75943d4b2c
	private static Void .cctor() { }
	// RVA: 0x1dbcba0 VA: 0x75943d4ba0
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```