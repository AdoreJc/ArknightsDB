# RoguelikeFocusView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeNodeViewData _viewData`

- `UIColorGraphic _colorGraphic`

- `Image _imageIcon`

- `RectTransform _panelBattleTitle`

- `RectTransform _panelNonBattleTitle`

- `RectTransform _panelEliteDesc`

- `RectTransform _panelBattleInfo`

- `Text _textNonBattleTitle`

- `Text _textBattleTitle`

- `Text _textBattleName`

- `Text _textDesc`

- `Text _textEliteDesc`

- `RectTransform _panelMapPreview`

- `Image _imageMapPreivewBlur`

- `Image _imageMapPreview`

- `Image _imageMapPreviewMini`

- `GameObject _haveCapsule`

- `Text _capsuleName`

- `GameObject _canGoToBtn`

- `GameObject _effectPrefab`

- `Action <onEnemyClick>k__BackingField`

- `Action <onConfirmClick>k__BackingField`

- `Action <onRollNodeClick>k__BackingField`

- `String <cacheStageId>k__BackingField`

- `GameObject effectInst`

- `RoguelikeFocusViewModel m_cacheModel`


## Properties

- `Action onEnemyClick`

- `Action onConfirmClick`

- `Action onRollNodeClick`

- `String cacheStageId`

- `RoguelikeNodeViewData viewData`

- `RectTransform panelEliteDesc`

- `GameObject canGoToBtn`

- `GameObject effectPrefab`

- `Image imageIcon`

- `UIColorGraphic colorGraphic`

- `RectTransform panelBattleTitle`

- `RectTransform panelNonBattleTitle`

- `RectTransform panelBattleInfo`

- `Text textNonBattleTitle`

- `Text textBattleTitle`

- `Text textDesc`


## Methods

- `Action get_onEnemyClick()`

- `Void set_onEnemyClick(Action)`

- `Action get_onConfirmClick()`

- `Void set_onConfirmClick(Action)`

- `Action get_onRollNodeClick()`

- `Void set_onRollNodeClick(Action)`

- `String get_cacheStageId()`

- `Void set_cacheStageId(String)`

- `RoguelikeNodeViewData get_viewData()`

- `RectTransform get_panelEliteDesc()`

- `GameObject get_canGoToBtn()`

- `GameObject get_effectPrefab()`

- `Void InitClosure(UIPage)`

- `Void ShowMapPreview()`

- `Void HideMapPreview()`

- `Void OnFocus()`

- `Void OnEnemy()`

- `Void OnRoll()`

- `Void RenderFocusNode()`

- `Void RenderStage()`

- `Void RenderImpl(String, RoguelikeEventType, String, PlayerNodeForesightType)`

- `Void LoadPreviewMap(String)`

- `Void _UnloadPreviewMap()`

- `Void _ShotBlurredSprite()`

- `Void _ClearBlurSprite()`

- `Void OnDestroy()`

- `Image get_imageIcon()`

- `UIColorGraphic get_colorGraphic()`

- `RectTransform get_panelBattleTitle()`

- `RectTransform get_panelNonBattleTitle()`

- `RectTransform get_panelBattleInfo()`

- `Text get_textNonBattleTitle()`

- `Text get_textBattleTitle()`

- `Text get_textDesc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFocusView : DataBinder`1
{
	private RoguelikeNodeViewData _viewData; // 0x20
	private UIColorGraphic _colorGraphic; // 0x28
	private Image _imageIcon; // 0x30
	private RectTransform _panelBattleTitle; // 0x38
	private RectTransform _panelNonBattleTitle; // 0x40
	private RectTransform _panelEliteDesc; // 0x48
	private RectTransform _panelBattleInfo; // 0x50
	private Text _textNonBattleTitle; // 0x58
	private Text _textBattleTitle; // 0x60
	private Text _textBattleName; // 0x68
	private Text _textDesc; // 0x70
	private Text _textEliteDesc; // 0x78
	private RectTransform _panelMapPreview; // 0x80
	private Image _imageMapPreivewBlur; // 0x88
	private Image _imageMapPreview; // 0x90
	private Image _imageMapPreviewMini; // 0x98
	private GameObject _haveCapsule; // 0xa0
	private Text _capsuleName; // 0xa8
	private GameObject _canGoToBtn; // 0xb0
	private GameObject _effectPrefab; // 0xb8
	private List`1 _pluginList; // 0xc0
	private Action <onEnemyClick>k__BackingField; // 0xc8
	private Action <onConfirmClick>k__BackingField; // 0xd0
	private Action <onRollNodeClick>k__BackingField; // 0xd8
	private String <cacheStageId>k__BackingField; // 0xe0
	public GameObject effectInst; // 0xe8
	private RoguelikeFocusViewModel m_cacheModel; // 0xf0
	private static DelegateBridge __Hotfix0_get_onEnemyClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onEnemyClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onConfirmClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onRollNodeClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onRollNodeClick; // 0x28
	private static DelegateBridge __Hotfix0_get_cacheStageId; // 0x30
	private static DelegateBridge __Hotfix0_set_cacheStageId; // 0x38
	private static DelegateBridge __Hotfix0_get_viewData; // 0x40
	private static DelegateBridge __Hotfix0_get_panelEliteDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_canGoToBtn; // 0x50
	private static DelegateBridge __Hotfix0_get_effectPrefab; // 0x58
	private static DelegateBridge __Hotfix0_InitClosure; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x68
	private static DelegateBridge __Hotfix0_ShowMapPreview; // 0x70
	private static DelegateBridge __Hotfix0_HideMapPreview; // 0x78
	private static DelegateBridge __Hotfix0_OnFocus; // 0x80
	private static DelegateBridge __Hotfix0_OnEnemy; // 0x88
	private static DelegateBridge __Hotfix0_OnRoll; // 0x90
	private static DelegateBridge __Hotfix0_RenderFocusNode; // 0x98
	private static DelegateBridge __Hotfix0_RenderStage; // 0xa0
	private static DelegateBridge __Hotfix0_RenderImpl; // 0xa8
	private static DelegateBridge __Hotfix0_LoadPreviewMap; // 0xb0
	private static DelegateBridge __Hotfix0__UnloadPreviewMap; // 0xb8
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0xc0
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0xc8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xd0
	private static DelegateBridge __Hotfix0_get_imageIcon; // 0xd8
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0xe0
	private static DelegateBridge __Hotfix0_get_panelBattleTitle; // 0xe8
	private static DelegateBridge __Hotfix0_get_panelNonBattleTitle; // 0xf0
	private static DelegateBridge __Hotfix0_get_panelBattleInfo; // 0xf8
	private static DelegateBridge __Hotfix0_get_textNonBattleTitle; // 0x100
	private static DelegateBridge __Hotfix0_get_textBattleTitle; // 0x108
	private static DelegateBridge __Hotfix0_get_textDesc; // 0x110
	private static DelegateBridge _c__Hotfix0_ctor; // 0x118

	private Action onEnemyClick { get; set; }
	private Action onConfirmClick { get; set; }
	private Action onRollNodeClick { get; set; }
	public String cacheStageId { get; set; }
	public RoguelikeNodeViewData viewData { get; }
	public RectTransform panelEliteDesc { get; }
	public GameObject canGoToBtn { get; }
	public GameObject effectPrefab { get; }
	public Image imageIcon { get; }
	public UIColorGraphic colorGraphic { get; }
	public RectTransform panelBattleTitle { get; }
	public RectTransform panelNonBattleTitle { get; }
	public RectTransform panelBattleInfo { get; }
	public Text textNonBattleTitle { get; }
	public Text textBattleTitle { get; }
	public Text textDesc { get; }

	// RVA: 0x2a1482c VA: 0x759502c82c
	private Action get_onEnemyClick() { }
	// RVA: 0x2a14894 VA: 0x759502c894
	public Void set_onEnemyClick(Action value) { }
	// RVA: 0x2a14918 VA: 0x759502c918
	private Action get_onConfirmClick() { }
	// RVA: 0x2a14980 VA: 0x759502c980
	public Void set_onConfirmClick(Action value) { }
	// RVA: 0x2a14a04 VA: 0x759502ca04
	private Action get_onRollNodeClick() { }
	// RVA: 0x2a14a6c VA: 0x759502ca6c
	public Void set_onRollNodeClick(Action value) { }
	// RVA: 0x2a14af0 VA: 0x759502caf0
	public String get_cacheStageId() { }
	// RVA: 0x2a14b58 VA: 0x759502cb58
	private Void set_cacheStageId(String value) { }
	// RVA: 0x2a14bdc VA: 0x759502cbdc
	public RoguelikeNodeViewData get_viewData() { }
	// RVA: 0x2a14c44 VA: 0x759502cc44
	public RectTransform get_panelEliteDesc() { }
	// RVA: 0x2a14cac VA: 0x759502ccac
	public GameObject get_canGoToBtn() { }
	// RVA: 0x2a14d14 VA: 0x759502cd14
	public GameObject get_effectPrefab() { }
	// RVA: 0x2a14d7c VA: 0x759502cd7c
	public Void InitClosure(UIPage page) { }
	// RVA: 0x2a14edc VA: 0x759502cedc
	public override Void OnValueChanged(RoguelikeFocusViewProperty property) { }
	// RVA: 0x2a152f8 VA: 0x759502d2f8
	public Void ShowMapPreview() { }
	// RVA: 0x2a15494 VA: 0x759502d494
	public Void HideMapPreview() { }
	// RVA: 0x2a15620 VA: 0x759502d620
	public Void OnFocus() { }
	// RVA: 0x2a156bc VA: 0x759502d6bc
	public Void OnEnemy() { }
	// RVA: 0x2a15758 VA: 0x759502d758
	public Void OnRoll() { }
	// RVA: 0x2a15248 VA: 0x759502d248
	public Void RenderFocusNode() { }
	// RVA: 0x2a151a4 VA: 0x759502d1a4
	public Void RenderStage() { }
	// RVA: 0x2a157f4 VA: 0x759502d7f4
	public Void RenderImpl(String topicId, RoguelikeEventType type, String stageId, PlayerNodeForesightType forsightType) { }
	// RVA: 0x2a15cf8 VA: 0x759502dcf8
	public Void LoadPreviewMap(String stageId) { }
	// RVA: 0x2a15e74 VA: 0x759502de74
	private Void _UnloadPreviewMap() { }
	// RVA: 0x2a15420 VA: 0x759502d420
	private Void _ShotBlurredSprite() { }
	// RVA: 0x2a1551c VA: 0x759502d51c
	private Void _ClearBlurSprite() { }
	// RVA: 0x2a15f10 VA: 0x759502df10
	public Void OnDestroy() { }
	// RVA: 0x2a15f78 VA: 0x759502df78
	public Image get_imageIcon() { }
	// RVA: 0x2a15fe0 VA: 0x759502dfe0
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2a16048 VA: 0x759502e048
	public RectTransform get_panelBattleTitle() { }
	// RVA: 0x2a160b0 VA: 0x759502e0b0
	public RectTransform get_panelNonBattleTitle() { }
	// RVA: 0x2a16118 VA: 0x759502e118
	public RectTransform get_panelBattleInfo() { }
	// RVA: 0x2a16180 VA: 0x759502e180
	public Text get_textNonBattleTitle() { }
	// RVA: 0x2a161e8 VA: 0x759502e1e8
	public Text get_textBattleTitle() { }
	// RVA: 0x2a16250 VA: 0x759502e250
	public Text get_textDesc() { }
	// RVA: 0x2a162b8 VA: 0x759502e2b8
	public Void .ctor() { }
}
```