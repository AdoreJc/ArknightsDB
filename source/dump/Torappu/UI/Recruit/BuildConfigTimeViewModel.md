# BuildConfigTimeViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Int64 m_buildTimeMillsec`

- `Int32 m_hour`

- `Int32 m_minute`

- `Int32 m_second`


## Properties

- `Int64 buildTimeMillsec`

- `String hour`

- `String minute`


## Methods

- `Int64 get_buildTimeMillsec()`

- `Void set_buildTimeMillsec(Int64)`

- `String get_hour()`

- `String get_minute()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class BuildConfigTimeViewModel
{
	private Int64 m_buildTimeMillsec; // 0x10
	private Int32 m_hour; // 0x18
	private Int32 m_minute; // 0x1c
	private Int32 m_second; // 0x20

	public Int64 buildTimeMillsec { get; set; }
	public String hour { get; }
	public String minute { get; }

	// RVA: 0x26fda10 VA: 0x7594d15a10
	public Int64 get_buildTimeMillsec() { }
	// RVA: 0x26fda18 VA: 0x7594d15a18
	public Void set_buildTimeMillsec(Int64 value) { }
	// RVA: 0x26fda98 VA: 0x7594d15a98
	public String get_hour() { }
	// RVA: 0x26fdb1c VA: 0x7594d15b1c
	public String get_minute() { }
	// RVA: 0x26fdba0 VA: 0x7594d15ba0
	public Void .ctor() { }
}
```