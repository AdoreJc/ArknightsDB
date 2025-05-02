# ObjectTranslatorPool

**Namespace:** `XLua`


## Fields

- `IntPtr lastPtr`

- `ObjectTranslator lastTranslator`


## Methods

- `Void Add(IntPtr, ObjectTranslator)`

- `ObjectTranslator Find(IntPtr)`

- `Void Remove(IntPtr)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class ObjectTranslatorPool
{
	private Dictionary`2 translators; // 0x10
	private IntPtr lastPtr; // 0x18
	private ObjectTranslator lastTranslator; // 0x20

	public static ObjectTranslatorPool Instance { get; }

	// RVA: 0x3ff180c VA: 0x759660980c
	public static ObjectTranslatorPool get_Instance() { }
	// RVA: 0x3ff186c VA: 0x759660986c
	public Void .ctor() { }
	// RVA: 0x3ff18f4 VA: 0x75966098f4
	public Void Add(IntPtr L, ObjectTranslator translator) { }
	// RVA: 0x3ff1adc VA: 0x7596609adc
	public ObjectTranslator Find(IntPtr L) { }
	// RVA: 0x3ff1d08 VA: 0x7596609d08
	public Void Remove(IntPtr L) { }
}
```