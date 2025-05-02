# PrefabMark

**Namespace:** `Torappu`


## Fields

- `GameObject _markPrefab`

- `Boolean _markVisible`

- `GameObject m_prefabInst`


## Properties

- `GameObject prefab`

- `Boolean showMark`


## Methods

- `GameObject get_prefab()`

- `Void set_prefab(GameObject)`

- `Boolean get_showMark()`

- `Void set_showMark(Boolean)`

- `Void _RefreshInst()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PrefabMark : MonoBehaviour, IHotfixable
{
	private GameObject _markPrefab; // 0x18
	private Boolean _markVisible; // 0x20
	private GameObject m_prefabInst; // 0x28
	private static DelegateBridge __Hotfix0_get_prefab; // 0x0
	private static DelegateBridge __Hotfix0_set_prefab; // 0x8
	private static DelegateBridge __Hotfix0_get_showMark; // 0x10
	private static DelegateBridge __Hotfix0_set_showMark; // 0x18
	private static DelegateBridge __Hotfix0__RefreshInst; // 0x20
	private static DelegateBridge __Hotfix0_Awake; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public GameObject prefab { get; set; }
	public Boolean showMark { get; set; }

	// RVA: 0x3105138 VA: 0x759571d138
	public GameObject get_prefab() { }
	// RVA: 0x31051a0 VA: 0x759571d1a0
	public Void set_prefab(GameObject value) { }
	// RVA: 0x3105458 VA: 0x759571d458
	public Boolean get_showMark() { }
	// RVA: 0x31054c0 VA: 0x759571d4c0
	public Void set_showMark(Boolean value) { }
	// RVA: 0x31052c4 VA: 0x759571d2c4
	private Void _RefreshInst() { }
	// RVA: 0x3105564 VA: 0x759571d564
	private Void Awake() { }
	// RVA: 0x31055cc VA: 0x759571d5cc
	public Void .ctor() { }
}
```