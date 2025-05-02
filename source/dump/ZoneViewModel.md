# ZoneViewModel

**Namespace:** ` `


## Fields

- `ZoneValidInfo m_zoneValidInfo`

- `Boolean m_hasStageJustUnlock`

- `Boolean m_needUnlock`


## Properties

- `Boolean isTimeout`

- `Boolean hasNewSign`


## Methods

- `Boolean get_isTimeout()`

- `Boolean get_hasNewSign()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ZoneViewModel
{
	private ZoneValidInfo m_zoneValidInfo; // 0x10
	private Boolean m_hasStageJustUnlock; // 0x18
	private Boolean m_needUnlock; // 0x19

	public Boolean isTimeout { get; }
	public Boolean hasNewSign { get; }

	// RVA: 0x341f1f4 VA: 0x7595a371f4
	public Boolean get_isTimeout() { }
	// RVA: 0x341f3cc VA: 0x7595a373cc
	public Boolean get_hasNewSign() { }
	// RVA: 0x341ef80 VA: 0x7595a36f80
	public static ZoneViewModel Create(Int64 actStartTime, ActivityZoneViewModel zoneData) { }
	// RVA: 0x341f3fc VA: 0x7595a373fc
	public Void .ctor() { }
}
```