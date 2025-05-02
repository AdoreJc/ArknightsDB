# SimpleLayoutContent

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _viewPrefab`

- `SimpleLayoutAdapter m_adapter`


## Properties

- `SimpleLayoutAdapter adapter`


## Methods

- `Void OnDestroy()`

- `SimpleLayoutAdapter get_adapter()`

- `Void set_adapter(SimpleLayoutAdapter)`

- `GameObject GetViewPrefab()`

- `Void _ObserveAdapter(SimpleLayoutAdapter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class SimpleLayoutContent : MonoBehaviour, IHotfixable
{
	private GameObject _viewPrefab; // 0x18
	private SimpleLayoutAdapter m_adapter; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x0
	private static DelegateBridge __Hotfix0_get_adapter; // 0x8
	private static DelegateBridge __Hotfix0_set_adapter; // 0x10
	private static DelegateBridge __Hotfix0_GetViewPrefab; // 0x18
	private static DelegateBridge __Hotfix0__ObserveAdapter; // 0x20
	private static DelegateBridge __Hotfix0_RefreshViews; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public SimpleLayoutAdapter adapter { get; set; }

	// RVA: 0x223f9b4 VA: 0x75948579b4
	private Void OnDestroy() { }
	// RVA: 0x223f204 VA: 0x7594857204
	public SimpleLayoutAdapter get_adapter() { }
	// RVA: 0x223f26c VA: 0x759485726c
	public Void set_adapter(SimpleLayoutAdapter value) { }
	// RVA: 0x223fa24 VA: 0x7594857a24
	public GameObject GetViewPrefab() { }
	// RVA: 0x223fa8c VA: 0x7594857a8c
	private Void _ObserveAdapter(SimpleLayoutAdapter adapter) { }
	// RVA: 0x223fb2c VA: 0x7594857b2c
	protected virtual Void RefreshViews() { }
	// RVA: 0x223fc60 VA: 0x7594857c60
	public Void .ctor() { }
}
```