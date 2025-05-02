# Act1VAutoChessEntrySettleGameEnterExitAnim

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `UIAnimationLocation _winEnterFromMainAnim`

- `UIAnimationLocation _loseEnterFromMainAnim`

- `UIAnimationLocation _winEnterFromBattleAnim`

- `UIAnimationLocation _loseEnterFromBattleAnim`

- `UIAnimationLocation _exitAnim`

- `Boolean m_cachedWin`

- `Boolean m_cachedFromBattle`


## Methods

- `Void SetConfig(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntrySettleGameEnterExitAnim : Act1VAutoChessEntrySubViewAbstractEnterExitAnim
{
	private UIAnimationLocation _winEnterFromMainAnim; // 0x18
	private UIAnimationLocation _loseEnterFromMainAnim; // 0x28
	private UIAnimationLocation _winEnterFromBattleAnim; // 0x38
	private UIAnimationLocation _loseEnterFromBattleAnim; // 0x48
	private UIAnimationLocation _exitAnim; // 0x58
	private Boolean m_cachedWin; // 0x68
	private Boolean m_cachedFromBattle; // 0x69
	private static DelegateBridge __Hotfix0_get_showType; // 0x0
	private static DelegateBridge __Hotfix0_get_enterAnim; // 0x8
	private static DelegateBridge __Hotfix0_get_exitAnim; // 0x10
	private static DelegateBridge __Hotfix0_SetConfig; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override ShowType showType { get; }
	public override UIAnimationLocation enterAnim { get; }
	public override UIAnimationLocation exitAnim { get; }

	// RVA: 0x33458d4 VA: 0x759595d8d4
	public override ShowType get_showType() { }
	// RVA: 0x334593c VA: 0x759595d93c
	public override UIAnimationLocation get_enterAnim() { }
	// RVA: 0x33459cc VA: 0x759595d9cc
	public override UIAnimationLocation get_exitAnim() { }
	// RVA: 0x3345a30 VA: 0x759595da30
	public Void SetConfig(Boolean win, Boolean fromBattle) { }
	// RVA: 0x3345ac0 VA: 0x759595dac0
	public Void .ctor() { }
}
```