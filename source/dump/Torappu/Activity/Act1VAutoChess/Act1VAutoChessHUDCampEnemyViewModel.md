# Act1VAutoChessHUDCampEnemyViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <presentingIndex>k__BackingField`

- `Int32 m_currentIndex`


## Properties

- `Int32 presentingIndex`


## Methods

- `Int32 get_presentingIndex()`

- `Void set_presentingIndex(Int32)`

- `Act1VAutoChessHUDCampEnemyItemViewModel GetEnemyByForceId(String)`

- `Act1VAutoChessHUDCampEnemyItemViewModel GetCurrentEnemy()`

- `Void LoadData(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Boolean SwitchIndex(Boolean)`

- `Void _LoadItems(ActivityAutoChessVerify1Data, AutoChessGame, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampEnemyViewModel : IHotfixable
{
	private readonly List`1 m_items; // 0x10
	private Int32 <presentingIndex>k__BackingField; // 0x18
	private Int32 m_currentIndex; // 0x1c
	private static DelegateBridge __Hotfix0_get_items; // 0x0
	private static DelegateBridge __Hotfix0_get_presentingIndex; // 0x8
	private static DelegateBridge __Hotfix0_set_presentingIndex; // 0x10
	private static DelegateBridge __Hotfix0_GetEnemyByForceId; // 0x18
	private static DelegateBridge __Hotfix0_GetCurrentEnemy; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_SwitchIndex; // 0x30
	private static DelegateBridge __Hotfix0__LoadItems; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 items { get; }
	public Int32 presentingIndex { get; set; }

	// RVA: 0x3366e54 VA: 0x759597ee54
	public List`1 get_items() { }
	// RVA: 0x3366dec VA: 0x759597edec
	public Int32 get_presentingIndex() { }
	// RVA: 0x336c634 VA: 0x7595984634
	private Void set_presentingIndex(Int32 value) { }
	// RVA: 0x336c6b0 VA: 0x75959846b0
	public Act1VAutoChessHUDCampEnemyItemViewModel GetEnemyByForceId(String forceId) { }
	// RVA: 0x336c800 VA: 0x7595984800
	public Act1VAutoChessHUDCampEnemyItemViewModel GetCurrentEnemy() { }
	// RVA: 0x336c888 VA: 0x7595984888
	public Void LoadData(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336cbf4 VA: 0x7595984bf4
	public Boolean SwitchIndex(Boolean resetToCurrent) { }
	// RVA: 0x336c954 VA: 0x7595984954
	private Void _LoadItems(ActivityAutoChessVerify1Data gameData, AutoChessGame game, Dictionary`2 forces) { }
	// RVA: 0x336d2b8 VA: 0x75959852b8
	public Void .ctor() { }
}
```