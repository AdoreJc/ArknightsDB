# MainStageButtonOnMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _spriteBkgTraining`

- `Sprite _spriteBkgStory`

- `Sprite _spriteBkgNormal`

- `Sprite _spriteBkgPredefinedNormal`

- `Sprite _spriteBkgBranch`

- `Sprite _spriteBkgHilight`

- `Image _imgBkg`

- `Color _normalTextColor`

- `Color _trainTextColor`

- `Color _storyTextColor`

- `Color _hilightTextColor`

- `Color _predefinedTextColor`

- `Graphic _hightDifficultBkgPrefab`

- `Graphic _mistOptBkgPrefab`

- `RectTransform _bkgInstLayer`

- `Image _iconBoss`

- `Sprite _spriteBossNormal`

- `Sprite _spriteBossHilight`

- `Image _iconTrainFinished`

- `Image _iconTrainUnfinished`

- `Image _iconPredefinedTraining`

- `Image _storyOnlyMark`

- `RectTransform _itemCardContainer`

- `Single _itemScaler`

- `GameObject _charContainer`

- `Image _imgChar`

- `Vector2 _charPosNoItem`

- `Vector2 _charPosWithItem`

- `UIColorGraphic _selectionGraphic`

- `Color _selectedColor`

- `Button _stageButton`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `UIItemViewModel m_charModel`

- `Graphic m_highDifficultBkgInst`

- `Graphic m_mistOptBkgInst`

- `ViewModelCache m_viewModelCache`

- `Boolean m_isBtnInited`


## Methods

- `Void _InitIfNot(StageButtonOnMapHolder)`

- `Boolean _CheckCanStageShowWithFog(StageViewModel)`

- `Void _RenderBkg()`

- `Void _RenderBossIcon()`

- `Void _RenderRewards()`

- `Void HideReward()`

- `Void _RenderEntry()`

- `Void HideEntry()`

- `Void HideStageNameCode()`

- `Void SetBtnColor(Color)`

- `Boolean _InstBkgStyle(Graphic, Boolean, ref)`

- `RectTransform <>xLuaBaseProxy_get_positionRect()`

- `Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`

- `Boolean <>xLuaBaseProxy_CheckIsStageButtonBlockClick(StageViewModel, ZoneViewModel)`

- `Boolean <>xLuaBaseProxy_CheckStageLocked(StageViewModel, ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainStageButtonOnMap : StageButtonOnMap, IHotfixable
{
	public const String FUNC_SELECT_GRAPHIC; // 0x0
	private Sprite _spriteBkgTraining; // 0xd8
	private Sprite _spriteBkgStory; // 0xe0
	private Sprite _spriteBkgNormal; // 0xe8
	private Sprite _spriteBkgPredefinedNormal; // 0xf0
	private Sprite _spriteBkgBranch; // 0xf8
	private Sprite _spriteBkgHilight; // 0x100
	private Image _imgBkg; // 0x108
	private Color _normalTextColor; // 0x110
	private Color _trainTextColor; // 0x120
	private Color _storyTextColor; // 0x130
	private Color _hilightTextColor; // 0x140
	private Color _predefinedTextColor; // 0x150
	private Graphic _hightDifficultBkgPrefab; // 0x160
	private Graphic _mistOptBkgPrefab; // 0x168
	private RectTransform _bkgInstLayer; // 0x170
	private Image _iconBoss; // 0x178
	private Sprite _spriteBossNormal; // 0x180
	private Sprite _spriteBossHilight; // 0x188
	private Image _iconTrainFinished; // 0x190
	private Image _iconTrainUnfinished; // 0x198
	private Image _iconPredefinedTraining; // 0x1a0
	private Image _storyOnlyMark; // 0x1a8
	private RectTransform _itemCardContainer; // 0x1b0
	private Single _itemScaler; // 0x1b8
	private GameObject _charContainer; // 0x1c0
	private Image _imgChar; // 0x1c8
	private Vector2 _charPosNoItem; // 0x1d0
	private Vector2 _charPosWithItem; // 0x1d8
	private UIColorGraphic _selectionGraphic; // 0x1e0
	private Color _selectedColor; // 0x1e8
	private Button _stageButton; // 0x1f8
	private UIItemCard m_itemCard; // 0x200
	private UIItemViewModel m_itemModel; // 0x208
	private UIItemViewModel m_charModel; // 0x210
	private Graphic m_highDifficultBkgInst; // 0x218
	private Graphic m_mistOptBkgInst; // 0x220
	private ViewModelCache m_viewModelCache; // 0x228
	private Boolean m_isBtnInited; // 0x258
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_positionRect; // 0x8
	private static DelegateBridge __Hotfix0_RenderStage; // 0x10
	private static DelegateBridge __Hotfix0_CheckIsStageButtonBlockClick; // 0x18
	private static DelegateBridge __Hotfix0_CheckStageLocked; // 0x20
	private static DelegateBridge __Hotfix0__CheckCanStageShowWithFog; // 0x28
	private static DelegateBridge __Hotfix0__RenderBkg; // 0x30
	private static DelegateBridge __Hotfix0__RenderBossIcon; // 0x38
	private static DelegateBridge __Hotfix0__RenderRewards; // 0x40
	private static DelegateBridge __Hotfix0_HideReward; // 0x48
	private static DelegateBridge __Hotfix0__RenderEntry; // 0x50
	private static DelegateBridge __Hotfix0_HideEntry; // 0x58
	private static DelegateBridge __Hotfix0_HideStageNameCode; // 0x60
	private static DelegateBridge __Hotfix0_SetBtnColor; // 0x68
	private static DelegateBridge __Hotfix0__InstBkgStyle; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override RectTransform positionRect { get; }

	// RVA: 0x2f8f1b8 VA: 0x75955a71b8
	private Void _InitIfNot(StageButtonOnMapHolder holder) { }
	// RVA: 0x2f8f334 VA: 0x75955a7334
	public override RectTransform get_positionRect() { }
	// RVA: 0x2f8f3a0 VA: 0x75955a73a0
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2f90364 VA: 0x75955a8364
	protected override Boolean CheckIsStageButtonBlockClick(StageViewModel stageViewModel, ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f903f4 VA: 0x75955a83f4
	protected override Boolean CheckStageLocked(StageViewModel stageViewModel, ZoneViewModel zoneViewModel) { }
	// RVA: 0x2f904c8 VA: 0x75955a84c8
	private Boolean _CheckCanStageShowWithFog(StageViewModel stageViewModel) { }
	// RVA: 0x2f8f6fc VA: 0x75955a76fc
	private Void _RenderBkg() { }
	// RVA: 0x2f8fa30 VA: 0x75955a7a30
	private Void _RenderBossIcon() { }
	// RVA: 0x2f8fb70 VA: 0x75955a7b70
	private Void _RenderRewards() { }
	// RVA: 0x2f90788 VA: 0x75955a8788
	public Void HideReward() { }
	// RVA: 0x2f8ff90 VA: 0x75955a7f90
	private Void _RenderEntry() { }
	// RVA: 0x2f90854 VA: 0x75955a8854
	public Void HideEntry() { }
	// RVA: 0x2f909bc VA: 0x75955a89bc
	public Void HideStageNameCode() { }
	// RVA: 0x2f901cc VA: 0x75955a81cc
	public Void SetBtnColor(Color targetColor) { }
	// RVA: 0x2f905a0 VA: 0x75955a85a0
	private Boolean _InstBkgStyle(Graphic prefab, Boolean isShow, ref Graphic inst) { }
	// RVA: 0x2f90af8 VA: 0x75955a8af8
	public Void .ctor() { }
	// RVA: 0x2f90b80 VA: 0x75955a8b80
	private RectTransform <>xLuaBaseProxy_get_positionRect() { }
	// RVA: 0x2f90b88 VA: 0x75955a8b88
	private Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder P0, StageViewModel P1, ZoneViewModel P2, Boolean P3) { }
	// RVA: 0x2f90b94 VA: 0x75955a8b94
	private Boolean <>xLuaBaseProxy_CheckIsStageButtonBlockClick(StageViewModel P0, ZoneViewModel P1) { }
	// RVA: 0x2f90b9c VA: 0x75955a8b9c
	private Boolean <>xLuaBaseProxy_CheckStageLocked(StageViewModel P0, ZoneViewModel P1) { }
}
```