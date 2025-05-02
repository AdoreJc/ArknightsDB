# Act1VAutoChessHUDCampEnemyItemViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int32 <forceHp>k__BackingField`

- `Int32 <forceHpMax>k__BackingField`

- `String <forceId>k__BackingField`

- `String <campIconId>k__BackingField`

- `String <campCharId>k__BackingField`

- `String <campName>k__BackingField`

- `String <campNameExtra>k__BackingField`

- `String <campFeature>k__BackingField`

- `Boolean <encountering>k__BackingField`


## Properties

- `Int32 forceHp`

- `Int32 forceHpMax`

- `String forceId`

- `String campIconId`

- `String campCharId`

- `String campName`

- `String campNameExtra`

- `String campFeature`

- `Boolean encountering`


## Methods

- `Int32 get_forceHp()`

- `Void set_forceHp(Int32)`

- `Int32 get_forceHpMax()`

- `Void set_forceHpMax(Int32)`

- `String get_forceId()`

- `Void set_forceId(String)`

- `String get_campIconId()`

- `Void set_campIconId(String)`

- `String get_campCharId()`

- `Void set_campCharId(String)`

- `String get_campName()`

- `Void set_campName(String)`

- `String get_campNameExtra()`

- `Void set_campNameExtra(String)`

- `String get_campFeature()`

- `Void set_campFeature(String)`

- `Boolean get_encountering()`

- `Void set_encountering(Boolean)`

- `Void LoadData(ActivityAutoChessVerify1Data, AutoChessGame, String, AutoChessForce, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampEnemyItemViewModel : IHotfixable
{
	private List`1 m_tempBuffs; // 0x10
	private List`1 m_permBuffs; // 0x18
	private Int32 <forceHp>k__BackingField; // 0x20
	private Int32 <forceHpMax>k__BackingField; // 0x24
	private String <forceId>k__BackingField; // 0x28
	private String <campIconId>k__BackingField; // 0x30
	private String <campCharId>k__BackingField; // 0x38
	private String <campName>k__BackingField; // 0x40
	private String <campNameExtra>k__BackingField; // 0x48
	private String <campFeature>k__BackingField; // 0x50
	private Boolean <encountering>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_forceHp; // 0x0
	private static DelegateBridge __Hotfix0_set_forceHp; // 0x8
	private static DelegateBridge __Hotfix0_get_forceHpMax; // 0x10
	private static DelegateBridge __Hotfix0_set_forceHpMax; // 0x18
	private static DelegateBridge __Hotfix0_get_forceId; // 0x20
	private static DelegateBridge __Hotfix0_set_forceId; // 0x28
	private static DelegateBridge __Hotfix0_get_campIconId; // 0x30
	private static DelegateBridge __Hotfix0_set_campIconId; // 0x38
	private static DelegateBridge __Hotfix0_get_campCharId; // 0x40
	private static DelegateBridge __Hotfix0_set_campCharId; // 0x48
	private static DelegateBridge __Hotfix0_get_campName; // 0x50
	private static DelegateBridge __Hotfix0_set_campName; // 0x58
	private static DelegateBridge __Hotfix0_get_campNameExtra; // 0x60
	private static DelegateBridge __Hotfix0_set_campNameExtra; // 0x68
	private static DelegateBridge __Hotfix0_get_campFeature; // 0x70
	private static DelegateBridge __Hotfix0_set_campFeature; // 0x78
	private static DelegateBridge __Hotfix0_get_tempBuffs; // 0x80
	private static DelegateBridge __Hotfix0_get_permBuffs; // 0x88
	private static DelegateBridge __Hotfix0_get_encountering; // 0x90
	private static DelegateBridge __Hotfix0_set_encountering; // 0x98
	private static DelegateBridge __Hotfix0_LoadData; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Int32 forceHp { get; set; }
	public Int32 forceHpMax { get; set; }
	public String forceId { get; set; }
	public String campIconId { get; set; }
	public String campCharId { get; set; }
	public String campName { get; set; }
	public String campNameExtra { get; set; }
	public String campFeature { get; set; }
	public List`1 tempBuffs { get; }
	public List`1 permBuffs { get; }
	public Boolean encountering { get; set; }

	// RVA: 0x336d40c VA: 0x759598540c
	public Int32 get_forceHp() { }
	// RVA: 0x336d474 VA: 0x7595985474
	private Void set_forceHp(Int32 value) { }
	// RVA: 0x336d4f0 VA: 0x75959854f0
	public Int32 get_forceHpMax() { }
	// RVA: 0x336d558 VA: 0x7595985558
	private Void set_forceHpMax(Int32 value) { }
	// RVA: 0x336d3a4 VA: 0x75959853a4
	public String get_forceId() { }
	// RVA: 0x336d5d4 VA: 0x75959855d4
	private Void set_forceId(String value) { }
	// RVA: 0x3367500 VA: 0x759597f500
	public String get_campIconId() { }
	// RVA: 0x336d658 VA: 0x7595985658
	private Void set_campIconId(String value) { }
	// RVA: 0x3367568 VA: 0x759597f568
	public String get_campCharId() { }
	// RVA: 0x336d6dc VA: 0x75959856dc
	private Void set_campCharId(String value) { }
	// RVA: 0x33675d0 VA: 0x759597f5d0
	public String get_campName() { }
	// RVA: 0x336d760 VA: 0x7595985760
	private Void set_campName(String value) { }
	// RVA: 0x3367638 VA: 0x759597f638
	public String get_campNameExtra() { }
	// RVA: 0x336d7e4 VA: 0x75959857e4
	private Void set_campNameExtra(String value) { }
	// RVA: 0x33676a0 VA: 0x759597f6a0
	public String get_campFeature() { }
	// RVA: 0x336d868 VA: 0x7595985868
	private Void set_campFeature(String value) { }
	// RVA: 0x3367708 VA: 0x759597f708
	public List`1 get_tempBuffs() { }
	// RVA: 0x33677f4 VA: 0x759597f7f4
	public List`1 get_permBuffs() { }
	// RVA: 0x3367498 VA: 0x759597f498
	public Boolean get_encountering() { }
	// RVA: 0x336d8ec VA: 0x75959858ec
	private Void set_encountering(Boolean value) { }
	// RVA: 0x336cdd8 VA: 0x7595984dd8
	public Void LoadData(ActivityAutoChessVerify1Data gameData, AutoChessGame playerData, String modeId, AutoChessForce force, Boolean isEncountering) { }
	// RVA: 0x336cce0 VA: 0x7595984ce0
	public Void .ctor() { }
}
```