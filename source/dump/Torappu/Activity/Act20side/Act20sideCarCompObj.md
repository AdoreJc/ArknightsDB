# Act20sideCarCompObj

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _equipName`

- `CartAccessoryPos _pos`

- `Image _iconSprite`

- `GameObject _emptyState`

- `GameObject _unEmptyState`


## Properties

- `CartAccessoryPos pos`


## Methods

- `CartAccessoryPos get_pos()`

- `Void OnRender(CartCompViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarCompObj : MonoBehaviour, IHotfixable
{
	private Text _equipName; // 0x18
	private CartAccessoryPos _pos; // 0x20
	private Image _iconSprite; // 0x28
	private GameObject _emptyState; // 0x30
	private GameObject _unEmptyState; // 0x38
	private static DelegateBridge __Hotfix0_get_pos; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public CartAccessoryPos pos { get; }

	// RVA: 0x32ebf28 VA: 0x7595903f28
	public CartAccessoryPos get_pos() { }
	// RVA: 0x32ebf90 VA: 0x7595903f90
	public Void OnRender(CartCompViewModel viewModel) { }
	// RVA: 0x32ec0ac VA: 0x75959040ac
	public Void .ctor() { }
}
```