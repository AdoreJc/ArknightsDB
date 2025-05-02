# RoguelikeExpeditionView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasSelected`

- `CanvasGroup _canvasNoSelect`

- `RectTransform _selectingBeforeTransHolder`

- `RectTransform _selectingAfterTransHolder`

- `Text _txtTipsSelect`

- `RoguelikeExpeditionCharGridAdapter _charCardList`

- `LoopVerticalScrollRect _charListScrollRect`

- `RoguelikeExpeditionPluginContext _pluginContext`

- `Action <onConfirmClick>k__BackingField`

- `Boolean m_inited`

- `RoguelikeExpeditionSelectingCharView m_selectingBeforeView`

- `RoguelikeExpeditionSelectingCharView m_selectingAfterView`

- `UISwitchTween m_showTweenNoSelect`

- `UISwitchTween m_showTweenSelect`

- `String m_cachedSelectedCharId`


## Properties

- `RoguelikeExpeditionPluginContext pluginContext`

- `Action onConfirmClick`


## Methods

- `RoguelikeExpeditionPluginContext get_pluginContext()`

- `Void set_onCharItemClicked(Action`1)`

- `Action get_onConfirmClick()`

- `Void set_onConfirmClick(Action)`

- `Void _InitIfNot()`

- `Void _RenderSelectingPart(RoguelikeExpeditionModel)`

- `Void _FadeSelectingPart(Boolean, Boolean)`

- `Void ResetListToTop()`

- `Void _OnCharItemClick(String)`

- `Void OnConfirmClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionView : DataBinder`1
{
	private CanvasGroup _canvasSelected; // 0x20
	private CanvasGroup _canvasNoSelect; // 0x28
	private RectTransform _selectingBeforeTransHolder; // 0x30
	private RectTransform _selectingAfterTransHolder; // 0x38
	private Text _txtTipsSelect; // 0x40
	private RoguelikeExpeditionCharGridAdapter _charCardList; // 0x48
	private LoopVerticalScrollRect _charListScrollRect; // 0x50
	private RoguelikeExpeditionPluginContext _pluginContext; // 0x58
	private Action`1 <onCharItemClicked>k__BackingField; // 0x60
	private Action <onConfirmClick>k__BackingField; // 0x68
	private Boolean m_inited; // 0x70
	private RoguelikeExpeditionSelectingCharView m_selectingBeforeView; // 0x78
	private RoguelikeExpeditionSelectingCharView m_selectingAfterView; // 0x80
	private UISwitchTween m_showTweenNoSelect; // 0x88
	private UISwitchTween m_showTweenSelect; // 0x90
	private String m_cachedSelectedCharId; // 0x98
	private static DelegateBridge __Hotfix0_get_pluginContext; // 0x0
	private static DelegateBridge __Hotfix0_get_onCharItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_set_onCharItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_get_onConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0_set_onConfirmClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__RenderSelectingPart; // 0x30
	private static DelegateBridge __Hotfix0__FadeSelectingPart; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0_ResetListToTop; // 0x48
	private static DelegateBridge __Hotfix0__OnCharItemClick; // 0x50
	private static DelegateBridge __Hotfix0_OnConfirmClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public RoguelikeExpeditionPluginContext pluginContext { get; }
	public Action`1 onCharItemClicked { get; set; }
	public Action onConfirmClick { get; set; }

	// RVA: 0x2a33f04 VA: 0x759504bf04
	public RoguelikeExpeditionPluginContext get_pluginContext() { }
	// RVA: 0x2a35d90 VA: 0x759504dd90
	public Action`1 get_onCharItemClicked() { }
	// RVA: 0x2a34018 VA: 0x759504c018
	public Void set_onCharItemClicked(Action`1 value) { }
	// RVA: 0x2a35df8 VA: 0x759504ddf8
	public Action get_onConfirmClick() { }
	// RVA: 0x2a3409c VA: 0x759504c09c
	public Void set_onConfirmClick(Action value) { }
	// RVA: 0x2a35e60 VA: 0x759504de60
	private Void _InitIfNot() { }
	// RVA: 0x2a36184 VA: 0x759504e184
	private Void _RenderSelectingPart(RoguelikeExpeditionModel model) { }
	// RVA: 0x2a362ac VA: 0x759504e2ac
	private Void _FadeSelectingPart(Boolean isSelecting, Boolean isFastMode) { }
	// RVA: 0x2a36380 VA: 0x759504e380
	public override Void OnValueChanged(RoguelikeExpeditionModelProperty property) { }
	// RVA: 0x2a34120 VA: 0x759504c120
	public Void ResetListToTop() { }
	// RVA: 0x2a36514 VA: 0x759504e514
	private Void _OnCharItemClick(String charId) { }
	// RVA: 0x2a365cc VA: 0x759504e5cc
	public Void OnConfirmClick() { }
	// RVA: 0x2a36668 VA: 0x759504e668
	public Void .ctor() { }
}
```