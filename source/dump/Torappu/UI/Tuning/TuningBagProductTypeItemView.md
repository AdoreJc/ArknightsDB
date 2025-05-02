# TuningBagProductTypeItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `UIAtlasImage _bgImage`

- `UIAtlasImage _selectImage`

- `GameObject _nonSelectImageObj`

- `GameObject _frameObj`

- `Text _typeNameText`

- `Color _lockTextColor`

- `Color _nonSelectTextColor`

- `Color _selectTextColor`

- `Button _productTypeBtn`

- `String m_cachedProductTypeId`


## Methods

- `Void Render(TuningProductBagProductGroupModel)`

- `Void OnSelectProductType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningBagProductTypeItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _bgImage; // 0x18
	private UIAtlasImage _selectImage; // 0x20
	private GameObject _nonSelectImageObj; // 0x28
	private GameObject _frameObj; // 0x30
	private Text _typeNameText; // 0x38
	private Color _lockTextColor; // 0x40
	private Color _nonSelectTextColor; // 0x50
	private Color _selectTextColor; // 0x60
	private Button _productTypeBtn; // 0x70
	public Action`1 onSelectProductType; // 0x78
	private String m_cachedProductTypeId; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectProductType; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x233f740 VA: 0x7594957740
	public Void Render(TuningProductBagProductGroupModel groupModel) { }
	// RVA: 0x233fce8 VA: 0x7594957ce8
	public Void OnSelectProductType() { }
	// RVA: 0x233fd70 VA: 0x7594957d70
	public Void .ctor() { }
}
```