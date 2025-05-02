# UIAVGCharacter

**Namespace:** `Torappu.AVG`


## Fields

- `Transform _container`

- `AVGSharedCharacter m_cachedCharacter`


## Methods

- `Void SetCharacter(Option)`

- `Void OnDestroy()`

- `Void _LoadCharacter(Option)`

- `Void _UnloadCharacter()`

- `GameObject _LoadHub(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class UIAVGCharacter : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private AVGSharedCharacter m_cachedCharacter; // 0x20
	private static DelegateBridge __Hotfix0_SetCharacter; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__LoadCharacter; // 0x10
	private static DelegateBridge __Hotfix0__UnloadCharacter; // 0x18
	private static DelegateBridge __Hotfix0__LoadHub; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3e9e288 VA: 0x75964b6288
	public Void SetCharacter(Option option) { }
	// RVA: 0x3e9e7fc VA: 0x75964b67fc
	public Void OnDestroy() { }
	// RVA: 0x3e9e5a0 VA: 0x75964b65a0
	private Void _LoadCharacter(Option option) { }
	// RVA: 0x3e9e3a8 VA: 0x75964b63a8
	private Void _UnloadCharacter() { }
	// RVA: 0x3e9e864 VA: 0x75964b6864
	private GameObject _LoadHub(String path) { }
	// RVA: 0x3e9e9a8 VA: 0x75964b69a8
	public Void .ctor() { }
}
```