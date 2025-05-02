# TickYieldInstruction

**Namespace:** `Torappu`


## Fields

- `TickFunction m_tickFunc`

- `Boolean m_keepWaiting`

- `Component <host>k__BackingField`

- `Options <options>k__BackingField`


## Properties

- `Component host`

- `Options options`


## Methods

- `Component get_host()`

- `Void set_host(Component)`

- `Options get_options()`

- `Void set_options(Options)`

- `Void TimeManagerOnly_SetTickFunc(TickFunction)`

- `Void TimeManagerOnly_OnTick(Single)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TickYieldInstruction
{
	private TickFunction m_tickFunc; // 0x10
	private Boolean m_keepWaiting; // 0x18
	private Component <host>k__BackingField; // 0x20
	private Options <options>k__BackingField; // 0x28

	public Component host { get; set; }
	public Options options { get; set; }

	// RVA: 0x67508f4 VA: 0x7598d688f4
	public Component get_host() { }
	// RVA: 0x67508fc VA: 0x7598d688fc
	private Void set_host(Component value) { }
	// RVA: 0x6750904 VA: 0x7598d68904
	public Options get_options() { }
	// RVA: 0x6750910 VA: 0x7598d68910
	private Void set_options(Options value) { }
	// RVA: 0x6750920 VA: 0x7598d68920
	public Void .ctor(Component host, Options options) { }
	// RVA: 0x675097c VA: 0x7598d6897c
	public Void TimeManagerOnly_SetTickFunc(TickFunction tickFunction) { }
	// RVA: 0x6750984 VA: 0x7598d68984
	public Void TimeManagerOnly_OnTick(Single timeDelta) { }
}
```