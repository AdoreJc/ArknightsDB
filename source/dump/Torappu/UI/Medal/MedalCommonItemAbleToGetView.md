# MedalCommonItemAbleToGetView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _iconImage`

- `Text _itemName`

- `Transform _itemContainer`

- `Single _scaler`

- `Text _medalName`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`


## Methods

- `Void _InitIfNot()`

- `Void Render(MedalCommonViewModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalCommonItemAbleToGetView : MonoBehaviour, IHotfixable
{
	private Image _iconImage; // 0x18
	private Text _itemName; // 0x20
	private Transform _itemContainer; // 0x28
	private Single _scaler; // 0x30
	private Text _medalName; // 0x38
	private Boolean m_isInited; // 0x40
	private UIItemCard m_itemCard; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2798680 VA: 0x7594db0680
	private Void _InitIfNot() { }
	// RVA: 0x2798814 VA: 0x7594db0814
	public Void Render(MedalCommonViewModel viewModel, String pageName) { }
	// RVA: 0x2798b48 VA: 0x7594db0b48
	public Void .ctor() { }
}
```