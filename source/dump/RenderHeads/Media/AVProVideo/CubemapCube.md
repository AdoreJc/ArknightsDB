# CubemapCube

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `Mesh _mesh`

- `MeshRenderer _renderer`

- `Material _material`

- `MediaPlayer _mediaPlayer`

- `Single expansion_coeff`

- `Layout _layout`

- `Texture _texture`

- `Boolean _verticalFlip`

- `Int32 _textureWidth`

- `Int32 _textureHeight`


## Properties

- `MediaPlayer Player`


## Methods

- `Void set_Player(MediaPlayer)`

- `MediaPlayer get_Player()`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void LateUpdate()`

- `Void BuildMesh()`

- `Void UpdateMeshUV(Int32, Int32, Boolean)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class CubemapCube : MonoBehaviour
{
	private Mesh _mesh; // 0x18
	protected MeshRenderer _renderer; // 0x20
	protected Material _material; // 0x28
	private MediaPlayer _mediaPlayer; // 0x30
	private Single expansion_coeff; // 0x38
	private Layout _layout; // 0x3c
	private Texture _texture; // 0x40
	private Boolean _verticalFlip; // 0x48
	private Int32 _textureWidth; // 0x4c
	private Int32 _textureHeight; // 0x50
	private static Int32 _propApplyGamma; // 0x0
	private static Int32 _propStereo; // 0x4
	private static Int32 _propUseYpCbCr; // 0x8
	private const String PropChromaTexName; // 0x0
	private static Int32 _propChromaTex; // 0xc
	private const String PropYpCbCrTransformName; // 0x0
	private static Int32 _propYpCbCrTransform; // 0x10

	public MediaPlayer Player { get; set; }

	// RVA: 0x6677cd0 VA: 0x7598c8fcd0
	public Void set_Player(MediaPlayer value) { }
	// RVA: 0x6677cd8 VA: 0x7598c8fcd8
	public MediaPlayer get_Player() { }
	// RVA: 0x6677ce0 VA: 0x7598c8fce0
	private Void Awake() { }
	// RVA: 0x6677e2c VA: 0x7598c8fe2c
	private Void Start() { }
	// RVA: 0x6678614 VA: 0x7598c90614
	private Void OnDestroy() { }
	// RVA: 0x6678774 VA: 0x7598c90774
	private Void LateUpdate() { }
	// RVA: 0x6677fd4 VA: 0x7598c8ffd4
	private Void BuildMesh() { }
	// RVA: 0x6678f4c VA: 0x7598c90f4c
	private Void UpdateMeshUV(Int32 textureWidth, Int32 textureHeight, Boolean flipY) { }
	// RVA: 0x6679360 VA: 0x7598c91360
	public Void .ctor() { }
}
```