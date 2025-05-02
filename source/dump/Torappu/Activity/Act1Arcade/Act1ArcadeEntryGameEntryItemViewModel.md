# Act1ArcadeEntryGameEntryItemViewModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `ArcadeZoneAdditionalData m_zoneData`

- `ArcadeConstData m_constData`

- `String <lockHint>k__BackingField`

- `Int32 <score>k__BackingField`

- `LockState <lockState>k__BackingField`

- `Boolean <hasNew>k__BackingField`


## Properties

- `String zoneId`

- `String zoneName`

- `String lockToast`

- `String endToast`

- `String lockHint`

- `String endHint`

- `Int32 score`

- `LockState lockState`

- `Boolean hasNew`


## Methods

- `String get_zoneId()`

- `String get_zoneName()`

- `String get_lockToast()`

- `String get_endToast()`

- `String get_lockHint()`

- `Void set_lockHint(String)`

- `String get_endHint()`

- `Int32 get_score()`

- `Void set_score(Int32)`

- `LockState get_lockState()`

- `Void set_lockState(LockState)`

- `Boolean get_hasNew()`

- `Void set_hasNew(Boolean)`

- `Void LoadData(String, ArcadeConstData, ArcadeZoneAdditionalData, PlayerArcadeActivity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryGameEntryItemViewModel : IHotfixable
{
	private ArcadeZoneAdditionalData m_zoneData; // 0x10
	private ArcadeConstData m_constData; // 0x18
	private String <lockHint>k__BackingField; // 0x20
	private Int32 <score>k__BackingField; // 0x28
	private LockState <lockState>k__BackingField; // 0x2c
	private Boolean <hasNew>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x0
	private static DelegateBridge __Hotfix0_get_zoneName; // 0x8
	private static DelegateBridge __Hotfix0_get_lockToast; // 0x10
	private static DelegateBridge __Hotfix0_get_endToast; // 0x18
	private static DelegateBridge __Hotfix0_get_lockHint; // 0x20
	private static DelegateBridge __Hotfix0_set_lockHint; // 0x28
	private static DelegateBridge __Hotfix0_get_endHint; // 0x30
	private static DelegateBridge __Hotfix0_get_score; // 0x38
	private static DelegateBridge __Hotfix0_set_score; // 0x40
	private static DelegateBridge __Hotfix0_get_lockState; // 0x48
	private static DelegateBridge __Hotfix0_set_lockState; // 0x50
	private static DelegateBridge __Hotfix0_get_hasNew; // 0x58
	private static DelegateBridge __Hotfix0_set_hasNew; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String zoneId { get; }
	public String zoneName { get; }
	public String lockToast { get; }
	public String endToast { get; }
	public String lockHint { get; set; }
	public String endHint { get; }
	public Int32 score { get; set; }
	public LockState lockState { get; set; }
	public Boolean hasNew { get; set; }

	// RVA: 0x33fedd0 VA: 0x7595a16dd0
	public String get_zoneId() { }
	// RVA: 0x33fe968 VA: 0x7595a16968
	public String get_zoneName() { }
	// RVA: 0x33fece8 VA: 0x7595a16ce8
	public String get_lockToast() { }
	// RVA: 0x33fed5c VA: 0x7595a16d5c
	public String get_endToast() { }
	// RVA: 0x33fe9dc VA: 0x7595a169dc
	public String get_lockHint() { }
	// RVA: 0x3400e00 VA: 0x7595a18e00
	private Void set_lockHint(String value) { }
	// RVA: 0x33fea44 VA: 0x7595a16a44
	public String get_endHint() { }
	// RVA: 0x33fe900 VA: 0x7595a16900
	public Int32 get_score() { }
	// RVA: 0x3400e84 VA: 0x7595a18e84
	private Void set_score(Int32 value) { }
	// RVA: 0x33feab8 VA: 0x7595a16ab8
	public LockState get_lockState() { }
	// RVA: 0x3400f00 VA: 0x7595a18f00
	private Void set_lockState(LockState value) { }
	// RVA: 0x33feb20 VA: 0x7595a16b20
	public Boolean get_hasNew() { }
	// RVA: 0x3400f7c VA: 0x7595a18f7c
	private Void set_hasNew(Boolean value) { }
	// RVA: 0x3400bfc VA: 0x7595a18bfc
	public Void LoadData(String actId, ArcadeConstData constData, ArcadeZoneAdditionalData zoneData, PlayerArcadeActivity playerData) { }
	// RVA: 0x3400b8c VA: 0x7595a18b8c
	public Void .ctor() { }
}
```