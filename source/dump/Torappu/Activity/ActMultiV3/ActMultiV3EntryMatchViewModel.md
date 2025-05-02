# ActMultiV3EntryMatchViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Boolean hasMentorUnlockTrackpoint`

- `Boolean hasInverseUnlockTrackpoint`

- `Boolean hasModeUnlockTrackpoint`


## Properties

- `Boolean hasTrackpoint`


## Methods

- `Boolean get_hasTrackpoint()`

- `Void LoadData(String, PlayerMultiV3Activity, ActMultiV3Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3EntryMatchViewModel : IHotfixable
{
	public Boolean hasMentorUnlockTrackpoint; // 0x10
	public Boolean hasInverseUnlockTrackpoint; // 0x11
	public Boolean hasModeUnlockTrackpoint; // 0x12
	public Dictionary`2 modeStarCount; // 0x18
	private static DelegateBridge __Hotfix0_get_hasTrackpoint; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean hasTrackpoint { get; }

	// RVA: 0x30f0100 VA: 0x7595708100
	public Boolean get_hasTrackpoint() { }
	// RVA: 0x30f1c1c VA: 0x7595709c1c
	public Void LoadData(String actId, PlayerMultiV3Activity playerActivity, ActMultiV3Data actData) { }
	// RVA: 0x30f20a8 VA: 0x759570a0a8
	public Void .ctor() { }
}
```