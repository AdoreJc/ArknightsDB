# CriAtomTimelinePreviewer

**Namespace:** `CriWare.CriTimeline.Atom`


## Fields

- `CriAtom atom`

- `String lastAcfFile`


## Methods

- `PlayerSource GetPlayer(Guid)`

- `Void Update3dTransform(Guid, Transform, Single)`

- `Void InitPreviewListenerList(CriAtomListener[])`

- `Void UpdateAllListeners(Guid, Single, CriAtomListener)`

- `Void SetCue(Guid, CriAtomExAcb, String)`

- `CriAtomExAcb GetAcb(String, String)`

- `CriAtomExPlayback Play(Guid)`

- `Void StopTrack(Guid, Boolean)`

- `Void StopAllTracks(Boolean)`

- `Void SetStartTime(Guid, Int64)`

- `Void SetLoop(Guid, Boolean)`

- `Void SetVolume(Guid, Single)`

- `Void SetPitch(Guid, Single)`

- `Void SetAISAC(Guid, String, Single)`

- `Void PlayerUpdateParameter(Guid, CriAtomExPlayback)`

- `Void UpdateTimelineExtension(CriAtomSourceBase, Guid)`

- `Void Dispose()`

- `Void Dispose(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Atom
public class CriAtomTimelinePreviewer : IDisposable
{
	private static CriAtomTimelinePreviewer instance; // 0x0
	private CriAtom atom; // 0x10
	private String lastAcfFile; // 0x18
	private Dictionary`2 acbTable; // 0x20
	private Dictionary`2 playerTable; // 0x28
	private Dictionary`2 listenerTable; // 0x30
	private List`1 listenerPurgeList; // 0x38
	private Nullable`1 trackIdForListenerUpdate; // 0x40

	public static CriAtomTimelinePreviewer Instance { get; }
	public static Boolean IsInitialized { get; }

	// RVA: 0x41526e0 VA: 0x759676a6e0
	public static CriAtomTimelinePreviewer get_Instance() { }
	// RVA: 0x4153328 VA: 0x759676b328
	public static Void InstanceDispose() { }
	// RVA: 0x41532d8 VA: 0x759676b2d8
	public static Boolean get_IsInitialized() { }
	// RVA: 0x4154880 VA: 0x759676c880
	public Void .ctor() { }
	// RVA: 0x4154a88 VA: 0x759676ca88
	private PlayerSource GetPlayer(Guid trackId) { }
	// RVA: 0x4153fd0 VA: 0x759676bfd0
	public Void Update3dTransform(Guid trackId, Transform transform, Single deltaTime) { }
	// RVA: 0x4153c64 VA: 0x759676bc64
	public Void InitPreviewListenerList(CriAtomListener[] listenerList) { }
	// RVA: 0x4154090 VA: 0x759676c090
	public Void UpdateAllListeners(Guid trackId, Single deltaTime, CriAtomListener exclusiveObj) { }
	// RVA: 0x4152b40 VA: 0x759676ab40
	public Void SetCue(Guid trackId, CriAtomExAcb acb, String cueName) { }
	// RVA: 0x415276c VA: 0x759676a76c
	public CriAtomExAcb GetAcb(String acbPath, String awbPath) { }
	// RVA: 0x4152c78 VA: 0x759676ac78
	public CriAtomExPlayback Play(Guid trackId) { }
	// RVA: 0x4155268 VA: 0x759676d268
	public Void StopTrack(Guid trackId, Boolean stopWithoutRelease) { }
	// RVA: 0x4153448 VA: 0x759676b448
	public Void StopAllTracks(Boolean stopWithoutRelease) { }
	// RVA: 0x4152c20 VA: 0x759676ac20
	public Void SetStartTime(Guid trackId, Int64 startTimeMs) { }
	// RVA: 0x4152c4c VA: 0x759676ac4c
	public Void SetLoop(Guid trackId, Boolean sw) { }
	// RVA: 0x4154788 VA: 0x759676c788
	public Void SetVolume(Guid trackId, Single volume) { }
	// RVA: 0x41547bc VA: 0x759676c7bc
	public Void SetPitch(Guid trackId, Single pitch) { }
	// RVA: 0x41547f0 VA: 0x759676c7f0
	public Void SetAISAC(Guid trackId, String controlName, Single value) { }
	// RVA: 0x415482c VA: 0x759676c82c
	public Void PlayerUpdateParameter(Guid trackId, CriAtomExPlayback atomExPlayback) { }
	// RVA: 0x4154858 VA: 0x759676c858
	public Void UpdateTimelineExtension(CriAtomSourceBase bindObject, Guid trackGuid) { }
	// RVA: 0x415529c VA: 0x759676d29c
	protected override Void Finalize() { }
	// RVA: 0x4154a24 VA: 0x759676ca24
	public Void Dispose() { }
	// RVA: 0x4155334 VA: 0x759676d334
	private Void Dispose(Boolean disposing) { }
}
```