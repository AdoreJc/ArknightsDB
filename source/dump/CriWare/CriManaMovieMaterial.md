# CriManaMovieMaterial

**Namespace:** `CriWare`


## Fields

- `String _moviePath`

- `Boolean _loop`

- `Boolean _audioBaseConcatenation`

- `Boolean _additiveMode`

- `Boolean _advancedAudio`

- `Boolean _ambisonics`

- `Boolean _applyTargetAlpha`

- `Boolean _uiRenderMode`

- `GameObject ambisonicSource`


## Properties

- `String moviePath`

- `Boolean loop`

- `Boolean audioBaseConcatenation`

- `Boolean advancedAudio`

- `Boolean ambisonics`

- `Boolean additiveMode`

- `Boolean applyTargetAlpha`

- `Boolean uiRenderMode`


## Methods

- `String get_moviePath()`

- `Void set_moviePath(String)`

- `Boolean get_loop()`

- `Void set_loop(Boolean)`

- `Boolean get_audioBaseConcatenation()`

- `Void set_audioBaseConcatenation(Boolean)`

- `Boolean get_advancedAudio()`

- `Void set_advancedAudio(Boolean)`

- `Boolean get_ambisonics()`

- `Void set_ambisonics(Boolean)`

- `Boolean get_additiveMode()`

- `Void set_additiveMode(Boolean)`

- `Boolean get_applyTargetAlpha()`

- `Void set_applyTargetAlpha(Boolean)`

- `Boolean get_uiRenderMode()`

- `Void set_uiRenderMode(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriManaMovieMaterial : CriManaMovieMaterialBase
{
	private String _moviePath; // 0x80
	private Boolean _loop; // 0x88
	private Boolean _audioBaseConcatenation; // 0x89
	private Boolean _additiveMode; // 0x8a
	private Boolean _advancedAudio; // 0x8b
	private Boolean _ambisonics; // 0x8c
	private Boolean _applyTargetAlpha; // 0x8d
	private Boolean _uiRenderMode; // 0x8e
	private GameObject ambisonicSource; // 0x90

	public String moviePath { get; set; }
	public Boolean loop { get; set; }
	public Boolean audioBaseConcatenation { get; set; }
	public Boolean advancedAudio { get; set; }
	public Boolean ambisonics { get; set; }
	public Boolean additiveMode { get; set; }
	public Boolean applyTargetAlpha { get; set; }
	public Boolean uiRenderMode { get; set; }
	protected override UInt32 FilePathLength { get; }
	protected override Boolean initializeWithAdvancedAudio { get; }
	protected override Boolean initializeWithAmbisonics { get; }

	// RVA: 0x4146a40 VA: 0x759675ea40
	public String get_moviePath() { }
	// RVA: 0x4146a48 VA: 0x759675ea48
	public Void set_moviePath(String value) { }
	// RVA: 0x4146ad8 VA: 0x759675ead8
	public Boolean get_loop() { }
	// RVA: 0x4146ae0 VA: 0x759675eae0
	public Void set_loop(Boolean value) { }
	// RVA: 0x4146b6c VA: 0x759675eb6c
	public Boolean get_audioBaseConcatenation() { }
	// RVA: 0x4146b74 VA: 0x759675eb74
	public Void set_audioBaseConcatenation(Boolean value) { }
	// RVA: 0x4146c00 VA: 0x759675ec00
	public Boolean get_advancedAudio() { }
	// RVA: 0x4146c08 VA: 0x759675ec08
	public Void set_advancedAudio(Boolean value) { }
	// RVA: 0x4147034 VA: 0x759675f034
	public Boolean get_ambisonics() { }
	// RVA: 0x4146ca4 VA: 0x759675eca4
	public Void set_ambisonics(Boolean value) { }
	// RVA: 0x414703c VA: 0x759675f03c
	public Boolean get_additiveMode() { }
	// RVA: 0x4147044 VA: 0x759675f044
	public Void set_additiveMode(Boolean value) { }
	// RVA: 0x41470d0 VA: 0x759675f0d0
	public Boolean get_applyTargetAlpha() { }
	// RVA: 0x41470d8 VA: 0x759675f0d8
	public Void set_applyTargetAlpha(Boolean value) { }
	// RVA: 0x4147164 VA: 0x759675f164
	public Boolean get_uiRenderMode() { }
	// RVA: 0x414716c VA: 0x759675f16c
	public Void set_uiRenderMode(Boolean value) { }
	// RVA: 0x41471f8 VA: 0x759675f1f8
	protected override UInt32 get_FilePathLength() { }
	// RVA: 0x4147330 VA: 0x759675f330
	protected override Boolean get_initializeWithAdvancedAudio() { }
	// RVA: 0x4147338 VA: 0x759675f338
	protected override Boolean get_initializeWithAmbisonics() { }
	// RVA: 0x4147340 VA: 0x759675f340
	protected override Void SetDataToPlayer() { }
	// RVA: 0x4146668 VA: 0x759675e668
	public Void .ctor() { }
}
```