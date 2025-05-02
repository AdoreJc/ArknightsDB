# UniEquipSelectViewModel

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `String uniEquipId`

- `UniEquipData data`

- `CharacterData cachedCharData`

- `String subProfessionId`

- `Boolean isSelect`

- `Boolean isFocus`

- `Boolean isUnlock`

- `PlayerCharacter cachePlayerChar`

- `Int32 equipLevel`

- `Boolean isUnlockAvailable`

- `Boolean isLevelUpValid`

- `Boolean isAddOrOverrideTalent`

- `Boolean isSubProfessionChanged`

- `Boolean isAttrbuteChanged`

- `Boolean isLevelUpEnough`

- `EquipAvgSortType <avgSortType>k__BackingField`


## Properties

- `EquipAvgSortType avgSortType`


## Methods

- `EquipAvgSortType get_avgSortType()`

- `Void set_avgSortType(EquipAvgSortType)`

- `Int32 CompareTo(UniEquipSelectViewModel)`

- `Void InitPlayerData(PlayerCharacter, CharacterData)`

- `Void TryRefreshSelectStateIfHasInitSelectId(PlayerCharacter, String)`

- `EquipAvgSortType _GetEquipAvgSortType()`

- `Void _CheckEquipAddOrOverrideTalent()`

- `Void _CheckSubProfession(PlayerCharacter, CharacterData, UniEquipData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipSelectViewModel : IHotfixable, IComparable`1
{
	public String uniEquipId; // 0x10
	public UniEquipData data; // 0x18
	public CharacterData cachedCharData; // 0x20
	public String subProfessionId; // 0x28
	public Boolean isSelect; // 0x30
	public Boolean isFocus; // 0x31
	public Boolean isUnlock; // 0x32
	public List`1 uniEquipMissionList; // 0x38
	public PlayerCharacter cachePlayerChar; // 0x40
	public Int32 equipLevel; // 0x48
	public Boolean isUnlockAvailable; // 0x4c
	public Boolean isLevelUpValid; // 0x4d
	public Boolean isAddOrOverrideTalent; // 0x4e
	public Boolean isSubProfessionChanged; // 0x4f
	public Boolean isAttrbuteChanged; // 0x50
	public Boolean isLevelUpEnough; // 0x51
	private EquipAvgSortType <avgSortType>k__BackingField; // 0x54
	private static DelegateBridge __Hotfix0_get_avgSortType; // 0x0
	private static DelegateBridge __Hotfix0_set_avgSortType; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge __Hotfix0_InitPlayerData; // 0x18
	private static DelegateBridge __Hotfix0_TryRefreshSelectStateIfHasInitSelectId; // 0x20
	private static DelegateBridge __Hotfix0__GetEquipAvgSortType; // 0x28
	private static DelegateBridge __Hotfix0__CheckEquipAddOrOverrideTalent; // 0x30
	private static DelegateBridge __Hotfix0__CheckSubProfession; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public EquipAvgSortType avgSortType { get; set; }

	// RVA: 0x230b744 VA: 0x7594923744
	public EquipAvgSortType get_avgSortType() { }
	// RVA: 0x230b7ac VA: 0x75949237ac
	private Void set_avgSortType(EquipAvgSortType value) { }
	// RVA: 0x230b828 VA: 0x7594923828
	public Int32 CompareTo(UniEquipSelectViewModel other) { }
	// RVA: 0x230b8d8 VA: 0x75949238d8
	public Void InitPlayerData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x230c25c VA: 0x759492425c
	public Void TryRefreshSelectStateIfHasInitSelectId(PlayerCharacter playerChar, String initSelectId) { }
	// RVA: 0x230bdc8 VA: 0x7594923dc8
	private EquipAvgSortType _GetEquipAvgSortType() { }
	// RVA: 0x230bfb0 VA: 0x7594923fb0
	private Void _CheckEquipAddOrOverrideTalent() { }
	// RVA: 0x230be68 VA: 0x7594923e68
	private Void _CheckSubProfession(PlayerCharacter playerChar, CharacterData charData, UniEquipData uniEquipData) { }
	// RVA: 0x230c304 VA: 0x7594924304
	public Void .ctor() { }
}
```