# CriManaClip

**Namespace:** `CriWare.CriTimeline.Mana`


## Fields

- `String m_moviePath`

- `TextAsset m_movieData`

- `CriManaBehaviour m_manaBehaviour`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Mana
public class CriManaClip : CriManaClipBase
{
	public String m_moviePath; // 0xa0
	public TextAsset m_movieData; // 0xa8
	public CriManaBehaviour m_manaBehaviour; // 0xb0

	public override String MoviePath { get; }
	public override Byte[] MovieData { get; }
	public override String MovieName { get; }
	public override Int32 DataId { get; }

	// RVA: 0x414e3dc VA: 0x75967663dc
	public override Playable CreatePlayable(PlayableGraph graph, GameObject owner) { }
	// RVA: 0x414e484 VA: 0x7596766484
	public override String get_MoviePath() { }
	// RVA: 0x414e48c VA: 0x759676648c
	public override Byte[] get_MovieData() { }
	// RVA: 0x414e514 VA: 0x7596766514
	public override String get_MovieName() { }
	// RVA: 0x414e5c8 VA: 0x75967665c8
	public override Int32 get_DataId() { }
	// RVA: 0x414e694 VA: 0x7596766694
	public Void .ctor() { }
}
```