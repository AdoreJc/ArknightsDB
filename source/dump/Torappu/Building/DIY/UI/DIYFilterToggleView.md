# DIYFilterToggleView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `UIAtlasImage _toggleIcon`

- `UIAtlasImage _toggleIconLight`

- `UIAtlasObject _iconAtlas`

- `Image _toggleBackGround`

- `Image _subTypeBackGround`

- `RectTransform _toggleBgRect`

- `CanvasGroup _lightPanel`

- `Text _textContent`

- `Color _selectIconColor`

- `Color _selectBgColor`

- `Color _selectSubTypeColor`

- `Color _unselectIconColor`

- `Color _unselectBgColor`

- `Color _unselectSubTypeColor`

- `Single _expandDuration`

- `Boolean _isFixed`

- `RectTransform _panelSubType`

- `Transform _subTypeContainer`

- `DIYFilterSubButton _filterSubButtonPrefab`

- `GameObject _pnlTrackpoint`

- `Boolean m_isInited`

- `DIYFilterType m_filterType`

- `FilterToggleSwitchTween m_filterToggleSwitchTween`

- `Single m_bgExpandWidth`

- `Single m_toggleExpandWidth`

- `Boolean m_hasSubTypes`

- `TextGenerationSettings m_filterTextGenerationSettings`

- `TextGenerator m_cachedTextGenerator`


## Methods

- `Void _InitIfNot(DIYFilterModel, Boolean)`

- `Void _InitSubTypeButton(ListDict`2)`

- `Void _OnSubTypePressed(FurnitureSubType)`

- `Single _GetTextWidth(TextGenerationSettings, String)`

- `Void _OnSubTypeToggle(FurnitureSubType, Boolean)`

- `Void SetTextGenerationSettings(TextGenerationSettings)`

- `Void SetupFilterToggle(DIYFilterModel)`

- `Void OnToggle(Boolean, Boolean)`

- `Void OnSubTypeToggle(FurnitureSubType, Boolean)`

- `Void RenderTrackPointStatus(DIYFilterModel)`

- `Void OnFilterTogglePressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterToggleView : MonoBehaviour, IHotfixable
{
	private const Single TOGGLE_ICON_WIDTH; // 0x0
	private const Single TOGGLE_FOLD_WIDTH; // 0x0
	private const Single SUB_TYPE_BG_EXPAND_PADDING; // 0x0
	private const Single PADDING_SUB_BUTTON_WIDTH; // 0x0
	private UIAtlasImage _toggleIcon; // 0x18
	private UIAtlasImage _toggleIconLight; // 0x20
	private UIAtlasObject _iconAtlas; // 0x28
	private Image _toggleBackGround; // 0x30
	private Image _subTypeBackGround; // 0x38
	private RectTransform _toggleBgRect; // 0x40
	private CanvasGroup _lightPanel; // 0x48
	private Text _textContent; // 0x50
	private Color _selectIconColor; // 0x58
	private Color _selectBgColor; // 0x68
	private Color _selectSubTypeColor; // 0x78
	private Color _unselectIconColor; // 0x88
	private Color _unselectBgColor; // 0x98
	private Color _unselectSubTypeColor; // 0xa8
	private Single _expandDuration; // 0xb8
	private Boolean _isFixed; // 0xbc
	private RectTransform _panelSubType; // 0xc0
	private Transform _subTypeContainer; // 0xc8
	private DIYFilterSubButton _filterSubButtonPrefab; // 0xd0
	private GameObject _pnlTrackpoint; // 0xd8
	public Action`1 onFilterPressed; // 0xe0
	public Action`1 onSubTypePressed; // 0xe8
	private Boolean m_isInited; // 0xf0
	private DIYFilterType m_filterType; // 0xf4
	private List`1 m_subButtons; // 0xf8
	private FilterToggleSwitchTween m_filterToggleSwitchTween; // 0x100
	private Single m_bgExpandWidth; // 0x108
	private Single m_toggleExpandWidth; // 0x10c
	private Boolean m_hasSubTypes; // 0x110
	private TextGenerationSettings m_filterTextGenerationSettings; // 0x118
	private TextGenerator m_cachedTextGenerator; // 0x178
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__InitSubTypeButton; // 0x8
	private static DelegateBridge __Hotfix0__OnSubTypePressed; // 0x10
	private static DelegateBridge __Hotfix0__GetTextWidth; // 0x18
	private static DelegateBridge __Hotfix0__OnSubTypeToggle; // 0x20
	private static DelegateBridge __Hotfix0_SetTextGenerationSettings; // 0x28
	private static DelegateBridge __Hotfix0_SetupFilterToggle; // 0x30
	private static DelegateBridge __Hotfix0_OnToggle; // 0x38
	private static DelegateBridge __Hotfix0_OnSubTypeToggle; // 0x40
	private static DelegateBridge __Hotfix0_RenderTrackPointStatus; // 0x48
	private static DelegateBridge __Hotfix0_OnFilterTogglePressed; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x381656c VA: 0x7595e2e56c
	private Void _InitIfNot(DIYFilterModel filterModel, Boolean dontChangeContent) { }
	// RVA: 0x381695c VA: 0x7595e2e95c
	private Void _InitSubTypeButton(ListDict`2 subtypeModels) { }
	// RVA: 0x3816eb0 VA: 0x7595e2eeb0
	private Void _OnSubTypePressed(FurnitureSubType subType) { }
	// RVA: 0x3816d70 VA: 0x7595e2ed70
	private Single _GetTextWidth(TextGenerationSettings settings, String textContent) { }
	// RVA: 0x3816f50 VA: 0x7595e2ef50
	private Void _OnSubTypeToggle(FurnitureSubType subType, Boolean fastMode) { }
	// RVA: 0x38170cc VA: 0x7595e2f0cc
	public Void SetTextGenerationSettings(TextGenerationSettings settings) { }
	// RVA: 0x381584c VA: 0x7595e2d84c
	public Void SetupFilterToggle(DIYFilterModel filterModel) { }
	// RVA: 0x3815b14 VA: 0x7595e2db14
	public Void OnToggle(Boolean isSelected, Boolean fastMode) { }
	// RVA: 0x3815bbc VA: 0x7595e2dbbc
	public Void OnSubTypeToggle(FurnitureSubType subType, Boolean fastMode) { }
	// RVA: 0x3815c48 VA: 0x7595e2dc48
	public Void RenderTrackPointStatus(DIYFilterModel filterModel) { }
	// RVA: 0x3817184 VA: 0x7595e2f184
	public Void OnFilterTogglePressed() { }
	// RVA: 0x381720c VA: 0x7595e2f20c
	public Void .ctor() { }
}
```