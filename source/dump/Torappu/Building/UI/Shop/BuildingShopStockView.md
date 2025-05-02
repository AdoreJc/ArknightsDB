# BuildingShopStockView

**Namespace:** `Torappu.Building.UI.Shop`


## Fields

- `Text _textName`

- `Text _textReserve`

- `Text _textRemain`

- `Text _textRemainInactive`

- `Text _textLimit`

- `StretchProgressBar _progressBar`

- `RectTransform _itemContainer`

- `UIItemCard _itemPrefab`

- `Single _itemScaler`

- `GameObject _panelActive`

- `GameObject _panelEmpty`

- `GameObject _panelLocked`

- `GameObject _panelChanged`

- `GameObject _panelStation`

- `GameObject _panelPause`

- `GameObject _panelFinish`

- `GameObject _panelUnlockCommon`

- `RectTransform _avatarContainer`

- `BuildingCharAvatar _avatarPrefab`

- `Text _textRemainTime`

- `UILongPressButton _btnPlus`

- `UILongPressButton _btnMinus`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `BuildingCharModel m_charModel`

- `BuildingCharAvatar m_charAvatar`

- `Int32 m_secsPerItem`

- `SStockViewModel m_cachedViewModel`

- `CountDownTask m_progressCountDown`

- `CountDownTask m_remainTimeCountDown`

- `Listeners listeners`


## Methods

- `Void _Init(SStockViewModel)`

- `Void _UpdateCountDowns(SStockViewModel, ShopStockSnapshot)`

- `Void _InvokeCountChanged(Int32)`

- `Void Start()`

- `Void OnDestroy()`

- `Void EventOnFormulaClicked()`

- `Void EventOnEditConfirmed()`

- `Void EventOnEditCancelled()`

- `Void UpdateTime(Single)`

- `Void _CountDownProgress(TickValue)`

- `Void _CountDownRemainTime(TickValue)`

- `Void _OnAvatarClicked(BuildingCharModel, Object)`

- `Void _OnPlusClicked()`

- `Void _OnMinusClicked()`

- `Boolean _OnPlusLongPressed()`

- `Boolean _OnMinusLongPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Shop
public class BuildingShopStockView : DataBinder`1, ITimeWatcher
{
	private const String INVALID_TIME; // 0x0
	private const Int32 LONG_PRESS_DELTA; // 0x0
	private Text _textName; // 0x20
	private Text _textReserve; // 0x28
	private Text _textRemain; // 0x30
	private Text _textRemainInactive; // 0x38
	private Text _textLimit; // 0x40
	private StretchProgressBar _progressBar; // 0x48
	private RectTransform _itemContainer; // 0x50
	private UIItemCard _itemPrefab; // 0x58
	private Single _itemScaler; // 0x60
	private GameObject _panelActive; // 0x68
	private GameObject _panelEmpty; // 0x70
	private GameObject _panelLocked; // 0x78
	private GameObject _panelChanged; // 0x80
	private GameObject _panelStation; // 0x88
	private GameObject _panelPause; // 0x90
	private GameObject _panelFinish; // 0x98
	private GameObject _panelUnlockCommon; // 0xa0
	private RectTransform _avatarContainer; // 0xa8
	private BuildingCharAvatar _avatarPrefab; // 0xb0
	private Text _textRemainTime; // 0xb8
	private UILongPressButton _btnPlus; // 0xc0
	private UILongPressButton _btnMinus; // 0xc8
	private RectTransform[] _autoLayouts; // 0xd0
	private Boolean m_isInited; // 0xd8
	private UIItemCard m_itemCard; // 0xe0
	private UIItemViewModel m_itemModel; // 0xe8
	private BuildingCharModel m_charModel; // 0xf0
	private BuildingCharAvatar m_charAvatar; // 0x160
	private Int32 m_secsPerItem; // 0x168
	private SStockViewModel m_cachedViewModel; // 0x170
	private CountDownTask m_progressCountDown; // 0x178
	private CountDownTask m_remainTimeCountDown; // 0x180
	public Listeners listeners; // 0x188
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__UpdateCountDowns; // 0x10
	private static DelegateBridge __Hotfix0__InvokeCountChanged; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_EventOnFormulaClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnEditConfirmed; // 0x38
	private static DelegateBridge __Hotfix0_EventOnEditCancelled; // 0x40
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x48
	private static DelegateBridge __Hotfix0__CountDownProgress; // 0x50
	private static DelegateBridge __Hotfix0__CountDownRemainTime; // 0x58
	private static DelegateBridge __Hotfix0__OnAvatarClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnPlusClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnMinusClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnPlusLongPressed; // 0x78
	private static DelegateBridge __Hotfix0__OnMinusLongPressed; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x3dc0844 VA: 0x75963d8844
	public override Void OnValueChanged(SStockViewProperty property) { }
	// RVA: 0x3dc0e3c VA: 0x75963d8e3c
	private Void _Init(SStockViewModel viewModel) { }
	// RVA: 0x3dc1184 VA: 0x75963d9184
	private Void _UpdateCountDowns(SStockViewModel viewModel, ShopStockSnapshot snapshot) { }
	// RVA: 0x3dc1710 VA: 0x75963d9710
	private Void _InvokeCountChanged(Int32 delta) { }
	// RVA: 0x3dc17b4 VA: 0x75963d97b4
	private Void Start() { }
	// RVA: 0x3dc1824 VA: 0x75963d9824
	private Void OnDestroy() { }
	// RVA: 0x3dc1894 VA: 0x75963d9894
	public Void EventOnFormulaClicked() { }
	// RVA: 0x3dc1928 VA: 0x75963d9928
	public Void EventOnEditConfirmed() { }
	// RVA: 0x3dc19b0 VA: 0x75963d99b0
	public Void EventOnEditCancelled() { }
	// RVA: 0x3dc1a38 VA: 0x75963d9a38
	public Void UpdateTime(Single timeDelta) { }
	// RVA: 0x3dc1490 VA: 0x75963d9490
	private Void _CountDownProgress(TickValue tick) { }
	// RVA: 0x3dc1540 VA: 0x75963d9540
	private Void _CountDownRemainTime(TickValue tick) { }
	// RVA: 0x3dc1adc VA: 0x75963d9adc
	private Void _OnAvatarClicked(BuildingCharModel model, Object param) { }
	// RVA: 0x3dc1b98 VA: 0x75963d9b98
	private Void _OnPlusClicked() { }
	// RVA: 0x3dc1c04 VA: 0x75963d9c04
	private Void _OnMinusClicked() { }
	// RVA: 0x3dc1c70 VA: 0x75963d9c70
	private Boolean _OnPlusLongPressed() { }
	// RVA: 0x3dc1ce4 VA: 0x75963d9ce4
	private Boolean _OnMinusLongPressed() { }
	// RVA: 0x3dc1d58 VA: 0x75963d9d58
	public Void .ctor() { }
}
```