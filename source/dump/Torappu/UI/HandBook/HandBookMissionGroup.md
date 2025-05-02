# HandBookMissionGroup

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookMissionItem _item`

- `Transform _itemContainer`

- `Image _teamImage`

- `Text _favorPoint`

- `Text _favorPercent`

- `Text _teamName`

- `GameObject _cannotGet`

- `GameObject _alreadyGet`

- `GameObject _canGet`

- `Transform _itemContainerAlreadyGet`

- `Transform _itemContainerCanGet`

- `Text _getTextGet`

- `Text _ungetTextGet`

- `Single _itemScale`

- `UIStringEvent clickEvent`

- `String m_cacheId`

- `UIItemViewModel m_cacheViewModel`

- `UIItemCard m_itemCard`


## Methods

- `Void OnClick()`

- `Void _OnClickButton(Int32)`

- `Void Render(HandBookMissionViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookMissionGroup : MonoBehaviour
{
	private HandBookMissionItem _item; // 0x18
	private Transform _itemContainer; // 0x20
	private Image _teamImage; // 0x28
	private Text _favorPoint; // 0x30
	private Text _favorPercent; // 0x38
	private Text _teamName; // 0x40
	private GameObject _cannotGet; // 0x48
	private GameObject _alreadyGet; // 0x50
	private GameObject _canGet; // 0x58
	private Transform _itemContainerAlreadyGet; // 0x60
	private Transform _itemContainerCanGet; // 0x68
	private Text _getTextGet; // 0x70
	private Text _ungetTextGet; // 0x78
	private Single _itemScale; // 0x80
	public UIStringEvent clickEvent; // 0x88
	private String m_cacheId; // 0x90
	private UIItemViewModel m_cacheViewModel; // 0x98
	private UIItemCard m_itemCard; // 0xa0


	// RVA: 0x2e9cecc VA: 0x75954b4ecc
	public Void OnClick() { }
	// RVA: 0x2e9cf28 VA: 0x75954b4f28
	private Void _OnClickButton(Int32 index) { }
	// RVA: 0x2e9cf60 VA: 0x75954b4f60
	public Void Render(HandBookMissionViewModel viewModel) { }
	// RVA: 0x2e9d758 VA: 0x75954b5758
	public Void .ctor() { }
}
```