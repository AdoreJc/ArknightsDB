# Act1VAutoChessHUDCampSelfViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Int64 m_latestTs`

- `String <campIconId>k__BackingField`

- `String <campCharId>k__BackingField`

- `String <campName>k__BackingField`

- `String <campNameExtra>k__BackingField`

- `String <campFeature>k__BackingField`

- `Boolean <hasOptions>k__BackingField`

- `Int32 <selectedIndex>k__BackingField`

- `Int32 <updatedBuffIndex>k__BackingField`


## Properties

- `String campIconId`

- `String campCharId`

- `String campName`

- `String campNameExtra`

- `String campFeature`

- `Boolean hasOptions`

- `Int32 selectedIndex`

- `Int32 updatedBuffIndex`


## Methods

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

- `Boolean get_hasOptions()`

- `Void set_hasOptions(Boolean)`

- `Int32 get_selectedIndex()`

- `Void set_selectedIndex(Int32)`

- `Int32 get_updatedBuffIndex()`

- `Void set_updatedBuffIndex(Int32)`

- `Void LoadData(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Boolean RefreshData(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Void SelectTalentIndex(Int32)`

- `Void _LoadBuffs(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Void _LoadOptions(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Boolean _RefreshBuffs(ActivityAutoChessVerify1Data, AutoChessGame)`

- `Void _UpdateCampFeature(ActivityAutoChessVerify1Data, AutoChessGame, String, Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampSelfViewModel : IHotfixable
{
	private const String FEATURE_EFEECT_COUNTER_ONLY_FORMAT; // 0x0
	private readonly List`1 m_buffs; // 0x10
	private readonly List`1 m_options; // 0x18
	private Int64 m_latestTs; // 0x20
	private Dictionary`2 m_cachedEffectInfoDict; // 0x28
	private Dictionary`2 m_cachedEffectTypeDescriptionDict; // 0x30
	private String <campIconId>k__BackingField; // 0x38
	private String <campCharId>k__BackingField; // 0x40
	private String <campName>k__BackingField; // 0x48
	private String <campNameExtra>k__BackingField; // 0x50
	private String <campFeature>k__BackingField; // 0x58
	private Boolean <hasOptions>k__BackingField; // 0x60
	private Int32 <selectedIndex>k__BackingField; // 0x64
	private Int32 <updatedBuffIndex>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_campIconId; // 0x0
	private static DelegateBridge __Hotfix0_set_campIconId; // 0x8
	private static DelegateBridge __Hotfix0_get_campCharId; // 0x10
	private static DelegateBridge __Hotfix0_set_campCharId; // 0x18
	private static DelegateBridge __Hotfix0_get_campName; // 0x20
	private static DelegateBridge __Hotfix0_set_campName; // 0x28
	private static DelegateBridge __Hotfix0_get_campNameExtra; // 0x30
	private static DelegateBridge __Hotfix0_set_campNameExtra; // 0x38
	private static DelegateBridge __Hotfix0_get_campFeature; // 0x40
	private static DelegateBridge __Hotfix0_set_campFeature; // 0x48
	private static DelegateBridge __Hotfix0_get_hasOptions; // 0x50
	private static DelegateBridge __Hotfix0_set_hasOptions; // 0x58
	private static DelegateBridge __Hotfix0_get_buffs; // 0x60
	private static DelegateBridge __Hotfix0_get_options; // 0x68
	private static DelegateBridge __Hotfix0_get_selectedIndex; // 0x70
	private static DelegateBridge __Hotfix0_set_selectedIndex; // 0x78
	private static DelegateBridge __Hotfix0_get_updatedBuffIndex; // 0x80
	private static DelegateBridge __Hotfix0_set_updatedBuffIndex; // 0x88
	private static DelegateBridge __Hotfix0_LoadData; // 0x90
	private static DelegateBridge __Hotfix0_RefreshData; // 0x98
	private static DelegateBridge __Hotfix0_SelectTalentIndex; // 0xa0
	private static DelegateBridge __Hotfix0__LoadBuffs; // 0xa8
	private static DelegateBridge __Hotfix0__LoadOptions; // 0xb0
	private static DelegateBridge __Hotfix0__RefreshBuffs; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateCampFeature; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public String campIconId { get; set; }
	public String campCharId { get; set; }
	public String campName { get; set; }
	public String campNameExtra { get; set; }
	public String campFeature { get; set; }
	public Boolean hasOptions { get; set; }
	public List`1 buffs { get; }
	public List`1 options { get; }
	public Int32 selectedIndex { get; set; }
	public Int32 updatedBuffIndex { get; set; }

	// RVA: 0x3368d5c VA: 0x7595980d5c
	public String get_campIconId() { }
	// RVA: 0x336ade8 VA: 0x7595982de8
	private Void set_campIconId(String value) { }
	// RVA: 0x3368dc4 VA: 0x7595980dc4
	public String get_campCharId() { }
	// RVA: 0x336ae6c VA: 0x7595982e6c
	private Void set_campCharId(String value) { }
	// RVA: 0x3368e2c VA: 0x7595980e2c
	public String get_campName() { }
	// RVA: 0x336aef0 VA: 0x7595982ef0
	private Void set_campName(String value) { }
	// RVA: 0x3368e94 VA: 0x7595980e94
	public String get_campNameExtra() { }
	// RVA: 0x336af74 VA: 0x7595982f74
	private Void set_campNameExtra(String value) { }
	// RVA: 0x3368efc VA: 0x7595980efc
	public String get_campFeature() { }
	// RVA: 0x336aff8 VA: 0x7595982ff8
	private Void set_campFeature(String value) { }
	// RVA: 0x336b07c VA: 0x759598307c
	public Boolean get_hasOptions() { }
	// RVA: 0x336b0e4 VA: 0x75959830e4
	private Void set_hasOptions(Boolean value) { }
	// RVA: 0x3368fcc VA: 0x7595980fcc
	public List`1 get_buffs() { }
	// RVA: 0x3369234 VA: 0x7595981234
	public List`1 get_options() { }
	// RVA: 0x336929c VA: 0x759598129c
	public Int32 get_selectedIndex() { }
	// RVA: 0x336b164 VA: 0x7595983164
	private Void set_selectedIndex(Int32 value) { }
	// RVA: 0x3368f64 VA: 0x7595980f64
	public Int32 get_updatedBuffIndex() { }
	// RVA: 0x336b1e0 VA: 0x75959831e0
	private Void set_updatedBuffIndex(Int32 value) { }
	// RVA: 0x336b25c VA: 0x759598325c
	public Void LoadData(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336b9b4 VA: 0x75959839b4
	public Boolean RefreshData(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336be94 VA: 0x7595983e94
	public Void SelectTalentIndex(Int32 index) { }
	// RVA: 0x336b3fc VA: 0x75959833fc
	private Void _LoadBuffs(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336b6f4 VA: 0x75959836f4
	private Void _LoadOptions(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336ba80 VA: 0x7595983a80
	private Boolean _RefreshBuffs(ActivityAutoChessVerify1Data gameData, AutoChessGame game) { }
	// RVA: 0x336bf50 VA: 0x7595983f50
	private Void _UpdateCampFeature(ActivityAutoChessVerify1Data gameData, AutoChessGame game, String effectId, Int32 instId, String desc) { }
	// RVA: 0x336c53c VA: 0x759598453c
	public Void .ctor() { }
}
```