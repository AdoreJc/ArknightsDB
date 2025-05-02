# CountingPartSwitchTween

**Namespace:** ` `


## Fields

- `CharacterLvlupHomeView m_closure`

- `Vector2 m_tagInitAnchorPos`

- `Vector2 m_countingAnchorPos`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CountingPartSwitchTween : UISwitchTween
{
	private const Single TAG_MOVE_OFFSET; // 0x0
	private const Single COUNTING_MOVE_OFFSET; // 0x0
	private const Single DURATION_SHOW_TWEEN; // 0x0
	private const Single DURATION_HIDE_TWEEN; // 0x0
	private CharacterLvlupHomeView m_closure; // 0x38
	private Vector2 m_tagInitAnchorPos; // 0x40
	private Vector2 m_countingAnchorPos; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x8
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x10


	// RVA: 0x2d760a8 VA: 0x759538e0a8
	public Void .ctor(CharacterLvlupHomeView closure) { }
	// RVA: 0x2d7664c VA: 0x759538e64c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x2d767e4 VA: 0x759538e7e4
	protected override ITweenHandler GenerateTweenOfHide() { }
}
```