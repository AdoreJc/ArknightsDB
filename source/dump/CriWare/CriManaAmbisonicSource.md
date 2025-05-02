# CriManaAmbisonicSource

**Namespace:** `CriWare`


## Fields

- `CriAtomEx3dSource atomEx3DsourceForAmbisonics`

- `Vector3 ambisonicSourceOrientationFront`

- `Vector3 ambisonicSourceOrientationTop`

- `Vector3 lastEulerOfAmbisonicSource`


## Methods

- `Void ForceUpdateAmbisonicSourceOrientation()`

- `Void UpdateAmbisonicSourceOrientation()`

- `Void RoatateAmbisonicSourceOrientationByTransformOfChild(ref)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriManaAmbisonicSource : CriMonoBehaviour
{
	private CriAtomEx3dSource atomEx3DsourceForAmbisonics; // 0x28
	private Vector3 ambisonicSourceOrientationFront; // 0x30
	private Vector3 ambisonicSourceOrientationTop; // 0x3c
	private Vector3 lastEulerOfAmbisonicSource; // 0x48


	// RVA: 0x4145db4 VA: 0x759675ddb4
	public override Void CriInternalUpdate() { }
	// RVA: 0x4145e3c VA: 0x759675de3c
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4145e40 VA: 0x759675de40
	protected override Void OnEnable() { }
	// RVA: 0x4145f94 VA: 0x759675df94
	private Void ForceUpdateAmbisonicSourceOrientation() { }
	// RVA: 0x4145db8 VA: 0x759675ddb8
	private Void UpdateAmbisonicSourceOrientation() { }
	// RVA: 0x4145ff8 VA: 0x759675dff8
	private Void RoatateAmbisonicSourceOrientationByTransformOfChild(ref Vector3 input_euler) { }
	// RVA: 0x414629c VA: 0x759675e29c
	public Void .ctor() { }
}
```