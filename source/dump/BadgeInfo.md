# BadgeInfo

**Namespace:** ` `


## Fields

- `BadgeStatus status`


## Properties

- `Int32 missionCurProgress`

- `Int32 missionTargetProgress`


## Methods

- `Int32 get_missionCurProgress()`

- `Int32 get_missionTargetProgress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BadgeInfo
{
	public BadgeStatus status; // 0x10
	private Int32[] m_missionProgress; // 0x18

	public Int32 missionCurProgress { get; }
	public Int32 missionTargetProgress { get; }

	// RVA: 0x32d2e64 VA: 0x75958eae64
	public Int32 get_missionCurProgress() { }
	// RVA: 0x32d2eb4 VA: 0x75958eaeb4
	public Int32 get_missionTargetProgress() { }
	// RVA: 0x32d2f04 VA: 0x75958eaf04
	public Void .ctor() { }
}
```