# ItemRepoItemCardGridView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `SimpleLayoutAdapter m_adapter`


## Properties

- `SimpleLayoutAdapter adapter`


## Methods

- `SimpleLayoutAdapter get_adapter()`

- `Void set_adapter(SimpleLayoutAdapter)`

- `Void _ObserveAdapter(SimpleLayoutAdapter)`

- `Void _UpdateViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoItemCardGridView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutAdapter m_adapter; // 0x18
	private static DelegateBridge __Hotfix0_get_adapter; // 0x0
	private static DelegateBridge __Hotfix0_set_adapter; // 0x8
	private static DelegateBridge __Hotfix0__ObserveAdapter; // 0x10
	private static DelegateBridge __Hotfix0__UpdateViews; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public SimpleLayoutAdapter adapter { get; set; }

	// RVA: 0x2d2f6cc VA: 0x75953476cc
	public SimpleLayoutAdapter get_adapter() { }
	// RVA: 0x2d2f734 VA: 0x7595347734
	public Void set_adapter(SimpleLayoutAdapter value) { }
	// RVA: 0x2d2f9e0 VA: 0x75953479e0
	private Void _ObserveAdapter(SimpleLayoutAdapter adapter) { }
	// RVA: 0x2d2f850 VA: 0x7595347850
	private Void _UpdateViews() { }
	// RVA: 0x2d2fa78 VA: 0x7595347a78
	public Void .ctor() { }
}
```