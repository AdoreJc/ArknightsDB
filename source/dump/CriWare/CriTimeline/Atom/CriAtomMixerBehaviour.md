# CriAtomMixerBehaviour

**Namespace:** `CriWare.CriTimeline.Atom`


## Fields

- `Guid <m_Guid>k__BackingField`

- `DateTime m_lastScrubTime`

- `Double m_lastDirectorTime`

- `CriAtomListener previewSelectedListenerObj`


## Properties

- `Guid m_Guid`


## Methods

- `Guid get_m_Guid()`

- `Void set_m_Guid(Guid)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Atom
public class CriAtomMixerBehaviour : PlayableBehaviour
{
	internal PlayableDirector m_Director; // 0x10
	internal TimelineClip[] m_Clips; // 0x18
	internal CriAtomSourceBase m_Bind; // 0x20
	internal String m_AisacControls; // 0x28
	internal Boolean m_StopOnWrapping; // 0x30
	internal Boolean m_StopAtGraphEnd; // 0x31
	internal Boolean m_ApplyPlayableSpeed; // 0x32
	internal Boolean m_CheckPosWithinClip; // 0x33
	private Guid <m_Guid>k__BackingField; // 0x34
	private const Int32 cScratchTimeIntervalMs; // 0x0
	private const Double cFrameSkipTolerance; // 0x0
	private DateTime m_lastScrubTime; // 0x48
	private Double m_lastDirectorTime; // 0x50
	private CriAtomListener previewSelectedListenerObj; // 0x58

	public Guid m_Guid { get; set; }
	private static Boolean IsEditor { get; }

	// RVA: 0x415326c VA: 0x759676b26c
	public Guid get_m_Guid() { }
	// RVA: 0x415327c VA: 0x759676b27c
	private Void set_m_Guid(Guid value) { }
	// RVA: 0x4153288 VA: 0x759676b288
	public override Void OnPlayableCreate(Playable playable) { }
	// RVA: 0x41532b4 VA: 0x759676b2b4
	public override Void OnPlayableDestroy(Playable playable) { }
	// RVA: 0x415339c VA: 0x759676b39c
	public override Void OnGraphStop(Playable playable) { }
	// RVA: 0x41535f8 VA: 0x759676b5f8
	public override Void ProcessFrame(Playable playable, FrameData info, Object playerData) { }
	// RVA: 0x41532d0 VA: 0x759676b2d0
	private static Boolean get_IsEditor() { }
	// RVA: 0x4154878 VA: 0x759676c878
	public Void .ctor() { }
}
```