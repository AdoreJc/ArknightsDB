# Root

**Namespace:** ` `


## Fields

- `TickGroup m_group`

- `String <name>k__BackingField`

- `Single m_frameInterval`

- `Double m_lastTickTs`


## Properties

- `String name`


## Methods

- `String get_name()`

- `Void set_name(String)`

- `Void SetOptions(RootOptions)`

- `Void SetGlobalTimeScale(Single)`

- `Void Tick(Single, Double)`

- `TickFunction AddTickFunction(ITickOwner, Action`1, String)`

- `Void Release()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Root
{
	private TickGroup m_group; // 0x10
	private String <name>k__BackingField; // 0x18
	private Single m_frameInterval; // 0x20
	private Double m_lastTickTs; // 0x28

	public String name { get; set; }

	// RVA: 0x678e5a0 VA: 0x7598da65a0
	public String get_name() { }
	// RVA: 0x678e5a8 VA: 0x7598da65a8
	private Void set_name(String value) { }
	// RVA: 0x678e5b0 VA: 0x7598da65b0
	public Void .ctor(String pName) { }
	// RVA: 0x678e64c VA: 0x7598da664c
	public Void SetOptions(RootOptions options) { }
	// RVA: 0x678e670 VA: 0x7598da6670
	public Void SetGlobalTimeScale(Single timeScale) { }
	// RVA: 0x678e688 VA: 0x7598da6688
	public Void Tick(Single unscaledDeltaTime, Double unscaledTime) { }
	// RVA: 0x678e6e4 VA: 0x7598da66e4
	public TickFunction AddTickFunction(ITickOwner owner, Action`1 func, String name) { }
	// RVA: 0x678e6fc VA: 0x7598da66fc
	public Void Release() { }
}
```