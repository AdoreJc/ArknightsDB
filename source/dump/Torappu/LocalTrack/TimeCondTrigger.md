# TimeCondTrigger

**Namespace:** `Torappu.LocalTrack`


## Fields

- `Int64 updateTs`

- `Int64 timeout`


## Methods

- `Int32 CompareTo(Object)`

- `Int64 GetTypeVersion()`

- `Boolean IsValid(Int64, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class TimeCondTrigger : TrackTrigger, ITrackWithTypeVersion, IComparable
{
	public Int64 updateTs; // 0x20
	public Int64 timeout; // 0x28
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge __Hotfix0_GetTypeVersion; // 0x8
	private static DelegateBridge __Hotfix0_IsValid; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f19e08 VA: 0x7596531e08
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x3f19ee0 VA: 0x7596531ee0
	public Int64 GetTypeVersion() { }
	// RVA: 0x3f19f48 VA: 0x7596531f48
	public Boolean IsValid(Int64 lastTs, Int64 curTs) { }
	// RVA: 0x3f0fcc0 VA: 0x7596527cc0
	public Void .ctor() { }
}
```