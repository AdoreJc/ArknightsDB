# SiracusaCharCardView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _emptyView`

- `GameObject _equipView`

- `GameObject _completeView`

- `TwoStateToggle _btnInventToggle`

- `GameObject _btnSwitchGo`

- `UIAtlasImage _imgChar`

- `UIDynImage _imgItem`

- `SimpleLayoutContent _taskRingList`

- `UIAtlasObject _charCardAtlas`

- `Text _textCurrentTask`

- `Single _bubbleDuration`

- `CanvasGroup _bubbleCanvasGroup`

- `CanvasGroup _taskDialogCanvasGroup`

- `CanvasGroup _cardViewCanvasGroup`

- `GameObject _newBagItemTrackPoint`

- `Boolean m_hasInited`

- `SiracusaCharCardModel m_charCardModel`

- `FadeSwitchTween m_cardViewTween`

- `FadeSwitchTween m_bubbleTween`

- `FadeSwitchTween m_taskDialogTween`

- `Adapter m_adapter`

- `AutoPackSpriteHub m_itemSpriteHub`

- `String m_cachedRingId`

- `Action <onBubbleShow>k__BackingField`

- `Action <onBagClick>k__BackingField`

- `Action <onChangeChar>k__BackingField`


## Properties

- `Action onBubbleShow`

- `Action onBagClick`

- `Action onChangeChar`


## Methods

- `Action get_onBubbleShow()`

- `Void set_onBubbleShow(Action)`

- `Void set_onSelectRing(Action`1)`

- `Void set_onTaskClick(Action`2)`

- `Action get_onBagClick()`

- `Void set_onBagClick(Action)`

- `Action get_onChangeChar()`

- `Void set_onChangeChar(Action)`

- `Void _ShowBubbleOfNewTaskRing(Boolean)`

- `Void _SetCharCardVisible(Boolean)`

- `Boolean TryShowBubble()`

- `IEnumerator HideBubbleAfterDelay()`

- `Void _InitIfNot()`

- `Void _RenderEquipView(SiracusaCharCardModel, Boolean)`

- `String _GetItemIconPath(ItemInfoData)`

- `Void _SetThemeColor(Color)`

- `Void Init(AutoPackSpriteHub)`

- `Void EventOnShowBubble()`

- `Void EventOnOpenBag()`

- `Void EventOnChangeChar()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharCardView : DataBinder`1
{
	private GameObject _emptyView; // 0x20
	private GameObject _equipView; // 0x28
	private GameObject _completeView; // 0x30
	private TwoStateToggle _btnInventToggle; // 0x38
	private UIAtlasImage[] _imgThemeList; // 0x40
	private GameObject _btnSwitchGo; // 0x48
	private UIAtlasImage _imgChar; // 0x50
	private UIDynImage _imgItem; // 0x58
	private SimpleLayoutContent _taskRingList; // 0x60
	private UIAtlasObject _charCardAtlas; // 0x68
	private Text _textCurrentTask; // 0x70
	private Single _bubbleDuration; // 0x78
	private CanvasGroup _bubbleCanvasGroup; // 0x80
	private CanvasGroup _taskDialogCanvasGroup; // 0x88
	private CanvasGroup _cardViewCanvasGroup; // 0x90
	private GameObject[] _newCharCardTrackPoints; // 0x98
	private GameObject _newBagItemTrackPoint; // 0xa0
	private Boolean m_hasInited; // 0xa8
	private SiracusaCharCardModel m_charCardModel; // 0xb0
	private FadeSwitchTween m_cardViewTween; // 0xb8
	private FadeSwitchTween m_bubbleTween; // 0xc0
	private FadeSwitchTween m_taskDialogTween; // 0xc8
	private Adapter m_adapter; // 0xd0
	private AutoPackSpriteHub m_itemSpriteHub; // 0xd8
	private String m_cachedRingId; // 0xe0
	private Action <onBubbleShow>k__BackingField; // 0xe8
	private Action`1 <onSelectRing>k__BackingField; // 0xf0
	private Action`2 <onTaskClick>k__BackingField; // 0xf8
	private Action <onBagClick>k__BackingField; // 0x100
	private Action <onChangeChar>k__BackingField; // 0x108
	private static DelegateBridge __Hotfix0_get_onBubbleShow; // 0x0
	private static DelegateBridge __Hotfix0_set_onBubbleShow; // 0x8
	private static DelegateBridge __Hotfix0_get_onSelectRing; // 0x10
	private static DelegateBridge __Hotfix0_set_onSelectRing; // 0x18
	private static DelegateBridge __Hotfix0_get_onTaskClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onTaskClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onBagClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onBagClick; // 0x38
	private static DelegateBridge __Hotfix0_get_onChangeChar; // 0x40
	private static DelegateBridge __Hotfix0_set_onChangeChar; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__ShowBubbleOfNewTaskRing; // 0x58
	private static DelegateBridge __Hotfix0__SetCharCardVisible; // 0x60
	private static DelegateBridge __Hotfix0_TryShowBubble; // 0x68
	private static DelegateBridge __Hotfix0_HideBubbleAfterDelay; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__RenderEquipView; // 0x80
	private static DelegateBridge __Hotfix0__GetItemIconPath; // 0x88
	private static DelegateBridge __Hotfix0__SetThemeColor; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x98
	private static DelegateBridge __Hotfix0_EventOnShowBubble; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnOpenBag; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnChangeChar; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	private Action onBubbleShow { get; set; }
	private Action`1 onSelectRing { get; set; }
	private Action`2 onTaskClick { get; set; }
	private Action onBagClick { get; set; }
	private Action onChangeChar { get; set; }

	// RVA: 0x23e7840 VA: 0x75949ff840
	private Action get_onBubbleShow() { }
	// RVA: 0x23e78a8 VA: 0x75949ff8a8
	public Void set_onBubbleShow(Action value) { }
	// RVA: 0x23e792c VA: 0x75949ff92c
	private Action`1 get_onSelectRing() { }
	// RVA: 0x23e7994 VA: 0x75949ff994
	public Void set_onSelectRing(Action`1 value) { }
	// RVA: 0x23e7a18 VA: 0x75949ffa18
	private Action`2 get_onTaskClick() { }
	// RVA: 0x23e7a80 VA: 0x75949ffa80
	public Void set_onTaskClick(Action`2 value) { }
	// RVA: 0x23e7b04 VA: 0x75949ffb04
	private Action get_onBagClick() { }
	// RVA: 0x23e7b6c VA: 0x75949ffb6c
	public Void set_onBagClick(Action value) { }
	// RVA: 0x23e7bf0 VA: 0x75949ffbf0
	private Action get_onChangeChar() { }
	// RVA: 0x23e7c58 VA: 0x75949ffc58
	public Void set_onChangeChar(Action value) { }
	// RVA: 0x23e7cdc VA: 0x75949ffcdc
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23e8488 VA: 0x7594a00488
	private Void _ShowBubbleOfNewTaskRing(Boolean isInSmallMap) { }
	// RVA: 0x23e821c VA: 0x7594a0021c
	private Void _SetCharCardVisible(Boolean isVisible) { }
	// RVA: 0x23e85a0 VA: 0x7594a005a0
	public Boolean TryShowBubble() { }
	// RVA: 0x23e8640 VA: 0x7594a00640
	public IEnumerator HideBubbleAfterDelay() { }
	// RVA: 0x23e801c VA: 0x7594a0001c
	private Void _InitIfNot() { }
	// RVA: 0x23e82a8 VA: 0x7594a002a8
	private Void _RenderEquipView(SiracusaCharCardModel charCardModel, Boolean isInSmallMapState) { }
	// RVA: 0x23e8850 VA: 0x7594a00850
	private String _GetItemIconPath(ItemInfoData bagItemInfoData) { }
	// RVA: 0x23e86ec VA: 0x7594a006ec
	private Void _SetThemeColor(Color themeColor) { }
	// RVA: 0x23e893c VA: 0x7594a0093c
	public Void Init(AutoPackSpriteHub itemSpriteHub) { }
	// RVA: 0x23e89c0 VA: 0x7594a009c0
	public Void EventOnShowBubble() { }
	// RVA: 0x23e8a5c VA: 0x7594a00a5c
	public Void EventOnOpenBag() { }
	// RVA: 0x23e8af8 VA: 0x7594a00af8
	public Void EventOnChangeChar() { }
	// RVA: 0x23e8b94 VA: 0x7594a00b94
	public Void .ctor() { }
}
```