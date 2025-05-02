# UpdateStereoMaterial

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `Camera _camera`

- `MeshRenderer _renderer`

- `Graphic _uGuiComponent`

- `Material _material`

- `StereoEye _forceEyeMode`

- `StereoEye _setForceEyeMode`

- `Camera _foundCamera`


## Properties

- `StereoEye ForceEyeMode`


## Methods

- `StereoEye get_ForceEyeMode()`

- `Void set_ForceEyeMode(StereoEye)`

- `Void Awake()`

- `Void SetupMaterial(Material, Camera)`

- `Void LateUpdate()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class UpdateStereoMaterial : MonoBehaviour
{
	public Camera _camera; // 0x18
	public MeshRenderer _renderer; // 0x20
	public Graphic _uGuiComponent; // 0x28
	public Material _material; // 0x30
	private StereoEye _forceEyeMode; // 0x38
	private static Int32 _cameraPositionId; // 0x0
	private static Int32 _viewMatrixId; // 0x4
	private StereoEye _setForceEyeMode; // 0x3c
	private Camera _foundCamera; // 0x40

	public StereoEye ForceEyeMode { get; set; }

	// RVA: 0x66892c0 VA: 0x7598ca12c0
	public StereoEye get_ForceEyeMode() { }
	// RVA: 0x66892c8 VA: 0x7598ca12c8
	public Void set_ForceEyeMode(StereoEye value) { }
	// RVA: 0x66892d0 VA: 0x7598ca12d0
	private Void Awake() { }
	// RVA: 0x6689408 VA: 0x7598ca1408
	private Void SetupMaterial(Material m, Camera camera) { }
	// RVA: 0x6689540 VA: 0x7598ca1540
	private Void LateUpdate() { }
	// RVA: 0x66898d0 VA: 0x7598ca18d0
	public Void .ctor() { }
}
```