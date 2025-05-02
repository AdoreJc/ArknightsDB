# CriFsInstallRequest

**Namespace:** `CriWare`


## Fields

- `String <sourcePath>k__BackingField`

- `String <destinationPath>k__BackingField`

- `Single <progress>k__BackingField`


## Properties

- `String sourcePath`

- `String destinationPath`

- `Single progress`


## Methods

- `String get_sourcePath()`

- `Void set_sourcePath(String)`

- `String get_destinationPath()`

- `Void set_destinationPath(String)`

- `Single get_progress()`

- `Void set_progress(Single)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsInstallRequest : CriFsRequest
{
	private String <sourcePath>k__BackingField; // 0x40
	private String <destinationPath>k__BackingField; // 0x48
	private Single <progress>k__BackingField; // 0x50

	public String sourcePath { get; set; }
	public String destinationPath { get; set; }
	public Single progress { get; set; }

	// RVA: 0x4140444 VA: 0x7596758444
	public String get_sourcePath() { }
	// RVA: 0x414044c VA: 0x759675844c
	protected Void set_sourcePath(String value) { }
	// RVA: 0x4140454 VA: 0x7596758454
	public String get_destinationPath() { }
	// RVA: 0x414045c VA: 0x759675845c
	protected Void set_destinationPath(String value) { }
	// RVA: 0x4140464 VA: 0x7596758464
	public Single get_progress() { }
	// RVA: 0x414046c VA: 0x759675846c
	protected Void set_progress(Single value) { }
	// RVA: 0x4140474 VA: 0x7596758474
	public Void .ctor() { }
}
```