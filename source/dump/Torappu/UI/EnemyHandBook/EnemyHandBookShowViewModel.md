# EnemyHandBookShowViewModel

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `Boolean needShuffleHide`

- `String selectedEnemyId`

- `Boolean disableNewFlag`

- `EnemyHandbookShuffleViewModel shuffleViewModel`


## Properties

- `Int32 selectIndex`


## Methods

- `Void CheckLink()`

- `Void set_selectIndex(Int32)`

- `Boolean TryGetSelectEnemy(out)`

- `EnemyHandBookEverViewModel GetSelectEnemyHandbook(out)`

- `Void ShuffleHideEnemyIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookShowViewModel : IHotfixable
{
	public List`1 enemyList; // 0x10
	public Boolean needShuffleHide; // 0x18
	public String selectedEnemyId; // 0x20
	public Boolean disableNewFlag; // 0x28
	public EnemyHandbookShuffleViewModel shuffleViewModel; // 0x30
	private List`1 m_resultList; // 0x38
	private static DelegateBridge __Hotfix0_CheckLink; // 0x0
	private static DelegateBridge __Hotfix0_set_selectIndex; // 0x8
	private static DelegateBridge __Hotfix0_TryGetSelectEnemy; // 0x10
	private static DelegateBridge __Hotfix0_GetList; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectEnemyHandbook; // 0x20
	private static DelegateBridge __Hotfix0_ShuffleHideEnemyIfNeed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 selectIndex { set; }

	// RVA: 0x293a2fc VA: 0x7594f522fc
	public Void CheckLink() { }
	// RVA: 0x293a6e8 VA: 0x7594f526e8
	public Void set_selectIndex(Int32 value) { }
	// RVA: 0x2937960 VA: 0x7594f4f960
	public Boolean TryGetSelectEnemy(out EnemyHandBookEverViewModel viewModel) { }
	// RVA: 0x29376ec VA: 0x7594f4f6ec
	public List`1 GetList() { }
	// RVA: 0x293a7b8 VA: 0x7594f527b8
	public EnemyHandBookEverViewModel GetSelectEnemyHandbook(out Int32 index) { }
	// RVA: 0x293a8e4 VA: 0x7594f528e4
	public Void ShuffleHideEnemyIfNeed() { }
	// RVA: 0x293aa04 VA: 0x7594f52a04
	public Void .ctor() { }
}
```