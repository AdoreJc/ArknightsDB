# RoguelikeChoiceItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Single _disableTextAlpha`

- `Single _disableIconAlpha`

- `Single _activeIconAlpha`

- `Color _diableBgColor`

- `Text _titleLabel`

- `Text _contentLabel`

- `Text _itemTitleLabel`

- `Text _itemDescLabel`

- `Text _itemHintLabel`

- `Image _funcIconImage`

- `RectTransform _itemIconHolder`

- `RoguelikeCustomizableItemIcon _itemIconPrefab`

- `Single _itemIconScale`

- `Button _choiceButton`

- `Button _riseButton`

- `RectTransform _leftDecoContainer`

- `UIAnimationLocation _switchAnim`

- `CanvasGroup _canvasFuncIcon`

- `CanvasGroup _canvasItemIcon`

- `UIColorGraphic _graphicChoiceGraphic`

- `UIColorGraphic _graphicRiseGraphic`

- `IRoguelikeGameChoice m_choice`

- `String m_topicId`

- `Boolean m_active`

- `RoguelikeChoiceLeftDecoType m_cacheDecoType`

- `RoguelikeChoiceLeftDecoView m_leftDecoView`

- `RoguelikeChoicePlugin m_choicePlugin`

- `RoguelikeCustomizableItemIcon m_itemIcon`


## Methods

- `Void set_onChoiceConfirm(Action`1)`

- `Void set_onChoiceSelect(Action`1)`

- `RoguelikeCustomizableItemIcon _EnsureItemIcon()`

- `Void Setup(String, UIPage, RoguelikeChoicePlugin, IRoguelikeGameChoice)`

- `Void _CreateAndRenderLeftDeco()`

- `Void _SetContentVisible(Boolean)`

- `Void SetChoiceActive(Boolean, Action)`

- `Boolean IsChoiceEqual(IRoguelikeGameChoice)`

- `Void OnSelectButtonPressed()`

- `Void OnActiveButtonPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceItemView : MonoBehaviour, IHotfixable
{
	private Single _disableTextAlpha; // 0x18
	private Single _disableIconAlpha; // 0x1c
	private Single _activeIconAlpha; // 0x20
	private Color _diableBgColor; // 0x24
	private UIAtlasImage[] _bgImageList; // 0x38
	private Text[] _descTextList; // 0x40
	private Text _titleLabel; // 0x48
	private Text _contentLabel; // 0x50
	private Text _itemTitleLabel; // 0x58
	private Text _itemDescLabel; // 0x60
	private Text _itemHintLabel; // 0x68
	private Image _funcIconImage; // 0x70
	private RectTransform _itemIconHolder; // 0x78
	private RoguelikeCustomizableItemIcon _itemIconPrefab; // 0x80
	private Single _itemIconScale; // 0x88
	private Button _choiceButton; // 0x90
	private Button _riseButton; // 0x98
	private RectTransform _leftDecoContainer; // 0xa0
	private UIAnimationLocation _switchAnim; // 0xa8
	private CanvasGroup _canvasFuncIcon; // 0xb8
	private CanvasGroup _canvasItemIcon; // 0xc0
	private UIColorGraphic _graphicChoiceGraphic; // 0xc8
	private UIColorGraphic _graphicRiseGraphic; // 0xd0
	private IRoguelikeGameChoice m_choice; // 0xd8
	private String m_topicId; // 0xe0
	private Boolean m_active; // 0xe8
	private RoguelikeChoiceLeftDecoType m_cacheDecoType; // 0xec
	private RoguelikeChoiceLeftDecoView m_leftDecoView; // 0xf0
	private RoguelikeChoicePlugin m_choicePlugin; // 0xf8
	private RoguelikeCustomizableItemIcon m_itemIcon; // 0x100
	private Action`1 <onChoiceConfirm>k__BackingField; // 0x108
	private Action`1 <onChoiceSelect>k__BackingField; // 0x110
	private static DelegateBridge __Hotfix0_get_onChoiceConfirm; // 0x0
	private static DelegateBridge __Hotfix0_set_onChoiceConfirm; // 0x8
	private static DelegateBridge __Hotfix0_get_onChoiceSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_onChoiceSelect; // 0x18
	private static DelegateBridge __Hotfix0__EnsureItemIcon; // 0x20
	private static DelegateBridge __Hotfix0_Setup; // 0x28
	private static DelegateBridge __Hotfix0__CreateAndRenderLeftDeco; // 0x30
	private static DelegateBridge __Hotfix0__SetContentVisible; // 0x38
	private static DelegateBridge __Hotfix0_SetChoiceActive; // 0x40
	private static DelegateBridge __Hotfix0_IsChoiceEqual; // 0x48
	private static DelegateBridge __Hotfix0_OnSelectButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnActiveButtonPressed; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`1 onChoiceConfirm { get; set; }
	private Action`1 onChoiceSelect { get; set; }

	// RVA: 0x29ecaec VA: 0x7595004aec
	private Action`1 get_onChoiceConfirm() { }
	// RVA: 0x29ecb54 VA: 0x7595004b54
	public Void set_onChoiceConfirm(Action`1 value) { }
	// RVA: 0x29ecbd8 VA: 0x7595004bd8
	private Action`1 get_onChoiceSelect() { }
	// RVA: 0x29ecc40 VA: 0x7595004c40
	public Void set_onChoiceSelect(Action`1 value) { }
	// RVA: 0x29eccc4 VA: 0x7595004cc4
	private RoguelikeCustomizableItemIcon _EnsureItemIcon() { }
	// RVA: 0x29ece38 VA: 0x7595004e38
	public Void Setup(String topicId, UIPage page, RoguelikeChoicePlugin choicePlugin, IRoguelikeGameChoice choice) { }
	// RVA: 0x29ed97c VA: 0x759500597c
	private Void _CreateAndRenderLeftDeco() { }
	// RVA: 0x29ede50 VA: 0x7595005e50
	private Void _SetContentVisible(Boolean isExpand) { }
	// RVA: 0x29ee098 VA: 0x7595006098
	public Void SetChoiceActive(Boolean active, Action onAnimComplete) { }
	// RVA: 0x29ee2f4 VA: 0x75950062f4
	public Boolean IsChoiceEqual(IRoguelikeGameChoice choice) { }
	// RVA: 0x29ee384 VA: 0x7595006384
	public Void OnSelectButtonPressed() { }
	// RVA: 0x29ee42c VA: 0x759500642c
	public Void OnActiveButtonPressed() { }
	// RVA: 0x29ee4cc VA: 0x75950064cc
	public Void .ctor() { }
}
```