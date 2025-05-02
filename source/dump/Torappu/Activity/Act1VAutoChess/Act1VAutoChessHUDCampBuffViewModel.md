# Act1VAutoChessHUDCampBuffViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String m_effectId`

- `Act1VAutoChessEffectType <type>k__BackingField`

- `String <buffName>k__BackingField`

- `String <buffDesc>k__BackingField`

- `String <buffTypeDesc>k__BackingField`

- `String <buffDecoIconId>k__BackingField`

- `Boolean <isMainEnemyBuff>k__BackingField`

- `Int64 <ts>k__BackingField`


## Properties

- `Act1VAutoChessEffectType type`

- `String buffName`

- `String buffDesc`

- `String buffTypeDesc`

- `String buffDecoIconId`

- `Boolean isMainEnemyBuff`

- `Int64 ts`

- `String effectId`


## Methods

- `Act1VAutoChessEffectType get_type()`

- `Void set_type(Act1VAutoChessEffectType)`

- `String get_buffName()`

- `Void set_buffName(String)`

- `String get_buffDesc()`

- `Void set_buffDesc(String)`

- `String get_buffTypeDesc()`

- `Void set_buffTypeDesc(String)`

- `String get_buffDecoIconId()`

- `Void set_buffDecoIconId(String)`

- `Boolean get_isMainEnemyBuff()`

- `Void set_isMainEnemyBuff(Boolean)`

- `Int64 get_ts()`

- `Void set_ts(Int64)`

- `String get_effectId()`

- `Void LoadData(ActivityAutoChessVerify1Data, AutoChessGame, Act1VAutoChessEffectInfoData, String)`

- `Void LoadData(ActivityAutoChessVerify1Data, AutoChessGame, Act1VAutoChessEffectInfoData, Int32, Int64)`

- `Int32 CompareTo(Act1VAutoChessHUDCampBuffViewModel)`

- `String _FormatDescString(ActivityAutoChessVerify1Data, AutoChessGame, Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampBuffViewModel : IHotfixable, IComparable`1
{
	private const String EFFECT_TRACKER_FORMAT; // 0x0
	private String m_effectId; // 0x10
	private Act1VAutoChessEffectType <type>k__BackingField; // 0x18
	private String <buffName>k__BackingField; // 0x20
	private String <buffDesc>k__BackingField; // 0x28
	private String <buffTypeDesc>k__BackingField; // 0x30
	private String <buffDecoIconId>k__BackingField; // 0x38
	private Boolean <isMainEnemyBuff>k__BackingField; // 0x40
	private Int64 <ts>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_set_type; // 0x8
	private static DelegateBridge __Hotfix0_get_buffName; // 0x10
	private static DelegateBridge __Hotfix0_set_buffName; // 0x18
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x20
	private static DelegateBridge __Hotfix0_set_buffDesc; // 0x28
	private static DelegateBridge __Hotfix0_get_buffTypeDesc; // 0x30
	private static DelegateBridge __Hotfix0_set_buffTypeDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_buffDecoIconId; // 0x40
	private static DelegateBridge __Hotfix0_set_buffDecoIconId; // 0x48
	private static DelegateBridge __Hotfix0_get_isMainEnemyBuff; // 0x50
	private static DelegateBridge __Hotfix0_set_isMainEnemyBuff; // 0x58
	private static DelegateBridge __Hotfix0_get_ts; // 0x60
	private static DelegateBridge __Hotfix0_set_ts; // 0x68
	private static DelegateBridge __Hotfix0_get_effectId; // 0x70
	private static DelegateBridge __Hotfix0_LoadData; // 0x78
	private static DelegateBridge __Hotfix1_LoadData; // 0x80
	private static DelegateBridge __Hotfix0_CompareTo; // 0x88
	private static DelegateBridge __Hotfix0__FormatDescString; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Act1VAutoChessEffectType type { get; set; }
	public String buffName { get; set; }
	public String buffDesc { get; set; }
	public String buffTypeDesc { get; set; }
	public String buffDecoIconId { get; set; }
	public Boolean isMainEnemyBuff { get; set; }
	public Int64 ts { get; set; }
	public String effectId { get; }

	// RVA: 0x336d96c VA: 0x759598596c
	public Act1VAutoChessEffectType get_type() { }
	// RVA: 0x336d9d4 VA: 0x75959859d4
	private Void set_type(Act1VAutoChessEffectType value) { }
	// RVA: 0x3365e88 VA: 0x759597de88
	public String get_buffName() { }
	// RVA: 0x336da50 VA: 0x7595985a50
	private Void set_buffName(String value) { }
	// RVA: 0x3365ef0 VA: 0x759597def0
	public String get_buffDesc() { }
	// RVA: 0x336dad4 VA: 0x7595985ad4
	private Void set_buffDesc(String value) { }
	// RVA: 0x3365f58 VA: 0x759597df58
	public String get_buffTypeDesc() { }
	// RVA: 0x336db58 VA: 0x7595985b58
	private Void set_buffTypeDesc(String value) { }
	// RVA: 0x3365fc0 VA: 0x759597dfc0
	public String get_buffDecoIconId() { }
	// RVA: 0x336dbdc VA: 0x7595985bdc
	private Void set_buffDecoIconId(String value) { }
	// RVA: 0x33668b4 VA: 0x759597e8b4
	public Boolean get_isMainEnemyBuff() { }
	// RVA: 0x336dc60 VA: 0x7595985c60
	private Void set_isMainEnemyBuff(Boolean value) { }
	// RVA: 0x336dce0 VA: 0x7595985ce0
	public Int64 get_ts() { }
	// RVA: 0x336dd48 VA: 0x7595985d48
	private Void set_ts(Int64 value) { }
	// RVA: 0x336c4d4 VA: 0x75959844d4
	public String get_effectId() { }
	// RVA: 0x336c3a8 VA: 0x75959843a8
	public Void LoadData(ActivityAutoChessVerify1Data gameData, AutoChessGame game, Act1VAutoChessEffectInfoData data, String typeDesc) { }
	// RVA: 0x336c25c VA: 0x759598425c
	public Void LoadData(ActivityAutoChessVerify1Data gameData, AutoChessGame game, Act1VAutoChessEffectInfoData data, Int32 instId, Int64 timeStamp) { }
	// RVA: 0x336df1c VA: 0x7595985f1c
	public Int32 CompareTo(Act1VAutoChessHUDCampBuffViewModel other) { }
	// RVA: 0x336ddc4 VA: 0x7595985dc4
	private String _FormatDescString(ActivityAutoChessVerify1Data gameData, AutoChessGame game, Int32 instId, String desc) { }
	// RVA: 0x336c1ec VA: 0x75959841ec
	public Void .ctor() { }
}
```