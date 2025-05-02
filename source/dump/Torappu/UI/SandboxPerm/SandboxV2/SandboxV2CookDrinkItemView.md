# SandboxV2CookDrinkItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCardPrefab`

- `Transform _itemCardHolder`

- `Single _itemCardScale`

- `Color _selectColor`

- `SandboxV2ItemCard m_itemCard`

- `Int32 m_cachedIndex`


## Methods

- `Void set_itemSelectEvent(Func`3)`

- `Void Render(Int32, SandboxV2CookDrinkItemModel)`

- `Void _InitIfNot()`

- `Void _OnAddEvent(Int32)`

- `Boolean _OnLongPressAddEvent(Int32)`

- `Void _OnMinusEvent(Int32)`

- `GameObject Tutorial_GetButtonGO()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDrinkItemView : MonoBehaviour, IHotfixable
{
	private const Int32 LONG_PRESS_STEP; // 0x0
	private SandboxV2ItemCard _itemCardPrefab; // 0x18
	private Transform _itemCardHolder; // 0x20
	private Single _itemCardScale; // 0x28
	private Color _selectColor; // 0x2c
	private SandboxV2ItemCard m_itemCard; // 0x40
	private Int32 m_cachedIndex; // 0x48
	private Func`3 <itemSelectEvent>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnAddEvent; // 0x20
	private static DelegateBridge __Hotfix0__OnLongPressAddEvent; // 0x28
	private static DelegateBridge __Hotfix0__OnMinusEvent; // 0x30
	private static DelegateBridge __Hotfix0_Tutorial_GetButtonGO; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Func`3 itemSelectEvent { get; set; }

	// RVA: 0x24c4710 VA: 0x7594adc710
	private Func`3 get_itemSelectEvent() { }
	// RVA: 0x24c4380 VA: 0x7594adc380
	public Void set_itemSelectEvent(Func`3 value) { }
	// RVA: 0x24c4404 VA: 0x7594adc404
	public Void Render(Int32 index, SandboxV2CookDrinkItemModel model) { }
	// RVA: 0x24c4778 VA: 0x7594adc778
	private Void _InitIfNot() { }
	// RVA: 0x24c4a40 VA: 0x7594adca40
	private Void _OnAddEvent(Int32 _) { }
	// RVA: 0x24c4afc VA: 0x7594adcafc
	private Boolean _OnLongPressAddEvent(Int32 _) { }
	// RVA: 0x24c4bb8 VA: 0x7594adcbb8
	private Void _OnMinusEvent(Int32 _) { }
	// RVA: 0x24c45fc VA: 0x7594adc5fc
	public GameObject Tutorial_GetButtonGO() { }
	// RVA: 0x24c4c74 VA: 0x7594adcc74
	public Void .ctor() { }
}
```