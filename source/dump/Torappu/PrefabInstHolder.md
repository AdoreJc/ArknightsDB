# PrefabInstHolder

**Namespace:** `Torappu`


## Fields

- `Transform _prefabContainer`

- `GameObject _prefab`

- `GameObject m_instance`


## Properties

- `Transform prefabContainer`


## Methods

- `Transform get_prefabContainer()`

- `Void set_achieveInst(Action`1)`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PrefabInstHolder : MonoBehaviour, IHotfixable
{
	private Transform _prefabContainer; // 0x18
	private GameObject _prefab; // 0x20
	private GameObject m_instance; // 0x28
	private Action`1 m_onAchieveInstOnce; // 0x30
	private static DelegateBridge __Hotfix0_get_prefabContainer; // 0x0
	private static DelegateBridge __Hotfix0_set_achieveInst; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected Transform prefabContainer { get; }
	public Action`1 achieveInst { set; }

	// RVA: 0x3104df4 VA: 0x759571cdf4
	protected Transform get_prefabContainer() { }
	// RVA: 0x3104eac VA: 0x759571ceac
	public Void set_achieveInst(Action`1 value) { }
	// RVA: 0x3104fb0 VA: 0x759571cfb0
	private Void Start() { }
	// RVA: 0x31050c8 VA: 0x759571d0c8
	public Void .ctor() { }
}
```