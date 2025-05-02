# ZoneGroupViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneType zoneType`

- `ZoneViewType zoneViewType`

- `String focusZoneId`


## Methods

- `Boolean CheckIfZoneEdged(String)`

- `ZoneViewModel FindFirstLockedZone()`

- `ZoneViewModel FindLastUnlockZone()`

- `ZoneViewModel FindZone(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneGroupViewModel
{
	public ZoneType zoneType; // 0x10
	public ZoneViewType zoneViewType; // 0x14
	public String focusZoneId; // 0x18
	public List`1 zones; // 0x20


	// RVA: 0x2fc3364 VA: 0x75955db364
	public Boolean CheckIfZoneEdged(String zoneId) { }
	// RVA: 0x2fc34ac VA: 0x75955db4ac
	public ZoneViewModel FindFirstLockedZone() { }
	// RVA: 0x2fc341c VA: 0x75955db41c
	public ZoneViewModel FindLastUnlockZone() { }
	// RVA: 0x2fbfe60 VA: 0x75955d7e60
	public ZoneViewModel FindZone(String zoneId) { }
	// RVA: 0x2fc3560 VA: 0x75955db560
	public Void .ctor() { }
}
```