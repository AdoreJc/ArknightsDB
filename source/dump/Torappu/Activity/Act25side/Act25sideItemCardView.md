# Act25sideItemCardView

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `GameObject _panelGain`

- `Transform _itemCardContainer`

- `CanvasGroup _itemCanvasGroup`

- `Single _inactiveAlpha`

- `Single _scale`

- `Boolean m_isInited`

- `UIItemCard m_itemCard`

- `UIScaler m_scaler`

- `UIItemViewModel m_itemViewModel`


## Methods

- `Void Render(Int32, UIItemViewModel, Boolean)`

- `Void _OnItemClick(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideItemCardView : MonoBehaviour, IHotfixable
{
	private GameObject _panelGain; // 0x18
	private Transform _itemCardContainer; // 0x20
	private CanvasGroup _itemCanvasGroup; // 0x28
	private Single _inactiveAlpha; // 0x30
	private Single _scale; // 0x34
	private Boolean m_isInited; // 0x38
	private UIItemCard m_itemCard; // 0x40
	private UIScaler m_scaler; // 0x48
	private UIItemViewModel m_itemViewModel; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x327b664 VA: 0x7595893664
	public Void Render(Int32 index, UIItemViewModel itemViewModel, Boolean isGain) { }
	// RVA: 0x3281a68 VA: 0x7595899a68
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x32818dc VA: 0x75958998dc
	private Void _InitIfNot() { }
	// RVA: 0x3281b00 VA: 0x7595899b00
	public Void .ctor() { }
}
```