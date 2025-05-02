# ClearAssets

**Namespace:** `Torappu`


## Fields

- `Boolean _clearOnAwake`

- `Boolean _unloadAll`

- `Boolean _forceUnloadEvenUsed`

- `Boolean <isClearing>k__BackingField`

- `Boolean <isCleared>k__BackingField`


## Properties

- `Boolean isClearing`

- `Boolean isCleared`


## Methods

- `Boolean get_isClearing()`

- `Void set_isClearing(Boolean)`

- `Boolean get_isCleared()`

- `Void set_isCleared(Boolean)`

- `IEnumerator _DoClear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ClearAssets : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private Boolean _clearOnAwake; // 0x18
	private Boolean _unloadAll; // 0x19
	private Boolean _forceUnloadEvenUsed; // 0x1a
	private String[] _excludedPrefixes; // 0x20
	private Boolean <isClearing>k__BackingField; // 0x28
	private Boolean <isCleared>k__BackingField; // 0x29
	private static DelegateBridge __Hotfix0_get_isClearing; // 0x0
	private static DelegateBridge __Hotfix0_set_isClearing; // 0x8
	private static DelegateBridge __Hotfix0_get_isCleared; // 0x10
	private static DelegateBridge __Hotfix0_set_isCleared; // 0x18
	private static DelegateBridge __Hotfix0_ClearIfExists; // 0x20
	private static DelegateBridge __Hotfix0__DoClear; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean isClearing { get; set; }
	public Boolean isCleared { get; set; }

	// RVA: 0x2d14270 VA: 0x759532c270
	public Boolean get_isClearing() { }
	// RVA: 0x2d142d8 VA: 0x759532c2d8
	private Void set_isClearing(Boolean value) { }
	// RVA: 0x2d14358 VA: 0x759532c358
	public Boolean get_isCleared() { }
	// RVA: 0x2d143c0 VA: 0x759532c3c0
	private Void set_isCleared(Boolean value) { }
	// RVA: 0x2d14440 VA: 0x759532c440
	public static IEnumerator ClearIfExists(Boolean force) { }
	// RVA: 0x2d1450c VA: 0x759532c50c
	private IEnumerator _DoClear() { }
	// RVA: 0x2d145e0 VA: 0x759532c5e0
	protected override Void OnInit() { }
	// RVA: 0x2d1468c VA: 0x759532c68c
	public Void .ctor() { }
}
```