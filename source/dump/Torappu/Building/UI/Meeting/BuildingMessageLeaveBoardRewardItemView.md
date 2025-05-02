# BuildingMessageLeaveBoardRewardItemView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Text _textRewardNum`

- `Button _btnGetReward`

- `RectTransform _itemCardContainer`

- `GameObject _panelCanGetRewardFx`

- `GameObject _panelGetReward`

- `UIItemViewModel m_itemViewModel`

- `Boolean m_isinited`

- `UIItemCard m_itemCard`


## Methods

- `Void _InitIfNot()`

- `Void ShowView()`

- `Void HideView()`

- `Boolean _GetCanGetReward()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMessageLeaveBoardRewardItemView : DataBinder`1, IHotfixable
{
	private Text _textRewardNum; // 0x20
	private Button _btnGetReward; // 0x28
	private RectTransform _itemCardContainer; // 0x30
	private GameObject _panelCanGetRewardFx; // 0x38
	private GameObject _panelGetReward; // 0x40
	private UIItemViewModel m_itemViewModel; // 0x48
	private Boolean m_isinited; // 0x50
	private UIItemCard m_itemCard; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_ShowView; // 0x10
	private static DelegateBridge __Hotfix0_HideView; // 0x18
	private static DelegateBridge __Hotfix0__GetCanGetReward; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3dc7bc8 VA: 0x75963dfbc8
	private Void _InitIfNot() { }
	// RVA: 0x3dc7d40 VA: 0x75963dfd40
	public override Void OnValueChanged(BuildingMessageLeaveBoardProperty property) { }
	// RVA: 0x3dc3fa0 VA: 0x75963dbfa0
	public Void ShowView() { }
	// RVA: 0x3dc4018 VA: 0x75963dc018
	public Void HideView() { }
	// RVA: 0x3dc7f68 VA: 0x75963dff68
	private Boolean _GetCanGetReward() { }
	// RVA: 0x3dc7fd8 VA: 0x75963dffd8
	public Void .ctor() { }
}
```