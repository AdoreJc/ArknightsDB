# CriAtomClip

**Namespace:** `CriWare.CriTimeline.Atom`


## Fields

- `String cueSheet`

- `String cueName`

- `CriAtomBehaviour templateBehaviour`


## Methods

- `CriAtomCueSheet GetCueSheet()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Atom
public class CriAtomClip : CriAtomClipBase
{
	public String cueSheet; // 0x28
	public String cueName; // 0x30
	public CriAtomBehaviour templateBehaviour; // 0x38

	public override String CueName { get; }
	public override String AcbPath { get; }
	public override String AwbPath { get; }

	// RVA: 0x4152e74 VA: 0x759676ae74
	public override Playable CreatePlayable(PlayableGraph graph, GameObject owner) { }
	// RVA: 0x4152f1c VA: 0x759676af1c
	public override String get_CueName() { }
	// RVA: 0x4152f24 VA: 0x759676af24
	public override CriAtomExAcb GetAcb() { }
	// RVA: 0x4152f30 VA: 0x759676af30
	private CriAtomCueSheet GetCueSheet() { }
	// RVA: 0x4152f3c VA: 0x759676af3c
	public override String get_AcbPath() { }
	// RVA: 0x4152fe4 VA: 0x759676afe4
	public override String get_AwbPath() { }
	// RVA: 0x415308c VA: 0x759676b08c
	public override Void SetCueFromAtomSource(CriAtomSourceBase atomSource) { }
	// RVA: 0x41531b4 VA: 0x759676b1b4
	public Void .ctor() { }
}
```