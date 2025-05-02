# Act1AutoChessEntryTeamInfoEnterExitAnim

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation _exitAnim`

- `UIAnimationLocation m_cachedEnterAnim`


## Methods

- `Void SetEnterAnim(UIAnimationLocation)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1AutoChessEntryTeamInfoEnterExitAnim : Act1VAutoChessEntrySubViewAbstractEnterExitAnim
{
	private UIAnimationLocation _exitAnim; // 0x18
	private UIAnimationLocation m_cachedEnterAnim; // 0x28
	private static DelegateBridge __Hotfix0_get_showType; // 0x0
	private static DelegateBridge __Hotfix0_get_enterAnim; // 0x8
	private static DelegateBridge __Hotfix0_get_exitAnim; // 0x10
	private static DelegateBridge __Hotfix0_SetEnterAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override ShowType showType { get; }
	public override UIAnimationLocation enterAnim { get; }
	public override UIAnimationLocation exitAnim { get; }

	// RVA: 0x334ceec VA: 0x7595964eec
	public override ShowType get_showType() { }
	// RVA: 0x334cf54 VA: 0x7595964f54
	public override UIAnimationLocation get_enterAnim() { }
	// RVA: 0x334cfb8 VA: 0x7595964fb8
	public override UIAnimationLocation get_exitAnim() { }
	// RVA: 0x334d01c VA: 0x759596501c
	public Void SetEnterAnim(UIAnimationLocation enterAnim) { }
	// RVA: 0x334d0ac VA: 0x75959650ac
	public Void .ctor() { }
}
```