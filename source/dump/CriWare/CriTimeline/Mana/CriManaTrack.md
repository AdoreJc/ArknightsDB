# CriManaTrack

**Namespace:** `CriWare.CriTimeline.Mana`


## Fields

- `Boolean frameSync`

- `Boolean checkPosWithinClip`


## Methods

- `Void OnDestroy()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Mana
public class CriManaTrack : TrackAsset
{
	public Boolean frameSync; // 0xa0
	public Boolean checkPosWithinClip; // 0xa1
	public readonly Guid guid; // 0xa4
	private static Dictionary`2 bindDict; // 0x0


	// RVA: 0x415155c VA: 0x759676955c
	public override Playable CreateTrackMixer(PlayableGraph graph, GameObject go, Int32 inputCount) { }
	// RVA: 0x41520e4 VA: 0x759676a0e4
	private Void OnDestroy() { }
	// RVA: 0x4151c48 VA: 0x7596769c48
	private static Void RemoveTrackFromBindDict(CriManaTrack trackAsset) { }
	// RVA: 0x4152138 VA: 0x759676a138
	public Void .ctor() { }
	// RVA: 0x41521a8 VA: 0x759676a1a8
	private static Void .cctor() { }
}
```