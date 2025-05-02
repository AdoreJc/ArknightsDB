# PrefabDisplay

**Namespace:** `Torappu`


## Fields

- `GameObject _prefab`

- `GameObject m_prefabInst`


## Properties

- `GameObject prefab`

- `GameObject inst`


## Methods

- `GameObject get_prefab()`

- `Void set_prefab(GameObject)`

- `Void Clear()`

- `GameObject get_inst()`

- `Void _RefreshInst()`

- `Void OnApplyInst()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PrefabDisplay : MonoBehaviour, IHotfixable
{
	private GameObject _prefab; // 0x18
	private GameObject m_prefabInst; // 0x20
	private static DelegateBridge __Hotfix0_get_prefab; // 0x0
	private static DelegateBridge __Hotfix0_set_prefab; // 0x8
	private static DelegateBridge __Hotfix0_Clear; // 0x10
	private static DelegateBridge __Hotfix0_get_inst; // 0x18
	private static DelegateBridge __Hotfix0__RefreshInst; // 0x20
	private static DelegateBridge __Hotfix0_OnApplyInst; // 0x28
	private static DelegateBridge __Hotfix0_Awake; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public GameObject prefab { get; set; }
	public GameObject inst { get; }

	// RVA: 0x3104940 VA: 0x759571c940
	public GameObject get_prefab() { }
	// RVA: 0x31049a8 VA: 0x759571c9a8
	public Void set_prefab(GameObject value) { }
	// RVA: 0x3104bd8 VA: 0x759571cbd8
	public Void Clear() { }
	// RVA: 0x3104c50 VA: 0x759571cc50
	public GameObject get_inst() { }
	// RVA: 0x3104a84 VA: 0x759571ca84
	private Void _RefreshInst() { }
	// RVA: 0x3104cb8 VA: 0x759571ccb8
	public Void OnApplyInst() { }
	// RVA: 0x3104d1c VA: 0x759571cd1c
	private Void Awake() { }
	// RVA: 0x3104d84 VA: 0x759571cd84
	public Void .ctor() { }
}
```