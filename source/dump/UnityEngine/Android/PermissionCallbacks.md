# PermissionCallbacks

**Namespace:** `UnityEngine.Android`


## Methods

- `Void add_PermissionGranted(Action`1)`

- `Void remove_PermissionGranted(Action`1)`

- `Void add_PermissionDenied(Action`1)`

- `Void remove_PermissionDenied(Action`1)`

- `Void add_PermissionDeniedAndDontAskAgain(Action`1)`

- `Void remove_PermissionDeniedAndDontAskAgain(Action`1)`

- `Void onPermissionGranted(String)`

- `Void onPermissionDenied(String)`

- `Void onPermissionDeniedAndDontAskAgain(String)`


## Dump
```C#
// Dll : UnityEngine.AndroidJNIModule.dll
// Namespace : UnityEngine.Android
public class PermissionCallbacks : AndroidJavaProxy
{
	private Action`1 PermissionGranted; // 0x20
	private Action`1 PermissionDenied; // 0x28
	private Action`1 PermissionDeniedAndDontAskAgain; // 0x30


	// RVA: 0x6844884 VA: 0x7598e5c884
	public Void add_PermissionGranted(Action`1 value) { }
	// RVA: 0x6844934 VA: 0x7598e5c934
	public Void remove_PermissionGranted(Action`1 value) { }
	// RVA: 0x68449e4 VA: 0x7598e5c9e4
	public Void add_PermissionDenied(Action`1 value) { }
	// RVA: 0x6844a94 VA: 0x7598e5ca94
	public Void remove_PermissionDenied(Action`1 value) { }
	// RVA: 0x6844b44 VA: 0x7598e5cb44
	public Void add_PermissionDeniedAndDontAskAgain(Action`1 value) { }
	// RVA: 0x6844bf4 VA: 0x7598e5cbf4
	public Void remove_PermissionDeniedAndDontAskAgain(Action`1 value) { }
	// RVA: 0x6844ca4 VA: 0x7598e5cca4
	public Void .ctor() { }
	// RVA: 0x6844d10 VA: 0x7598e5cd10
	private Void onPermissionGranted(String permissionName) { }
	// RVA: 0x6844d2c VA: 0x7598e5cd2c
	private Void onPermissionDenied(String permissionName) { }
	// RVA: 0x6844d48 VA: 0x7598e5cd48
	private Void onPermissionDeniedAndDontAskAgain(String permissionName) { }
}
```