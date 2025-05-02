# OpenServerData

**Namespace:** `Torappu`


## Fields

- `MissionGroup openServerMissionGroup`


## Methods

- `Boolean ShouldSerializetotalCheckinCharData()`

- `Boolean ShouldSerializechainLoginCharData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class OpenServerData
{
	public MissionGroup openServerMissionGroup; // 0x10
	public List`1 openServerMissionData; // 0x18
	public List`1 checkInData; // 0x20
	public List`1 chainLoginData; // 0x28
	public List`1 totalCheckinCharData; // 0x30
	public List`1 chainLoginCharData; // 0x38


	// RVA: 0x34a5ec8 VA: 0x7595abdec8
	public Boolean ShouldSerializetotalCheckinCharData() { }
	// RVA: 0x34a5f1c VA: 0x7595abdf1c
	public Boolean ShouldSerializechainLoginCharData() { }
	// RVA: 0x34a5f70 VA: 0x7595abdf70
	public Void .ctor() { }
}
```