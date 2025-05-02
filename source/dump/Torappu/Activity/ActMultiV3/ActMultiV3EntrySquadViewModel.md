# ActMultiV3EntrySquadViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadEffectTrackPointModel squadEffectTrackPoint`

- `Boolean hasNewUnlockedSquad`


## Properties

- `Boolean showTrackPoint`


## Methods

- `Boolean get_showTrackPoint()`

- `Void LoadData(String, ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntrySquadViewModel : IHotfixable
{
	public ActMultiV3SquadEffectTrackPointModel squadEffectTrackPoint; // 0x10
	public Boolean hasNewUnlockedSquad; // 0x18
	private static DelegateBridge __Hotfix0_get_showTrackPoint; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean showTrackPoint { get; }

	// RVA: 0x30f0070 VA: 0x7595708070
	public Boolean get_showTrackPoint() { }
	// RVA: 0x30f1394 VA: 0x7595709394
	public Void LoadData(String actId, ActMultiV3Data actData) { }
	// RVA: 0x30f1588 VA: 0x7595709588
	public Void .ctor() { }
}
```