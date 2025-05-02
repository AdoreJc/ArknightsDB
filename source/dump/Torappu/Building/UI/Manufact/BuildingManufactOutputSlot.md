# BuildingManufactOutputSlot

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `GameObject _panelStop`

- `GameObject _panelFinish`

- `GameObject _panelAdd`

- `GameObject _panelItemInfo`

- `GameObject _panelWorking`

- `Text _textName`

- `Text _textWeight`

- `Text _textTime`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `Boolean m_isInited`

- `CountDownTask m_countDown`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemViewModel`

- `MRoomViewModel m_viewModelCache`

- `Action onEditFormula`


## Methods

- `Void _Init(MRoomViewModel)`

- `Void _RenderNormal(MRoomViewModel)`

- `Void _RenderEdit(MRoomViewModel)`

- `Void _RenderItemInfo(ManufactFormula, Int32)`

- `Void _UpdateCountDown(MRoomViewModel, ManufactSnapshot)`

- `Void _UpdateSecond(TickValue)`

- `Void EventOnPanelClick()`

- `Void Update()`

- `Void <_UpdateCountDown>b__21_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactOutputSlot : DataBinder`1
{
	private GameObject _panelStop; // 0x20
	private GameObject _panelFinish; // 0x28
	private GameObject _panelAdd; // 0x30
	private GameObject _panelItemInfo; // 0x38
	private GameObject _panelWorking; // 0x40
	private Text _textName; // 0x48
	private Text _textWeight; // 0x50
	private Text _textTime; // 0x58
	private RectTransform _itemContainer; // 0x60
	private Single _itemScale; // 0x68
	private Boolean m_isInited; // 0x6c
	private CountDownTask m_countDown; // 0x70
	private UIItemCard m_itemCard; // 0x78
	private UIItemViewModel m_itemViewModel; // 0x80
	private MRoomViewModel m_viewModelCache; // 0x88
	public Action onEditFormula; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Init; // 0x8
	private static DelegateBridge __Hotfix0__RenderNormal; // 0x10
	private static DelegateBridge __Hotfix0__RenderEdit; // 0x18
	private static DelegateBridge __Hotfix0__RenderItemInfo; // 0x20
	private static DelegateBridge __Hotfix0__UpdateCountDown; // 0x28
	private static DelegateBridge __Hotfix0__UpdateSecond; // 0x30
	private static DelegateBridge __Hotfix0_EventOnPanelClick; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3e0c0bc VA: 0x75964240bc
	public override Void OnValueChanged(MRoomViewPropety property) { }
	// RVA: 0x3e0c1bc VA: 0x75964241bc
	private Void _Init(MRoomViewModel viewModel) { }
	// RVA: 0x3e0c498 VA: 0x7596424498
	private Void _RenderNormal(MRoomViewModel viewModel) { }
	// RVA: 0x3e0c334 VA: 0x7596424334
	private Void _RenderEdit(MRoomViewModel viewModel) { }
	// RVA: 0x3e0c65c VA: 0x759642465c
	private Void _RenderItemInfo(ManufactFormula formula, Int32 remainCount) { }
	// RVA: 0x3e0c7b0 VA: 0x75964247b0
	private Void _UpdateCountDown(MRoomViewModel viewModel, ManufactSnapshot snapshot) { }
	// RVA: 0x3e0c9ac VA: 0x75964249ac
	private Void _UpdateSecond(TickValue value) { }
	// RVA: 0x3e0cb14 VA: 0x7596424b14
	public Void EventOnPanelClick() { }
	// RVA: 0x3e0cb98 VA: 0x7596424b98
	private Void Update() { }
	// RVA: 0x3e0cc14 VA: 0x7596424c14
	public Void .ctor() { }
	// RVA: 0x3e0cce4 VA: 0x7596424ce4
	private Void <_UpdateCountDown>b__21_0() { }
}
```