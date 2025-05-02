# ShopDetailItemView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _itemName`

- `Text _itemCount`

- `GameObject _panelSpecial`

- `GameObject _panelPreview`

- `Text _specialDesc`

- `Text _btnText`

- `UIStringEvent onPreviewClick`

- `UIItemViewModel m_cachedItemViewModel`


## Methods

- `Void Render(ItemBundle, SpecialItemInfo)`

- `Void Onclick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailItemView : MonoBehaviour, IHotfixable
{
	private Text _itemName; // 0x18
	private Text _itemCount; // 0x20
	private GameObject _panelSpecial; // 0x28
	private GameObject _panelPreview; // 0x30
	private Text _specialDesc; // 0x38
	private Text _btnText; // 0x40
	public UIStringEvent onPreviewClick; // 0x48
	private UIItemViewModel m_cachedItemViewModel; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Onclick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2439854 VA: 0x7594a51854
	public Void Render(ItemBundle item, SpecialItemInfo specialInfo) { }
	// RVA: 0x2439a80 VA: 0x7594a51a80
	public Void Onclick() { }
	// RVA: 0x2439b20 VA: 0x7594a51b20
	public Void .ctor() { }
}
```