# ScriptableComponent

**Namespace:** `AdvancedInspector`


## Fields

- `ScriptableObject owner`


## Properties

- `ScriptableObject Owner`


## Methods

- `ScriptableObject get_Owner()`

- `Void set_Owner(ScriptableObject)`

- `Void Erase()`

- `ScriptableComponent Instantiate()`

- `ScriptableComponent Instantiate(ScriptableObject)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class ScriptableComponent : ScriptableObject
{
	private ScriptableObject owner; // 0x18

	public ScriptableObject Owner { get; set; }

	// RVA: 0x1b22204 VA: 0x759413a204
	public ScriptableObject get_Owner() { }
	// RVA: 0x1b2220c VA: 0x759413a20c
	public Void set_Owner(ScriptableObject value) { }
	// RVA: 0x1b22298 VA: 0x759413a298
	protected virtual Void Reset() { }
	// RVA: 0x1b222a4 VA: 0x759413a2a4
	public Void Erase() { }
	// RVA: 0x1b224dc VA: 0x759413a4dc
	public ScriptableComponent Instantiate() { }
	// RVA: 0x1b224e4 VA: 0x759413a4e4
	public ScriptableComponent Instantiate(ScriptableObject owner) { }
	// RVA: 0x1b2256c VA: 0x759413a56c
	private static Object CopyObject(ScriptableObject owner, Object original) { }
	// RVA: 0x1b229fc VA: 0x759413a9fc
	private static IList CopyList(ScriptableObject owner, IList original) { }
	// RVA: 0x1b22db4 VA: 0x759413adb4
	private static ScriptableComponent CopyComponent(ScriptableObject owner, ScriptableComponent original) { }
	// RVA: 0x1b22f88 VA: 0x759413af88
	private static Object CopyClass(ScriptableObject owner, Object original) { }
	// RVA: 0x1b2314c VA: 0x759413b14c
	public Void .ctor() { }
}
```