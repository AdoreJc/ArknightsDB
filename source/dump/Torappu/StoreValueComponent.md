# StoreValueComponent

**Namespace:** `Torappu`


## Fields

- `Boolean m_isInited`


## Methods

- `Void _RuntimeInitIfNot()`

- `Void _ConvertRuntimeStores()`

- `String GetString(String)`

- `Single GetFloat(String)`

- `TObj GetObject(String)`

- `Vector3 GetVector3(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class StoreValueComponent : MonoBehaviour, IHotfixable
{
	private List`1 _objects; // 0x18
	private List`1 _values; // 0x20
	private Boolean m_isInited; // 0x28
	private ListDict`2 m_objectDict; // 0x30
	private ListDict`2 m_strDict; // 0x38
	private ListDict`2 m_vectorDict; // 0x40
	private ListDict`2 m_floatDict; // 0x48
	private static DelegateBridge __Hotfix0__RuntimeInitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__ConvertRuntimeStores; // 0x8
	private static DelegateBridge __Hotfix0__StrToFloat; // 0x10
	private static DelegateBridge __Hotfix0__StrToVector3; // 0x18
	private static DelegateBridge __Hotfix0__Vector3ToStr; // 0x20
	private static DelegateBridge __Hotfix0_GetString; // 0x28
	private static DelegateBridge __Hotfix0_GetFloat; // 0x30
	private static DelegateBridge __Hotfix0_GetObject; // 0x38
	private static DelegateBridge __Hotfix0_GetVector3; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x31077e8 VA: 0x759571f7e8
	private Void _RuntimeInitIfNot() { }
	// RVA: 0x310786c VA: 0x759571f86c
	private Void _ConvertRuntimeStores() { }
	// RVA: 0x3107ba0 VA: 0x759571fba0
	private static Single _StrToFloat(String str) { }
	// RVA: 0x3107cac VA: 0x759571fcac
	private static Vector3 _StrToVector3(String str) { }
	// RVA: 0x3107e98 VA: 0x759571fe98
	private static String _Vector3ToStr(Vector3 vector) { }
	// RVA: 0x3107fb8 VA: 0x759571ffb8
	public String GetString(String key) { }
	// RVA: 0x310805c VA: 0x759572005c
	public Single GetFloat(String key) { }
	// RVA: 0x VA: 0x0
	public TObj GetObject(String key) { }
	// RVA: 0x3108100 VA: 0x7595720100
	public Vector3 GetVector3(String key) { }
	// RVA: 0x31081ac VA: 0x75957201ac
	public Void .ctor() { }
}
```