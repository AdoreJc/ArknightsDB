# CriAtomSource

**Namespace:** `CriWare`


## Fields

- `String _cueName`

- `String _cueSheet`


## Properties

- `String cueName`

- `String cueSheet`


## Methods

- `String get_cueName()`

- `Void set_cueName(String)`

- `String get_cueSheet()`

- `Void set_cueSheet(String)`

- `IEnumerator PlayAsync(String)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomSource : CriAtomSourceBase
{
	private String _cueName; // 0xa0
	private String _cueSheet; // 0xa8

	public String cueName { get; set; }
	public String cueSheet { get; set; }

	// RVA: 0x4117cf4 VA: 0x759672fcf4
	public String get_cueName() { }
	// RVA: 0x4117cfc VA: 0x759672fcfc
	public Void set_cueName(String value) { }
	// RVA: 0x4117d04 VA: 0x759672fd04
	public String get_cueSheet() { }
	// RVA: 0x4117d0c VA: 0x759672fd0c
	public Void set_cueSheet(String value) { }
	// RVA: 0x4117d14 VA: 0x759672fd14
	public override CriAtomExPlayback Play() { }
	// RVA: 0x4117dac VA: 0x759672fdac
	protected override CriAtomExAcb GetAcb() { }
	// RVA: 0x4117ddc VA: 0x759672fddc
	protected override Void PlayOnStart() { }
	// RVA: 0x4117e24 VA: 0x759672fe24
	private IEnumerator PlayAsync(String cueName) { }
	// RVA: 0x4117edc VA: 0x759672fedc
	public Void .ctor() { }
}
```