# CriAtomRegion

**Namespace:** `CriWare`


## Fields

- `CriAtomEx3dRegion <region3dHn>k__BackingField`


## Properties

- `CriAtomEx3dRegion region3dHn`


## Methods

- `CriAtomEx3dRegion get_region3dHn()`

- `Void set_region3dHn(CriAtomEx3dRegion)`

- `Void Awake()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomRegion : CriMonoBehaviour
{
	private CriAtomEx3dRegion <region3dHn>k__BackingField; // 0x28
	internal List`1 referringSources; // 0x30
	internal List`1 referringListeners; // 0x38
	internal List`1 referringTransceivers; // 0x40

	public CriAtomEx3dRegion region3dHn { get; set; }

	// RVA: 0x4116f34 VA: 0x759672ef34
	public CriAtomEx3dRegion get_region3dHn() { }
	// RVA: 0x4116f3c VA: 0x759672ef3c
	protected Void set_region3dHn(CriAtomEx3dRegion value) { }
	// RVA: 0x4116f44 VA: 0x759672ef44
	private Void Awake() { }
	// RVA: 0x4116f50 VA: 0x759672ef50
	protected override Void OnEnable() { }
	// RVA: 0x4116f74 VA: 0x759672ef74
	private Void OnDestroy() { }
	// RVA: 0x4116f80 VA: 0x759672ef80
	protected virtual Void InternalInitialize() { }
	// RVA: 0x41170c4 VA: 0x759672f0c4
	protected virtual Void InternalFinalize() { }
	// RVA: 0x411776c VA: 0x759672f76c
	protected virtual Void InitializeParameters() { }
	// RVA: 0x41177f0 VA: 0x759672f7f0
	public override Void CriInternalUpdate() { }
	// RVA: 0x41177f4 VA: 0x759672f7f4
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x41177f8 VA: 0x759672f7f8
	public Void .ctor() { }
}
```