# HomeSecretarySkinChangeViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int32 maxSelectSkinNum`

- `String presetInstId`

- `String secretarySkinId`

- `Boolean showSelectCharBtn`

- `String m_displaySkinId`

- `FilterType m_skinFilterFlag`


## Properties

- `String displaySkinId`

- `HomeSecretarySkinItemModel displaySkinModel`


## Methods

- `String get_displaySkinId()`

- `HomeSecretarySkinItemModel get_displaySkinModel()`

- `Void LoadData(List`1, List`1, String, Boolean)`

- `Void SelectSkin(String)`

- `Void RemoveSkin(String)`

- `Void CleanAllSelect()`

- `Void SetFilter(FilterType, Boolean)`

- `Boolean GetFilterStatusByType(FilterType)`

- `Void _ClearData()`

- `Void _LoadSkinInfo(List`1)`

- `Void _LoadGameDataConsts()`

- `Void _UpdateSelectedSkinInfo(List`1)`

- `Void _UpdateDisplaySkinInfo()`

- `Void _LoadSecretarySkin(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinChangeViewModel : IHotfixable
{
	public HashSet`1 selectedSkinIds; // 0x10
	public Int32 maxSelectSkinNum; // 0x18
	public String presetInstId; // 0x20
	public List`1 selectedCharIds; // 0x28
	public String secretarySkinId; // 0x30
	public Boolean showSelectCharBtn; // 0x38
	private ListDict`2 m_skinDict; // 0x40
	private List`1 m_playerSelectRecords; // 0x48
	private String m_displaySkinId; // 0x50
	private List`1 m_filterdSkinList; // 0x58
	private FilterType m_skinFilterFlag; // 0x60
	private static DelegateBridge __Hotfix0_get_displaySkinId; // 0x0
	private static DelegateBridge __Hotfix0_get_filterdSkinList; // 0x8
	private static DelegateBridge __Hotfix0_get_displaySkinModel; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_SelectSkin; // 0x20
	private static DelegateBridge __Hotfix0_RemoveSkin; // 0x28
	private static DelegateBridge __Hotfix0_CleanAllSelect; // 0x30
	private static DelegateBridge __Hotfix0_SetFilter; // 0x38
	private static DelegateBridge __Hotfix0_GetFilterStatusByType; // 0x40
	private static DelegateBridge __Hotfix0_GenerateSelectedSlots; // 0x48
	private static DelegateBridge __Hotfix0__ClearData; // 0x50
	private static DelegateBridge __Hotfix0__LoadSkinInfo; // 0x58
	private static DelegateBridge __Hotfix0__LoadGameDataConsts; // 0x60
	private static DelegateBridge __Hotfix0__UpdateSelectedSkinInfo; // 0x68
	private static DelegateBridge __Hotfix0__UpdateDisplaySkinInfo; // 0x70
	private static DelegateBridge __Hotfix0__GenerateFilterdSkinList; // 0x78
	private static DelegateBridge __Hotfix0__LoadSecretarySkin; // 0x80
	private static DelegateBridge __Hotfix0__GetSkinFiltersByType; // 0x88
	private static DelegateBridge __Hotfix0__CheckIfEvolveTwoSkin; // 0x90
	private static DelegateBridge __Hotfix0__CheckIfShopSkin; // 0x98
	private static DelegateBridge __Hotfix0__CheckIfDynSkin; // 0xa0
	private static DelegateBridge __Hotfix0__IsEvolveSkin; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String displaySkinId { get; }
	public List`1 filterdSkinList { get; }
	public HomeSecretarySkinItemModel displaySkinModel { get; }

	// RVA: 0x2816c54 VA: 0x7594e2ec54
	public String get_displaySkinId() { }
	// RVA: 0x2816ee0 VA: 0x7594e2eee0
	public List`1 get_filterdSkinList() { }
	// RVA: 0x28172fc VA: 0x7594e2f2fc
	public HomeSecretarySkinItemModel get_displaySkinModel() { }
	// RVA: 0x2815508 VA: 0x7594e2d508
	public Void LoadData(List`1 charIdList, List`1 selectedSkinIdList, String presetInstId, Boolean showSelectCharBtn) { }
	// RVA: 0x2817c80 VA: 0x7594e2fc80
	public Void SelectSkin(String skinId) { }
	// RVA: 0x2817df8 VA: 0x7594e2fdf8
	public Void RemoveSkin(String skinId) { }
	// RVA: 0x2817f1c VA: 0x7594e2ff1c
	public Void CleanAllSelect() { }
	// RVA: 0x2817fec VA: 0x7594e2ffec
	public Void SetFilter(FilterType type, Boolean flag) { }
	// RVA: 0x28180e0 VA: 0x7594e300e0
	public Boolean GetFilterStatusByType(FilterType type) { }
	// RVA: 0x2818164 VA: 0x7594e30164
	public List`1 GenerateSelectedSlots() { }
	// RVA: 0x28173c4 VA: 0x7594e2f3c4
	private Void _ClearData() { }
	// RVA: 0x28174e4 VA: 0x7594e2f4e4
	private Void _LoadSkinInfo(List`1 charIdList) { }
	// RVA: 0x2817a58 VA: 0x7594e2fa58
	private Void _LoadGameDataConsts() { }
	// RVA: 0x2817ae4 VA: 0x7594e2fae4
	private Void _UpdateSelectedSkinInfo(List`1 selectedSkinIdList) { }
	// RVA: 0x2816cd4 VA: 0x7594e2ecd4
	private Void _UpdateDisplaySkinInfo() { }
	// RVA: 0x2816f6c VA: 0x7594e2ef6c
	private List`1 _GenerateFilterdSkinList() { }
	// RVA: 0x2817b7c VA: 0x7594e2fb7c
	private Void _LoadSecretarySkin(String presetInstId) { }
	// RVA: 0x2818cec VA: 0x7594e30cec
	private static List`1 _GetSkinFiltersByType(FilterType type) { }
	// RVA: 0x2819124 VA: 0x7594e31124
	private static Boolean _CheckIfEvolveTwoSkin(HomeSecretarySkinItemModel model) { }
	// RVA: 0x28191a8 VA: 0x7594e311a8
	private static Boolean _CheckIfShopSkin(HomeSecretarySkinItemModel model) { }
	// RVA: 0x2819224 VA: 0x7594e31224
	private static Boolean _CheckIfDynSkin(HomeSecretarySkinItemModel model) { }
	// RVA: 0x2818a9c VA: 0x7594e30a9c
	private static Boolean _IsEvolveSkin(ListDict`2 evolveSkinDict, String skinId, out EvolvePhase phase) { }
	// RVA: 0x28192a0 VA: 0x7594e312a0
	public Void .ctor() { }
}
```