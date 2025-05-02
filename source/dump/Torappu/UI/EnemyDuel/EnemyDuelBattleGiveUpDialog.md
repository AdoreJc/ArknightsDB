# EnemyDuelBattleGiveUpDialog

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `EnemyDuelBattleGiveUpView _view`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnBackBtnClicked()`

- `Void EventOnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleGiveUpDialog : UICompDialog`1
{
	private EnemyDuelBattleGiveUpView _view; // 0x48
	private readonly EnemyDuelBattleGiveUpProperty m_prop; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2986f7c VA: 0x7594f9ef7c
	protected override Void OnRender(Options input) { }
	// RVA: 0x298704c VA: 0x7594f9f04c
	private Void _InitIfNot() { }
	// RVA: 0x2987278 VA: 0x7594f9f278
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x298734c VA: 0x7594f9f34c
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2987420 VA: 0x7594f9f420
	public Void .ctor() { }
}
```