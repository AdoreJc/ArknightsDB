# ChangeEvent

**Namespace:** `UnityEngine.UIElements`


## Fields

- `T <previousValue>k__BackingField`

- `T <newValue>k__BackingField`


## Properties

- `T previousValue`

- `T newValue`


## Methods

- `T get_previousValue()`

- `Void set_previousValue(T)`

- `T get_newValue()`

- `Void set_newValue(T)`

- `Void LocalInit()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class ChangeEvent`1 : EventBase`1
{
	private T <previousValue>k__BackingField; // 0x0
	private T <newValue>k__BackingField; // 0x0

	public T previousValue { get; set; }
	public T newValue { get; set; }

	// RVA: 0x VA: 0x0
	public T get_previousValue() { }
	// RVA: 0x VA: 0x0
	protected Void set_previousValue(T value) { }
	// RVA: 0x VA: 0x0
	public T get_newValue() { }
	// RVA: 0x VA: 0x0
	protected Void set_newValue(T value) { }
	// RVA: 0x VA: 0x0
	protected override Void Init() { }
	// RVA: 0x VA: 0x0
	private Void LocalInit() { }
	// RVA: 0x VA: 0x0
	public static ChangeEvent`1 GetPooled(T previousValue, T newValue) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```