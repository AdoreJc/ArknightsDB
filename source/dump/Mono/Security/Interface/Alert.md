# Alert

**Namespace:** `Mono.Security.Interface`


## Fields

- `AlertLevel level`

- `AlertDescription description`


## Properties

- `AlertLevel Level`

- `AlertDescription Description`


## Methods

- `AlertLevel get_Level()`

- `AlertDescription get_Description()`

- `Void inferAlertLevel()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Interface
public class Alert
{
	private AlertLevel level; // 0x10
	private AlertDescription description; // 0x11

	public AlertLevel Level { get; }
	public AlertDescription Description { get; }

	// RVA: 0x5ee97c4 VA: 0x75985017c4
	public AlertLevel get_Level() { }
	// RVA: 0x5ee97cc VA: 0x75985017cc
	public AlertDescription get_Description() { }
	// RVA: 0x5ee97d4 VA: 0x75985017d4
	public Void .ctor(AlertDescription description) { }
	// RVA: 0x5ee9840 VA: 0x7598501840
	private Void inferAlertLevel() { }
	// RVA: 0x5ee9880 VA: 0x7598501880
	public override String ToString() { }
}
```