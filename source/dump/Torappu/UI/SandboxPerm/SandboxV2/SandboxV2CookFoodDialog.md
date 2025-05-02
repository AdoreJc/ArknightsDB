# SandboxV2CookFoodDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIRenderTextureImage _blurBackground`

- `RectTransform _backRect`

- `SandboxV2CookDeckView _deckPrefab`

- `Transform _deckHolder`

- `GameObject _subItemsPanel`

- `GameObject _subEmptyPanel`

- `GameObject _switchRecipePanel`

- `GameObject _clearValidPanel`

- `GameObject _clearInvalidPanel`

- `GameObject _makeValidPanel`

- `GameObject _makeInvalidPanel`

- `SimpleLayoutContent _mainMatContent`

- `SimpleLayoutContent _subMatContent`

- `Text _foodNameText`

- `Text _foodStockText`

- `Text _currentRecipeText`

- `Single _itemCardScale`

- `SandboxV2Data m_gameData`

- `SandboxV2CookDeckView m_deckView`

- `Adapter m_mainMatAdapter`

- `Adapter m_subMatAdapter`

- `Options m_options`

- `String m_cachedTopicId`

- `String m_cachedFoodId`

- `SandboxV2FoodData m_cachedFoodData`

- `String m_cachedFoodFallbackName`

- `Int32 m_cachedRecipeIndex`

- `Boolean m_canMake`

- `CookResult m_cachedCookResult`


## Methods

- `Void OnBackEvent()`

- `Void OnSwitchRecipeEvent()`

- `Void OnClearEvent()`

- `Void OnMakeEvent()`

- `Void _UpdateViews()`

- `Void _LoadData()`

- `Void _RefreshFood()`

- `Void _RefreshFoodRecipe()`

- `Void _LoadFoodData(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadRecipeData(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadSubData(SandboxV2Data, PlayerSandboxV2)`

- `Boolean _CheckSubMatOptionValid()`

- `Void _OnSubMatSelect(Int32)`

- `Void _OnSubMatDeselect(Int32)`

- `Void _OnCookFoodRespond(SandboxV2CookFoodResponse)`

- `Void _ConfirmWithCookResult()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFoodDialog : UICompDialog`1
{
	private UIRenderTextureImage _blurBackground; // 0x48
	private RectTransform _backRect; // 0x50
	private SandboxV2CookDeckView _deckPrefab; // 0x58
	private Transform _deckHolder; // 0x60
	private GameObject _subItemsPanel; // 0x68
	private GameObject _subEmptyPanel; // 0x70
	private GameObject _switchRecipePanel; // 0x78
	private GameObject _clearValidPanel; // 0x80
	private GameObject _clearInvalidPanel; // 0x88
	private GameObject _makeValidPanel; // 0x90
	private GameObject _makeInvalidPanel; // 0x98
	private SimpleLayoutContent _mainMatContent; // 0xa0
	private SimpleLayoutContent _subMatContent; // 0xa8
	private Text _foodNameText; // 0xb0
	private Text _foodStockText; // 0xb8
	private Text _currentRecipeText; // 0xc0
	private Single _itemCardScale; // 0xc8
	private SandboxV2Data m_gameData; // 0xd0
	private SandboxV2CookDeckView m_deckView; // 0xd8
	private Adapter m_mainMatAdapter; // 0xe0
	private Adapter m_subMatAdapter; // 0xe8
	private Options m_options; // 0xf0
	private String m_cachedTopicId; // 0xf8
	private String m_cachedFoodId; // 0x100
	private SandboxV2FoodData m_cachedFoodData; // 0x108
	private String m_cachedFoodFallbackName; // 0x110
	private Int32 m_cachedRecipeIndex; // 0x118
	private Boolean m_canMake; // 0x11c
	private readonly List`1 m_seperatedMainMats; // 0x120
	private readonly List`1 m_mainMatItems; // 0x128
	private readonly List`1 m_subMatItems; // 0x130
	private readonly Dictionary`2 m_subItemDict; // 0x138
	private readonly List`1 m_subItemIdList; // 0x140
	private readonly Dictionary`2 m_testDict; // 0x148
	private CookResult m_cachedCookResult; // 0x150
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnSwitchRecipeEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnClearEvent; // 0x28
	private static DelegateBridge __Hotfix0_OnMakeEvent; // 0x30
	private static DelegateBridge __Hotfix0__UpdateViews; // 0x38
	private static DelegateBridge __Hotfix0__LoadData; // 0x40
	private static DelegateBridge __Hotfix0__RefreshFood; // 0x48
	private static DelegateBridge __Hotfix0__RefreshFoodRecipe; // 0x50
	private static DelegateBridge __Hotfix0__LoadFoodData; // 0x58
	private static DelegateBridge __Hotfix0__LoadRecipeData; // 0x60
	private static DelegateBridge __Hotfix0__LoadSubData; // 0x68
	private static DelegateBridge __Hotfix0__CheckSubMatOptionValid; // 0x70
	private static DelegateBridge __Hotfix0__OnSubMatSelect; // 0x78
	private static DelegateBridge __Hotfix0__OnSubMatDeselect; // 0x80
	private static DelegateBridge __Hotfix0__OnCookFoodRespond; // 0x88
	private static DelegateBridge __Hotfix0__ConfirmWithCookResult; // 0x90
	private static DelegateBridge __Hotfix0__ItemComparison; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x24ce270 VA: 0x7594ae6270
	protected override Void OnInit() { }
	// RVA: 0x24ce7fc VA: 0x7594ae67fc
	protected override Void OnRender(Options options) { }
	// RVA: 0x24cf59c VA: 0x7594ae759c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x24cf604 VA: 0x7594ae7604
	public Void OnBackEvent() { }
	// RVA: 0x24cf6f4 VA: 0x7594ae76f4
	public Void OnSwitchRecipeEvent() { }
	// RVA: 0x24cf7d8 VA: 0x7594ae77d8
	public Void OnClearEvent() { }
	// RVA: 0x24cf9cc VA: 0x7594ae79cc
	public Void OnMakeEvent() { }
	// RVA: 0x24cf198 VA: 0x7594ae7198
	private Void _UpdateViews() { }
	// RVA: 0x24cebb0 VA: 0x7594ae6bb0
	private Void _LoadData() { }
	// RVA: 0x24cfdc0 VA: 0x7594ae7dc0
	private Void _RefreshFood() { }
	// RVA: 0x24cff18 VA: 0x7594ae7f18
	private Void _RefreshFoodRecipe() { }
	// RVA: 0x24d0064 VA: 0x7594ae8064
	private Void _LoadFoodData(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24d0230 VA: 0x7594ae8230
	private Void _LoadRecipeData(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24d0a28 VA: 0x7594ae8a28
	private Void _LoadSubData(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24cedd8 VA: 0x7594ae6dd8
	private Boolean _CheckSubMatOptionValid() { }
	// RVA: 0x24d0d70 VA: 0x7594ae8d70
	private Void _OnSubMatSelect(Int32 index) { }
	// RVA: 0x24d0f64 VA: 0x7594ae8f64
	private Void _OnSubMatDeselect(Int32 index) { }
	// RVA: 0x24d1100 VA: 0x7594ae9100
	private Void _OnCookFoodRespond(SandboxV2CookFoodResponse response) { }
	// RVA: 0x24d1488 VA: 0x7594ae9488
	private Void _ConfirmWithCookResult() { }
	// RVA: 0x24d153c VA: 0x7594ae953c
	private static Int32 _ItemComparison(UIItemViewModel x, UIItemViewModel y) { }
	// RVA: 0x24d1640 VA: 0x7594ae9640
	public Void .ctor() { }
	// RVA: 0x24d1864 VA: 0x7594ae9864
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x24d186c VA: 0x7594ae986c
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```