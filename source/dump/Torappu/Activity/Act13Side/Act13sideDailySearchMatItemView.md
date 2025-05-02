# Act13sideDailySearchMatItemView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _selectedBgGo`

- `GameObject _normalBgGo`

- `Image _imgItem`

- `String m_cacheItemId`

- `ItemBundle m_matData`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Act13sideDailySearchViewModel, ItemBundle)`

- `Void _UpdateIconIfNeed(ItemBundle)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailySearchMatItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectedBgGo; // 0x18
	private GameObject _normalBgGo; // 0x20
	private Image _imgItem; // 0x28
	private Action`1 <onItemClick>k__BackingField; // 0x30
	private String m_cacheItemId; // 0x38
	private ItemBundle m_matData; // 0x40
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateIconIfNeed; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClick { get; set; }

	// RVA: 0x3440bd0 VA: 0x7595a58bd0
	private Action`1 get_onItemClick() { }
	// RVA: 0x3440254 VA: 0x7595a58254
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x34402d8 VA: 0x7595a582d8
	public Void Render(Act13sideDailySearchViewModel searchModel, ItemBundle matData) { }
	// RVA: 0x3440c38 VA: 0x7595a58c38
	private Void _UpdateIconIfNeed(ItemBundle matData) { }
	// RVA: 0x3440d90 VA: 0x7595a58d90
	public Void OnItemClick() { }
	// RVA: 0x3440e30 VA: 0x7595a58e30
	public Void .ctor() { }
}
```