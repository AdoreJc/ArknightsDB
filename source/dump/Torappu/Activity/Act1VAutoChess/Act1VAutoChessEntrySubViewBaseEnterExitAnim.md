# Act1VAutoChessEntrySubViewBaseEnterExitAnim

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _exitAnim`

- `ShowType _showType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntrySubViewBaseEnterExitAnim : Act1VAutoChessEntrySubViewAbstractEnterExitAnim
{
	private UIAnimationLocation _enterAnim; // 0x18
	private UIAnimationLocation _exitAnim; // 0x28
	private ShowType _showType; // 0x38
	private static DelegateBridge __Hotfix0_get_showType; // 0x0
	private static DelegateBridge __Hotfix0_get_enterAnim; // 0x8
	private static DelegateBridge __Hotfix0_get_exitAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override ShowType showType { get; }
	public override UIAnimationLocation enterAnim { get; }
	public override UIAnimationLocation exitAnim { get; }

	// RVA: 0x333ccdc VA: 0x7595954cdc
	public override ShowType get_showType() { }
	// RVA: 0x333cd44 VA: 0x7595954d44
	public override UIAnimationLocation get_enterAnim() { }
	// RVA: 0x333cda8 VA: 0x7595954da8
	public override UIAnimationLocation get_exitAnim() { }
	// RVA: 0x333ce0c VA: 0x7595954e0c
	public Void .ctor() { }
}
```