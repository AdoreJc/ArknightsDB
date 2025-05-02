# CountDownTask

**Namespace:** `Torappu`


## Fields

- `Action onTimeout`


## Properties

- `TickValue latestTickValue`


## Methods

- `TickValue get_latestTickValue()`

- `Void SetCountDown(Int64)`

- `Void Interrupt()`

- `Void Tick()`

- `Void _OnTaskEnd(Context)`

- `Void _OnValueChanged(Context)`

- `TickValue _UpdateValue(Context)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CountDownTask
{
	private const Int64 DEFAULT_INTERVAL; // 0x0
	private TaskTimer`1 m_timer; // 0x10
	public Func`2 overrideUpdateTickValue; // 0x18
	public Action`1 onTimeTick; // 0x20
	public Action onTimeout; // 0x28

	public TickValue latestTickValue { get; }

	// RVA: 0x2f42d9c VA: 0x759555ad9c
	public Void .ctor() { }
	// RVA: 0x2f42da4 VA: 0x759555ada4
	public TickValue get_latestTickValue() { }
	// RVA: 0x2f42df0 VA: 0x759555adf0
	public Void SetCountDown(Int64 remainSeconds) { }
	// RVA: 0x2f43064 VA: 0x759555b064
	public Void Interrupt() { }
	// RVA: 0x2f430bc VA: 0x759555b0bc
	public Void Tick() { }
	// RVA: 0x2f43114 VA: 0x759555b114
	private Void _OnTaskEnd(Context context) { }
	// RVA: 0x2f43130 VA: 0x759555b130
	private Void _OnValueChanged(Context context) { }
	// RVA: 0x2f43150 VA: 0x759555b150
	private TickValue _UpdateValue(Context context) { }
}
```