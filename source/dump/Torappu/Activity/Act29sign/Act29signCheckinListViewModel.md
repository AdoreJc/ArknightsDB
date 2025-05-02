# Act29signCheckinListViewModel

**Namespace:** `Torappu.Activity.Act29sign`


## Fields

- `String specialApItemTimeStr`

- `String openTimeStr`

- `String activityId`

- `PlayerCheckinOnlyTypeActivity playerInfo`

- `String moonCakeSpriteId`

- `String furnitureSpriteId`

- `Int32 focusItemIndex`

- `ItemConfigGroup m_normalItemConfigGroup`

- `Color m_specialItemNumColor`

- `Color m_specialItemProgressTextColor`


## Methods

- `Void set_LoadSpriteFromAutoPackHub(Func`3)`

- `Void LoadStaticData(ActivityCommonCheckinViewModel, ItemConfigGroup, Color, Color)`

- `Void LoadDynamicData(ActivityCommonCheckinViewModel)`

- `Sprite _LoadSpriteForCurrentAct(String)`

- `Void _GenerateSpecialItemIndexSet()`

- `Void _GetSpecialApTime(ActivityCommonCheckinViewModel)`

- `Void _LoadDynamicSpriteId()`

- `Void _CalculateFocusItem()`

- `Void _GenerateCheckinItemViewModels()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign
public class Act29signCheckinListViewModel : IHotfixable
{
	public Dictionary`2 normalCheckinDict; // 0x10
	public String specialApItemTimeStr; // 0x18
	public String openTimeStr; // 0x20
	public String activityId; // 0x28
	public PlayerCheckinOnlyTypeActivity playerInfo; // 0x30
	public String moonCakeSpriteId; // 0x38
	public String furnitureSpriteId; // 0x40
	public Int32 focusItemIndex; // 0x48
	private ItemConfigGroup m_normalItemConfigGroup; // 0x50
	private Dictionary`2 m_dynOptionRewardItemDict; // 0xd8
	private Dictionary`2 m_dynCheckInDict; // 0xe0
	private Dictionary`2 dynOptionInfoDict; // 0xe8
	private HashSet`1 m_specialItemIndices; // 0xf0
	private Color m_specialItemNumColor; // 0xf8
	private Color m_specialItemProgressTextColor; // 0x108
	private List`1 m_checkinItemViewModels; // 0x118
	private Func`3 <LoadSpriteFromAutoPackHub>k__BackingField; // 0x120
	private static DelegateBridge __Hotfix0_get_checkinItemViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_LoadSpriteFromAutoPackHub; // 0x8
	private static DelegateBridge __Hotfix0_set_LoadSpriteFromAutoPackHub; // 0x10
	private static DelegateBridge __Hotfix0_LoadStaticData; // 0x18
	private static DelegateBridge __Hotfix0_LoadDynamicData; // 0x20
	private static DelegateBridge __Hotfix0__LoadSpriteForCurrentAct; // 0x28
	private static DelegateBridge __Hotfix0__GenerateSpecialItemIndexSet; // 0x30
	private static DelegateBridge __Hotfix0__GetSpecialApTime; // 0x38
	private static DelegateBridge __Hotfix0__LoadDynamicSpriteId; // 0x40
	private static DelegateBridge __Hotfix0__CalculateFocusItem; // 0x48
	private static DelegateBridge __Hotfix0__GenerateCheckinItemViewModels; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public List`1 checkinItemViewModels { get; }
	private Func`3 LoadSpriteFromAutoPackHub { get; set; }

	// RVA: 0x3258bb4 VA: 0x7595870bb4
	public List`1 get_checkinItemViewModels() { }
	// RVA: 0x3258c1c VA: 0x7595870c1c
	private Func`3 get_LoadSpriteFromAutoPackHub() { }
	// RVA: 0x3258c84 VA: 0x7595870c84
	public Void set_LoadSpriteFromAutoPackHub(Func`3 value) { }
	// RVA: 0x3258d08 VA: 0x7595870d08
	public Void LoadStaticData(ActivityCommonCheckinViewModel outerViewModel, ItemConfigGroup normalItemConfigGroup, Color specialItemNumColor, Color specialItemProgressTextColor) { }
	// RVA: 0x3259534 VA: 0x7595871534
	public Void LoadDynamicData(ActivityCommonCheckinViewModel outerViewModel) { }
	// RVA: 0x3259c6c VA: 0x7595871c6c
	private Sprite _LoadSpriteForCurrentAct(String spriteId) { }
	// RVA: 0x3258ee8 VA: 0x7595870ee8
	private Void _GenerateSpecialItemIndexSet() { }
	// RVA: 0x3259170 VA: 0x7595871170
	private Void _GetSpecialApTime(ActivityCommonCheckinViewModel outerViewModel) { }
	// RVA: 0x32599b8 VA: 0x75958719b8
	private Void _LoadDynamicSpriteId() { }
	// RVA: 0x3259b50 VA: 0x7595871b50
	private Void _CalculateFocusItem() { }
	// RVA: 0x32595f4 VA: 0x75958715f4
	private Void _GenerateCheckinItemViewModels() { }
	// RVA: 0x3259d38 VA: 0x7595871d38
	public Void .ctor() { }
}
```