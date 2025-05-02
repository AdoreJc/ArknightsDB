# GameObjectClusterActive

**Namespace:** `Torappu`


## Properties

- `Boolean active`


## Methods

- `Boolean get_active()`

- `Void set_active(Boolean)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void _SetActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GameObjectClusterActive : MonoBehaviour, IHotfixable
{
	private GameObject[] _gos; // 0x18
	private static DelegateBridge __Hotfix0_get_active; // 0x0
	private static DelegateBridge __Hotfix0_set_active; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDisable; // 0x18
	private static DelegateBridge __Hotfix0__SetActive; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean active { get; set; }

	// RVA: 0x2f47da4 VA: 0x759555fda4
	public Boolean get_active() { }
	// RVA: 0x2f47e10 VA: 0x759555fe10
	public Void set_active(Boolean value) { }
	// RVA: 0x2f47eb0 VA: 0x759555feb0
	private Void OnEnable() { }
	// RVA: 0x2f48000 VA: 0x7595560000
	private Void OnDisable() { }
	// RVA: 0x2f47f1c VA: 0x759555ff1c
	private Void _SetActive(Boolean active) { }
	// RVA: 0x2f4806c VA: 0x759556006c
	public Void .ctor() { }
}
```