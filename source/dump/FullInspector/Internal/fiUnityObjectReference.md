# fiUnityObjectReference

**Namespace:** `FullInspector.Internal`


## Fields

- `Object _target`

- `Object Target`


## Properties

- `Boolean IsValid`


## Methods

- `Boolean get_IsValid()`

- `Void TryRestoreFromInstanceId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiUnityObjectReference
{
	private Object _target; // 0x10
	public Object Target; // 0x18

	public Boolean IsValid { get; }

	// RVA: 0x34e6554 VA: 0x7595afe554
	public Void .ctor() { }
	// RVA: 0x34d572c VA: 0x7595aed72c
	public Void .ctor(Object target, Boolean tryRestore) { }
	// RVA: 0x34e65f0 VA: 0x7595afe5f0
	public Boolean get_IsValid() { }
	// RVA: 0x34e655c VA: 0x7595afe55c
	private Void TryRestoreFromInstanceId() { }
	// RVA: 0x34e6650 VA: 0x7595afe650
	public override Int32 GetHashCode() { }
	// RVA: 0x34e6688 VA: 0x7595afe688
	public override Boolean Equals(Object obj) { }
}
```