# UIItemDescFloatVoucherRelation

**Namespace:** `Torappu.UI`


## Fields

- `Text _voucherName`

- `Transform _remainTimeContainer`

- `UIItemTimeCountDown _remainTimePrefab`

- `Single _remainTimeScale`

- `ConsumableInfo m_consumableInfo`

- `ItemType m_cachedVoucherItemType`

- `VoucherRouteFocus m_cachedFocus`

- `Boolean m_hasInited`

- `UIItemTimeCountDown m_timeCountDown`


## Methods

- `Void set_onVoucherClicked(Action`3)`

- `Void _InitIfNot()`

- `Void Render(ConsumableInfo, ItemType, VoucherRouteFocus)`

- `Void OnVoucherRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloatVoucherRelation : MonoBehaviour, IHotfixable
{
	private Text _voucherName; // 0x18
	private Transform _remainTimeContainer; // 0x20
	private UIItemTimeCountDown _remainTimePrefab; // 0x28
	private Single _remainTimeScale; // 0x30
	private ConsumableInfo m_consumableInfo; // 0x38
	private ItemType m_cachedVoucherItemType; // 0x50
	private VoucherRouteFocus m_cachedFocus; // 0x58
	private Boolean m_hasInited; // 0x68
	private UIItemTimeCountDown m_timeCountDown; // 0x70
	private Action`3 <onVoucherClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onVoucherClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onVoucherClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnVoucherRouted; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`3 onVoucherClicked { get; set; }

	// RVA: 0x2192f20 VA: 0x75947aaf20
	private Action`3 get_onVoucherClicked() { }
	// RVA: 0x2192f88 VA: 0x75947aaf88
	public Void set_onVoucherClicked(Action`3 value) { }
	// RVA: 0x219300c VA: 0x75947ab00c
	private Void _InitIfNot() { }
	// RVA: 0x219310c VA: 0x75947ab10c
	public Void Render(ConsumableInfo consumableInfo, ItemType voucherItemType, VoucherRouteFocus focus) { }
	// RVA: 0x21932e4 VA: 0x75947ab2e4
	public Void OnVoucherRouted() { }
	// RVA: 0x21933c8 VA: 0x75947ab3c8
	public Void .ctor() { }
}
```