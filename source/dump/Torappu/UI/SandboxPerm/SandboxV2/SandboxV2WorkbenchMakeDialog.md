# SandboxV2WorkbenchMakeDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIRenderTextureImage _blurBackground`

- `RectTransform _backRect`

- `SandboxV2ItemCard _itemCardPrefab`

- `Transform _itemCardHolder`

- `Single _itemCardScale`

- `Text _nameText`

- `Text _usageText`

- `Text _descText`

- `GameObject _tagPanel`

- `Image _tagPicImage`

- `Text _tagNameText`

- `Text _stockText`

- `GameObject _deployStatusPanel`

- `Text _deployStatusText`

- `SimpleLayoutContent _materialContent`

- `Single _materialItemCardScale`

- `Image _increaseMakeCountButtonImage`

- `UILongPressButtonEx _decreaseMakeCountButton`

- `UILongPressButtonEx _increaseMakeCountButton`

- `Text _makeCountText`

- `Text _totalCountText`

- `Color _validColor`

- `Color _invalidColor`

- `GameObject _levelPanel`

- `GameObject _makeValidPanel`

- `GameObject _makeInvalidPanel`

- `UIAnimationLocation _itemAnimation`

- `CanvasGroup _lowGroup`

- `CanvasGroup _highNearGroup`

- `CanvasGroup _highFarGroup`

- `SandboxV2ItemCard m_makeItemCard`

- `MatAdapter m_matAdapter`

- `LevelAnimator m_levelAnimator`

- `Options m_options`

- `String m_waterId`

- `String m_goldId`

- `Int32 m_goldCount`

- `Int32 m_onceMakeLimit`

- `Int32 m_makingLevel`

- `MakeItemModel m_makingItem`

- `Int32 m_makingCount`

- `Boolean m_makeValid`

- `WorkBenchMakeResult m_cachedMakeResult`


## Methods

- `Void OnBackEvent()`

- `Void OnMakeConfirmEvent()`

- `Void OnSelectLevel(Int32)`

- `Void _LoadData()`

- `Void _UpdatePanel()`

- `Void _UpdateMakingItem()`

- `Void _UpdateMakingItemTag()`

- `Void _LoadCraftItems(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadAlchemyItems(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadCraftItemSingle(SandboxV2Data, PlayerSandboxV2)`

- `Void _LoadAlchemyItemSingle(SandboxV2Data, PlayerSandboxV2)`

- `Int32 _MatComparison(MakeMaterialModel, MakeMaterialModel)`

- `Void _UpdateMakingLevel(Int32)`

- `Boolean _UpdateMakingCount(Int32)`

- `Void _OnCraftResponded(SandboxV2CraftResponse)`

- `Void _OnAlchemyResponded(SandboxV2AlchemyResponse)`

- `Void _ConfirmWithMakeResult()`

- `Void _OnMakeCountIncrease()`

- `Boolean _OnMakeCountIncreaseLongPress()`

- `Void _OnMakeCountDecrease()`

- `Boolean _OnMakeCountDecreaseLongPress()`

- `Void _SendCraftRequest()`

- `MakeMaterialModel _GenerateMaterial(PlayerSandboxV2, String, Int32)`

- `Void _TutorialOnly_RegisterButton()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2WorkbenchMakeDialog : UICompDialog`1
{
	private const Int32 MAKE_COUNT_LONG_PRESS_STEP; // 0x0
	private UIRenderTextureImage _blurBackground; // 0x48
	private RectTransform _backRect; // 0x50
	private SandboxV2ItemCard _itemCardPrefab; // 0x58
	private Transform _itemCardHolder; // 0x60
	private Single _itemCardScale; // 0x68
	private Text _nameText; // 0x70
	private Text _usageText; // 0x78
	private Text _descText; // 0x80
	private GameObject _tagPanel; // 0x88
	private Image _tagPicImage; // 0x90
	private Text _tagNameText; // 0x98
	private Text _stockText; // 0xa0
	private GameObject _deployStatusPanel; // 0xa8
	private Text _deployStatusText; // 0xb0
	private SimpleLayoutContent _materialContent; // 0xb8
	private Single _materialItemCardScale; // 0xc0
	private Image _increaseMakeCountButtonImage; // 0xc8
	private UILongPressButtonEx _decreaseMakeCountButton; // 0xd0
	private UILongPressButtonEx _increaseMakeCountButton; // 0xd8
	private Text _makeCountText; // 0xe0
	private Text _totalCountText; // 0xe8
	private Color _validColor; // 0xf0
	private Color _invalidColor; // 0x100
	private GameObject _levelPanel; // 0x110
	private GameObject[] _alchemyPanels; // 0x118
	private GameObject[] _craftPanels; // 0x120
	private GameObject _makeValidPanel; // 0x128
	private GameObject _makeInvalidPanel; // 0x130
	private MakeLevelGroup[] _levelGroups; // 0x138
	private UIAnimationLocation _itemAnimation; // 0x140
	private CanvasGroup _lowGroup; // 0x150
	private CanvasGroup _highNearGroup; // 0x158
	private CanvasGroup _highFarGroup; // 0x160
	private CanvasGroup[] _switchGroups; // 0x168
	private readonly List`1 m_items; // 0x170
	private SandboxV2ItemCard m_makeItemCard; // 0x178
	private MatAdapter m_matAdapter; // 0x180
	private LevelAnimator m_levelAnimator; // 0x188
	private Options m_options; // 0x190
	private String m_waterId; // 0x198
	private String m_goldId; // 0x1a0
	private Int32 m_goldCount; // 0x1a8
	private Int32 m_onceMakeLimit; // 0x1ac
	private Int32 m_makingLevel; // 0x1b0
	private MakeItemModel m_makingItem; // 0x1b8
	private Int32 m_makingCount; // 0x1c0
	private Boolean m_makeValid; // 0x1c4
	private WorkBenchMakeResult m_cachedMakeResult; // 0x1c8
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnMakeConfirmEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnSelectLevel; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnRender; // 0x20
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x28
	private static DelegateBridge __Hotfix0__LoadData; // 0x30
	private static DelegateBridge __Hotfix0__UpdatePanel; // 0x38
	private static DelegateBridge __Hotfix0__UpdateMakingItem; // 0x40
	private static DelegateBridge __Hotfix0__UpdateMakingItemTag; // 0x48
	private static DelegateBridge __Hotfix0__LoadCraftItems; // 0x50
	private static DelegateBridge __Hotfix0__LoadAlchemyItems; // 0x58
	private static DelegateBridge __Hotfix0__LoadCraftItemSingle; // 0x60
	private static DelegateBridge __Hotfix0__LoadAlchemyItemSingle; // 0x68
	private static DelegateBridge __Hotfix0__GenerateMaterials; // 0x70
	private static DelegateBridge __Hotfix1__GenerateMaterials; // 0x78
	private static DelegateBridge __Hotfix0__MatComparison; // 0x80
	private static DelegateBridge __Hotfix0__UpdateMakingLevel; // 0x88
	private static DelegateBridge __Hotfix0__UpdateMakingCount; // 0x90
	private static DelegateBridge __Hotfix0__OnCraftResponded; // 0x98
	private static DelegateBridge __Hotfix0__OnAlchemyResponded; // 0xa0
	private static DelegateBridge __Hotfix0__ConfirmWithMakeResult; // 0xa8
	private static DelegateBridge __Hotfix0__OnMakeCountIncrease; // 0xb0
	private static DelegateBridge __Hotfix0__OnMakeCountIncreaseLongPress; // 0xb8
	private static DelegateBridge __Hotfix0__OnMakeCountDecrease; // 0xc0
	private static DelegateBridge __Hotfix0__OnMakeCountDecreaseLongPress; // 0xc8
	private static DelegateBridge __Hotfix0__SendCraftRequest; // 0xd0
	private static DelegateBridge __Hotfix0__GenerateMaterial; // 0xd8
	private static DelegateBridge __Hotfix0__AlchemyItemComparison; // 0xe0
	private static DelegateBridge __Hotfix0__TutorialOnly_RegisterButton; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0


	// RVA: 0x24f0718 VA: 0x7594b08718
	public Void OnBackEvent() { }
	// RVA: 0x24f0808 VA: 0x7594b08808
	public Void OnMakeConfirmEvent() { }
	// RVA: 0x24f0ecc VA: 0x7594b08ecc
	public Void OnSelectLevel(Int32 level) { }
	// RVA: 0x24f108c VA: 0x7594b0908c
	protected override Void OnInit() { }
	// RVA: 0x24f1cb0 VA: 0x7594b09cb0
	protected override Void OnRender(Options input) { }
	// RVA: 0x24f2a8c VA: 0x7594b0aa8c
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x24f1d80 VA: 0x7594b09d80
	private Void _LoadData() { }
	// RVA: 0x24f3cc0 VA: 0x7594b0bcc0
	private Void _UpdatePanel() { }
	// RVA: 0x24f1fec VA: 0x7594b09fec
	private Void _UpdateMakingItem() { }
	// RVA: 0x24f3d34 VA: 0x7594b0bd34
	private Void _UpdateMakingItemTag() { }
	// RVA: 0x24f3790 VA: 0x7594b0b790
	private Void _LoadCraftItems(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24f32c8 VA: 0x7594b0b2c8
	private Void _LoadAlchemyItems(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24f2e64 VA: 0x7594b0ae64
	private Void _LoadCraftItemSingle(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24f2af4 VA: 0x7594b0aaf4
	private Void _LoadAlchemyItemSingle(SandboxV2Data gameData, PlayerSandboxV2 playerData) { }
	// RVA: 0x24f3e44 VA: 0x7594b0be44
	private List`1 _GenerateMaterials(PlayerSandboxV2 playerData, SandboxV2CraftItemData craftData, Int32 makeLimit, out Int32 makeMaximum) { }
	// RVA: 0x24f4274 VA: 0x7594b0c274
	private List`1 _GenerateMaterials(PlayerSandboxV2 playerData, SandboxV2AlchemyRecipeData recipeData, Int32 makeLimit, out Int32 makeMaximum) { }
	// RVA: 0x24f4880 VA: 0x7594b0c880
	private Int32 _MatComparison(MakeMaterialModel x, MakeMaterialModel y) { }
	// RVA: 0x24f0f4c VA: 0x7594b08f4c
	private Void _UpdateMakingLevel(Int32 makingLevel) { }
	// RVA: 0x24f22e0 VA: 0x7594b0a2e0
	private Boolean _UpdateMakingCount(Int32 makingCount) { }
	// RVA: 0x24f4b74 VA: 0x7594b0cb74
	private Void _OnCraftResponded(SandboxV2CraftResponse response) { }
	// RVA: 0x24f4eec VA: 0x7594b0ceec
	private Void _OnAlchemyResponded(SandboxV2AlchemyResponse response) { }
	// RVA: 0x24f51c4 VA: 0x7594b0d1c4
	private Void _ConfirmWithMakeResult() { }
	// RVA: 0x24f5278 VA: 0x7594b0d278
	private Void _OnMakeCountIncrease() { }
	// RVA: 0x24f538c VA: 0x7594b0d38c
	private Boolean _OnMakeCountIncreaseLongPress() { }
	// RVA: 0x24f549c VA: 0x7594b0d49c
	private Void _OnMakeCountDecrease() { }
	// RVA: 0x24f550c VA: 0x7594b0d50c
	private Boolean _OnMakeCountDecreaseLongPress() { }
	// RVA: 0x24f0cac VA: 0x7594b08cac
	private Void _SendCraftRequest() { }
	// RVA: 0x24f4630 VA: 0x7594b0c630
	private MakeMaterialModel _GenerateMaterial(PlayerSandboxV2 playerData, String id, Int32 count) { }
	// RVA: 0x24f55cc VA: 0x7594b0d5cc
	private static Int32 _AlchemyItemComparison(MakeItemModel x, MakeItemModel y) { }
	// RVA: 0x24f1be4 VA: 0x7594b09be4
	private Void _TutorialOnly_RegisterButton() { }
	// RVA: 0x24f565c VA: 0x7594b0d65c
	public Void .ctor() { }
	// RVA: 0x24f5740 VA: 0x7594b0d740
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x24f5748 VA: 0x7594b0d748
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```