# Act1VAutoChessEntryModeChoiceBackEnterExitAnim

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation m_cachedEnterAnim`

- `UIAnimationLocation m_cachedExitAnim`


## Methods

- `Void SetEnterAnim(UIAnimationLocation)`

- `Void SetExitAnim(UIAnimationLocation)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryModeChoiceBackEnterExitAnim : Act1VAutoChessEntrySubViewAbstractEnterExitAnim
{
	private UIAnimationLocation m_cachedEnterAnim; // 0x18
	private UIAnimationLocation m_cachedExitAnim; // 0x28
	private static DelegateBridge __Hotfix0_get_showType; // 0x0
	private static DelegateBridge __Hotfix0_get_enterAnim; // 0x8
	private static DelegateBridge __Hotfix0_get_exitAnim; // 0x10
	private static DelegateBridge __Hotfix0_SetEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0_SetExitAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ShowType showType { get; }
	public override UIAnimationLocation enterAnim { get; }
	public override UIAnimationLocation exitAnim { get; }

	// RVA: 0x3343858 VA: 0x759595b858
	public override ShowType get_showType() { }
	// RVA: 0x33438c0 VA: 0x759595b8c0
	public override UIAnimationLocation get_enterAnim() { }
	// RVA: 0x3343924 VA: 0x759595b924
	public override UIAnimationLocation get_exitAnim() { }
	// RVA: 0x3343988 VA: 0x759595b988
	public Void SetEnterAnim(UIAnimationLocation enterAnim) { }
	// RVA: 0x3343a18 VA: 0x759595ba18
	public Void SetExitAnim(UIAnimationLocation exitAnim) { }
	// RVA: 0x3343aa8 VA: 0x759595baa8
	public Void .ctor() { }
}
```