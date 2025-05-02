# CriAtomBehaviour

**Namespace:** `CriWare.CriTimeline.Atom`


## Fields

- `Single volume`

- `Single pitch`

- `Single AISACValue`

- `CriAtomExAcb m_acb`

- `String m_lastCueSheetPath`

- `CriAtomExPlayback <playback>k__BackingField`

- `Boolean _IsClipPlaying`

- `Double _CueLength`


## Properties

- `CriAtomExPlayback playback`

- `Boolean IsClipPlaying`

- `Double CueLength`


## Methods

- `CriAtomExPlayback get_playback()`

- `Void set_playback(CriAtomExPlayback)`

- `Boolean get_IsClipPlaying()`

- `Void set_IsClipPlaying(Boolean)`

- `Double get_CueLength()`

- `Void set_CueLength(Double)`

- `Void Play(CriAtomSourceBase, CriAtomClipPlayConfig)`

- `Void PreviewPlay(Guid, Boolean, CriAtomClipPlayConfig)`

- `Void WaitAndStop()`

- `Void Stop(Boolean)`

- `Double GetCueLengthSec(CriAtomExAcb, String)`

- `Void <WaitAndStop>b__21_0()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Atom
public class CriAtomBehaviour : PlayableBehaviour
{
	public Single volume; // 0x10
	public Single pitch; // 0x14
	public Single AISACValue; // 0x18
	private static Int32 cPreviewStopTimeMs; // 0x0
	private CriAtomExAcb m_acb; // 0x20
	private String m_lastCueSheetPath; // 0x28
	private CriAtomExPlayback <playback>k__BackingField; // 0x30
	private Boolean _IsClipPlaying; // 0x34
	private Double _CueLength; // 0x38

	public CriAtomExPlayback playback { get; set; }
	public Boolean IsClipPlaying { get; set; }
	public Double CueLength { get; set; }

	// RVA: 0x4152280 VA: 0x759676a280
	public CriAtomExPlayback get_playback() { }
	// RVA: 0x4152288 VA: 0x759676a288
	private Void set_playback(CriAtomExPlayback value) { }
	// RVA: 0x4152290 VA: 0x759676a290
	public Boolean get_IsClipPlaying() { }
	// RVA: 0x4152298 VA: 0x759676a298
	private Void set_IsClipPlaying(Boolean value) { }
	// RVA: 0x41522a4 VA: 0x759676a2a4
	public Double get_CueLength() { }
	// RVA: 0x41522ac VA: 0x759676a2ac
	private Void set_CueLength(Double value) { }
	// RVA: 0x41522b4 VA: 0x759676a2b4
	public override Void OnGraphStop(Playable playable) { }
	// RVA: 0x41522d0 VA: 0x759676a2d0
	public Void Play(CriAtomSourceBase atomSource, CriAtomClipPlayConfig config) { }
	// RVA: 0x4152540 VA: 0x759676a540
	public Void PreviewPlay(Guid trackId, Boolean instantStop, CriAtomClipPlayConfig config) { }
	// RVA: 0x4152cac VA: 0x759676acac
	private Void WaitAndStop() { }
	// RVA: 0x4152d5c VA: 0x759676ad5c
	public Void Stop(Boolean noReleaseTime) { }
	// RVA: 0x41524dc VA: 0x759676a4dc
	private Double GetCueLengthSec(CriAtomExAcb acb, String cueName) { }
	// RVA: 0x4152d90 VA: 0x759676ad90
	public Void .ctor() { }
	// RVA: 0x4152da0 VA: 0x759676ada0
	private static Void .cctor() { }
	// RVA: 0x4152dec VA: 0x759676adec
	private Void <WaitAndStop>b__21_0() { }
}
```