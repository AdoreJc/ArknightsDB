# ClimbTowerTrapGroupViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `TrapGroupType m_trapGroupType`


## Properties

- `TrapGroupType trapGroupType`


## Methods

- `TrapGroupType get_trapGroupType()`

- `Void InitData(TrapGroupType)`

- `Boolean IsEmpty()`

- `Void _InitGodCardGroupData()`

- `Void _InitCurseCardGroupData()`

- `Void _InitTrapCardGroupData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapGroupViewModel : IHotfixable
{
	private List`1 m_trapList; // 0x10
	private TrapGroupType m_trapGroupType; // 0x18
	private static DelegateBridge __Hotfix0_get_itemList; // 0x0
	private static DelegateBridge __Hotfix0_get_trapGroupType; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x18
	private static DelegateBridge __Hotfix0__InitGodCardGroupData; // 0x20
	private static DelegateBridge __Hotfix0__InitCurseCardGroupData; // 0x28
	private static DelegateBridge __Hotfix0__InitTrapCardGroupData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 itemList { get; }
	public TrapGroupType trapGroupType { get; }

	// RVA: 0x2c8e820 VA: 0x75952a6820
	public List`1 get_itemList() { }
	// RVA: 0x2c8e614 VA: 0x75952a6614
	public TrapGroupType get_trapGroupType() { }
	// RVA: 0x2c90508 VA: 0x75952a8508
	public Void InitData(TrapGroupType trapGroupType) { }
	// RVA: 0x2c90620 VA: 0x75952a8620
	public Boolean IsEmpty() { }
	// RVA: 0x2c906a4 VA: 0x75952a86a4
	private Void _InitGodCardGroupData() { }
	// RVA: 0x2c908c0 VA: 0x75952a88c0
	private Void _InitCurseCardGroupData() { }
	// RVA: 0x2c90b3c VA: 0x75952a8b3c
	private Void _InitTrapCardGroupData() { }
	// RVA: 0x2c90444 VA: 0x75952a8444
	public Void .ctor() { }
}
```