# HandBookV2MissionItemView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Image _imgForceIcon`

- `Text _textForceName`

- `Text _textTotalFavorPoint`

- `Text _textAvgFavorPoint`

- `SimpleLayoutContent _charListContent`

- `GameObject _normalBgGo`

- `GameObject _availBgGo`

- `GameObject _alreadyGetGo`

- `Text _textDesc`

- `Transform _itemContainer`

- `Single _itemScale`

- `Boolean m_hasInited`

- `HandBookV2MissionListItemModel m_missionItemModel`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `Adapter m_adapter`

- `UIStringEvent m_onBtnGetClick`


## Properties

- `UIStringEvent onBtnGetClick`


## Methods

- `Void set_onBtnGetClick(UIStringEvent)`

- `Void OnBtnGetClick()`

- `Void Render(HandBookV2MissionListItemModel)`

- `Void _OnClickItemButton(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MissionItemView : MonoBehaviour, IHotfixable
{
	private Image _imgForceIcon; // 0x18
	private Text _textForceName; // 0x20
	private Text _textTotalFavorPoint; // 0x28
	private Text _textAvgFavorPoint; // 0x30
	private SimpleLayoutContent _charListContent; // 0x38
	private GameObject _normalBgGo; // 0x40
	private GameObject _availBgGo; // 0x48
	private GameObject _alreadyGetGo; // 0x50
	private Text _textDesc; // 0x58
	private Transform _itemContainer; // 0x60
	private Single _itemScale; // 0x68
	private Boolean m_hasInited; // 0x6c
	private HandBookV2MissionListItemModel m_missionItemModel; // 0x70
	private UIItemCard m_itemCard; // 0x78
	private UIItemViewModel m_itemModel; // 0x80
	private Adapter m_adapter; // 0x88
	private UIStringEvent m_onBtnGetClick; // 0x90
	private static DelegateBridge __Hotfix0_set_onBtnGetClick; // 0x0
	private static DelegateBridge __Hotfix0_OnBtnGetClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__OnClickItemButton; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UIStringEvent onBtnGetClick { set; }

	// RVA: 0x2ed8c50 VA: 0x75954f0c50
	public Void set_onBtnGetClick(UIStringEvent value) { }
	// RVA: 0x2ed8cd4 VA: 0x75954f0cd4
	public Void OnBtnGetClick() { }
	// RVA: 0x2ed8d74 VA: 0x75954f0d74
	public Void Render(HandBookV2MissionListItemModel missionItemModel) { }
	// RVA: 0x2ed9444 VA: 0x75954f1444
	private Void _OnClickItemButton(Int32 index) { }
	// RVA: 0x2ed92e8 VA: 0x75954f12e8
	private Void _InitIfNot() { }
	// RVA: 0x2ed9554 VA: 0x75954f1554
	public Void .ctor() { }
}
```