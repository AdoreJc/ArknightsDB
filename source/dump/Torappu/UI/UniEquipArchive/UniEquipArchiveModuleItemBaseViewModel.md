# UniEquipArchiveModuleItemBaseViewModel

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `String <uniEquipId>k__BackingField`

- `String <uniEquipName>k__BackingField`

- `Boolean <isLocked>k__BackingField`

- `String <uniEquipType>k__BackingField`

- `Int32 <uniEquipTypeSortId>k__BackingField`

- `Int32 <uniEquipLevel>k__BackingField`

- `Boolean <isLevelUpValid>k__BackingField`

- `Boolean <isLevelMax>k__BackingField`

- `Int64 <startGetTime>k__BackingField`

- `ModuleCollectionItemUnlockState <collectionItemUnlockState>k__BackingField`

- `Boolean <hasMissions>k__BackingField`

- `UniEquipData m_cachedUniEquipData`

- `String m_tmplId`


## Properties

- `String uniEquipId`

- `String uniEquipName`

- `Boolean isLocked`

- `String uniEquipType`

- `Int32 uniEquipTypeSortId`

- `Int32 uniEquipLevel`

- `Boolean isLevelUpValid`

- `Boolean isLevelMax`

- `Int64 startGetTime`

- `ModuleCollectionItemUnlockState collectionItemUnlockState`

- `Boolean hasMissions`


## Methods

- `String get_uniEquipId()`

- `Void set_uniEquipId(String)`

- `String get_uniEquipName()`

- `Void set_uniEquipName(String)`

- `Boolean get_isLocked()`

- `Void set_isLocked(Boolean)`

- `String get_uniEquipType()`

- `Void set_uniEquipType(String)`

- `Int32 get_uniEquipTypeSortId()`

- `Void set_uniEquipTypeSortId(Int32)`

- `Int32 get_uniEquipLevel()`

- `Void set_uniEquipLevel(Int32)`

- `Boolean get_isLevelUpValid()`

- `Void set_isLevelUpValid(Boolean)`

- `Boolean get_isLevelMax()`

- `Void set_isLevelMax(Boolean)`

- `Int64 get_startGetTime()`

- `Void set_startGetTime(Int64)`

- `ModuleCollectionItemUnlockState get_collectionItemUnlockState()`

- `Void set_collectionItemUnlockState(ModuleCollectionItemUnlockState)`

- `Boolean get_hasMissions()`

- `Void set_hasMissions(Boolean)`

- `Void LoadData(UniEquipData)`

- `Void RefreshData(PlayerCharacter)`

- `ModuleCollectionItemUnlockState _GetLockedItemState(PlayerCharacter)`

- `UniEquipTypeInfo _GetTypeInfo(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleItemBaseViewModel : IHotfixable
{
	private String <uniEquipId>k__BackingField; // 0x10
	private String <uniEquipName>k__BackingField; // 0x18
	private Boolean <isLocked>k__BackingField; // 0x20
	private String <uniEquipType>k__BackingField; // 0x28
	private Int32 <uniEquipTypeSortId>k__BackingField; // 0x30
	private Int32 <uniEquipLevel>k__BackingField; // 0x34
	private Boolean <isLevelUpValid>k__BackingField; // 0x38
	private Boolean <isLevelMax>k__BackingField; // 0x39
	private Int64 <startGetTime>k__BackingField; // 0x40
	private ModuleCollectionItemUnlockState <collectionItemUnlockState>k__BackingField; // 0x48
	private Boolean <hasMissions>k__BackingField; // 0x4c
	private UniEquipData m_cachedUniEquipData; // 0x50
	private String m_tmplId; // 0x58
	private static DelegateBridge __Hotfix0_get_uniEquipId; // 0x0
	private static DelegateBridge __Hotfix0_set_uniEquipId; // 0x8
	private static DelegateBridge __Hotfix0_get_uniEquipName; // 0x10
	private static DelegateBridge __Hotfix0_set_uniEquipName; // 0x18
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x20
	private static DelegateBridge __Hotfix0_set_isLocked; // 0x28
	private static DelegateBridge __Hotfix0_get_uniEquipType; // 0x30
	private static DelegateBridge __Hotfix0_set_uniEquipType; // 0x38
	private static DelegateBridge __Hotfix0_get_uniEquipTypeSortId; // 0x40
	private static DelegateBridge __Hotfix0_set_uniEquipTypeSortId; // 0x48
	private static DelegateBridge __Hotfix0_get_uniEquipLevel; // 0x50
	private static DelegateBridge __Hotfix0_set_uniEquipLevel; // 0x58
	private static DelegateBridge __Hotfix0_get_isLevelUpValid; // 0x60
	private static DelegateBridge __Hotfix0_set_isLevelUpValid; // 0x68
	private static DelegateBridge __Hotfix0_get_isLevelMax; // 0x70
	private static DelegateBridge __Hotfix0_set_isLevelMax; // 0x78
	private static DelegateBridge __Hotfix0_get_startGetTime; // 0x80
	private static DelegateBridge __Hotfix0_set_startGetTime; // 0x88
	private static DelegateBridge __Hotfix0_get_collectionItemUnlockState; // 0x90
	private static DelegateBridge __Hotfix0_set_collectionItemUnlockState; // 0x98
	private static DelegateBridge __Hotfix0_get_hasMissions; // 0xa0
	private static DelegateBridge __Hotfix0_set_hasMissions; // 0xa8
	private static DelegateBridge __Hotfix0_LoadData; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshData; // 0xb8
	private static DelegateBridge __Hotfix0__GetLockedItemState; // 0xc0
	private static DelegateBridge __Hotfix0__GetTypeInfo; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public String uniEquipId { get; set; }
	public String uniEquipName { get; set; }
	public Boolean isLocked { get; set; }
	public String uniEquipType { get; set; }
	public Int32 uniEquipTypeSortId { get; set; }
	public Int32 uniEquipLevel { get; set; }
	public Boolean isLevelUpValid { get; set; }
	public Boolean isLevelMax { get; set; }
	public Int64 startGetTime { get; set; }
	public ModuleCollectionItemUnlockState collectionItemUnlockState { get; set; }
	public Boolean hasMissions { get; set; }

	// RVA: 0x22f7d34 VA: 0x759490fd34
	public String get_uniEquipId() { }
	// RVA: 0x22f7d9c VA: 0x759490fd9c
	private Void set_uniEquipId(String value) { }
	// RVA: 0x22f0acc VA: 0x7594908acc
	public String get_uniEquipName() { }
	// RVA: 0x22f7e20 VA: 0x759490fe20
	private Void set_uniEquipName(String value) { }
	// RVA: 0x22f7a68 VA: 0x759490fa68
	public Boolean get_isLocked() { }
	// RVA: 0x22f7ea4 VA: 0x759490fea4
	private Void set_isLocked(Boolean value) { }
	// RVA: 0x22f7ad0 VA: 0x759490fad0
	public String get_uniEquipType() { }
	// RVA: 0x22f7f24 VA: 0x759490ff24
	private Void set_uniEquipType(String value) { }
	// RVA: 0x22f7fa8 VA: 0x759490ffa8
	public Int32 get_uniEquipTypeSortId() { }
	// RVA: 0x22f8010 VA: 0x7594910010
	private Void set_uniEquipTypeSortId(Int32 value) { }
	// RVA: 0x22f0f6c VA: 0x7594908f6c
	public Int32 get_uniEquipLevel() { }
	// RVA: 0x22f808c VA: 0x759491008c
	private Void set_uniEquipLevel(Int32 value) { }
	// RVA: 0x22f0f04 VA: 0x7594908f04
	public Boolean get_isLevelUpValid() { }
	// RVA: 0x22f8108 VA: 0x7594910108
	private Void set_isLevelUpValid(Boolean value) { }
	// RVA: 0x22f0e9c VA: 0x7594908e9c
	public Boolean get_isLevelMax() { }
	// RVA: 0x22f8188 VA: 0x7594910188
	private Void set_isLevelMax(Boolean value) { }
	// RVA: 0x22f8208 VA: 0x7594910208
	public Int64 get_startGetTime() { }
	// RVA: 0x22f8270 VA: 0x7594910270
	private Void set_startGetTime(Int64 value) { }
	// RVA: 0x22f0dcc VA: 0x7594908dcc
	public ModuleCollectionItemUnlockState get_collectionItemUnlockState() { }
	// RVA: 0x22f82ec VA: 0x75949102ec
	private Void set_collectionItemUnlockState(ModuleCollectionItemUnlockState value) { }
	// RVA: 0x22f0e34 VA: 0x7594908e34
	public Boolean get_hasMissions() { }
	// RVA: 0x22f8368 VA: 0x7594910368
	private Void set_hasMissions(Boolean value) { }
	// RVA: 0x22f83e8 VA: 0x75949103e8
	public Void LoadData(UniEquipData equipData) { }
	// RVA: 0x22f8654 VA: 0x7594910654
	public Void RefreshData(PlayerCharacter playerChar) { }
	// RVA: 0x22f88d8 VA: 0x75949108d8
	private ModuleCollectionItemUnlockState _GetLockedItemState(PlayerCharacter playerChar) { }
	// RVA: 0x22f851c VA: 0x759491051c
	private UniEquipTypeInfo _GetTypeInfo(String uniEquipTypeName2) { }
	// RVA: 0x22f8bd0 VA: 0x7594910bd0
	public Void .ctor() { }
}
```