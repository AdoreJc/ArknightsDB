# CriAtomTrack

**Namespace:** `CriWare.CriTimeline.Atom`


## Fields

- `String m_AisacControls`

- `Boolean m_StopOnWrapping`

- `Boolean m_StopAtGraphEnd`

- `Boolean m_ApplyPlayableSpeed`

- `Boolean m_CheckPosWithinClip`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Atom
public class CriAtomTrack : TrackAsset
{
	public String m_AisacControls; // 0xa0
	public Boolean m_StopOnWrapping; // 0xa8
	public Boolean m_StopAtGraphEnd; // 0xa9
	public Boolean m_ApplyPlayableSpeed; // 0xaa
	public Boolean m_CheckPosWithinClip; // 0xab


	// RVA: 0x41559c8 VA: 0x759676d9c8
	public override Playable CreateTrackMixer(PlayableGraph graph, GameObject owner, Int32 inputCount) { }
	// RVA: 0x4155d7c VA: 0x759676dd7c
	public Void .ctor() { }
}
```