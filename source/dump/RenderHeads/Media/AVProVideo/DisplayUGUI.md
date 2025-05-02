# DisplayUGUI

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _mediaPlayer`

- `Rect m_UVRect`

- `Boolean _setNativeSize`

- `ScaleMode _scaleMode`

- `Boolean _noDefaultDisplay`

- `Boolean _displayInEditor`

- `Texture _defaultTexture`

- `Int32 _lastWidth`

- `Int32 _lastHeight`

- `Boolean _flipY`

- `Texture _lastTexture`

- `Boolean _userMaterial`

- `Material _material`


## Properties

- `MediaPlayer CurrentMediaPlayer`

- `Rect uvRect`


## Methods

- `Shader EnsureAndroidOESShader()`

- `Shader GetRequiredShader()`

- `Boolean HasValidTexture()`

- `Void UpdateInternalMaterial()`

- `Void LateUpdate()`

- `MediaPlayer get_CurrentMediaPlayer()`

- `Void set_CurrentMediaPlayer(MediaPlayer)`

- `Rect get_uvRect()`

- `Void set_uvRect(Rect)`

- `Void _OnFillVBO(List`1)`

- `Vector4 GetDrawingDimensions(ScaleMode, ref)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class DisplayUGUI : MaskableGraphic
{
	public MediaPlayer _mediaPlayer; // 0xe0
	public Rect m_UVRect; // 0xe8
	public Boolean _setNativeSize; // 0xf8
	public ScaleMode _scaleMode; // 0xfc
	public Boolean _noDefaultDisplay; // 0x100
	public Boolean _displayInEditor; // 0x101
	public Texture _defaultTexture; // 0x108
	private Int32 _lastWidth; // 0x110
	private Int32 _lastHeight; // 0x114
	private Boolean _flipY; // 0x118
	private Texture _lastTexture; // 0x120
	private static Shader _shaderStereoPacking; // 0x0
	private static Shader _shaderAlphaPacking; // 0x8
	private static Shader _shaderAndroidOES; // 0x10
	private static Int32 _propAlphaPack; // 0x18
	private static Int32 _propVertScale; // 0x1c
	private static Int32 _propStereo; // 0x20
	private static Int32 _propApplyGamma; // 0x24
	private static Int32 _propUseYpCbCr; // 0x28
	private const String PropChromaTexName; // 0x0
	private static Int32 _propChromaTex; // 0x2c
	private const String PropYpCbCrTransformName; // 0x0
	private static Int32 _propYpCbCrTransform; // 0x30
	private static Int32 _propCroppingScalars; // 0x34
	private Boolean _userMaterial; // 0x128
	private Material _material; // 0x130
	private List`1 _vertices; // 0x138
	private static List`1 QuadIndices; // 0x38

	public override Texture mainTexture { get; }
	public MediaPlayer CurrentMediaPlayer { get; set; }
	public Rect uvRect { get; set; }

	// RVA: 0x667bdb8 VA: 0x7598c93db8
	protected override Void Awake() { }
	// RVA: 0x667bfd0 VA: 0x7598c93fd0
	private static Boolean HasMask(GameObject obj) { }
	// RVA: 0x667c10c VA: 0x7598c9410c
	private static Shader EnsureShader(Shader shader, String name) { }
	// RVA: 0x667c214 VA: 0x7598c94214
	private static Shader EnsureAlphaPackingShader() { }
	// RVA: 0x667c2ac VA: 0x7598c942ac
	private static Shader EnsureStereoPackingShader() { }
	// RVA: 0x667c348 VA: 0x7598c94348
	private Shader EnsureAndroidOESShader() { }
	// RVA: 0x667c3e0 VA: 0x7598c943e0
	protected override Void Start() { }
	// RVA: 0x667c4d0 VA: 0x7598c944d0
	protected override Void OnDestroy() { }
	// RVA: 0x667c58c VA: 0x7598c9458c
	private Shader GetRequiredShader() { }
	// RVA: 0x667c85c VA: 0x7598c9485c
	public override Texture get_mainTexture() { }
	// RVA: 0x667c9e8 VA: 0x7598c949e8
	public Boolean HasValidTexture() { }
	// RVA: 0x667cb30 VA: 0x7598c94b30
	private Void UpdateInternalMaterial() { }
	// RVA: 0x667cd14 VA: 0x7598c94d14
	private Void LateUpdate() { }
	// RVA: 0x667d734 VA: 0x7598c95734
	public MediaPlayer get_CurrentMediaPlayer() { }
	// RVA: 0x667d73c VA: 0x7598c9573c
	public Void set_CurrentMediaPlayer(MediaPlayer value) { }
	// RVA: 0x667d7e4 VA: 0x7598c957e4
	public Rect get_uvRect() { }
	// RVA: 0x667d7f0 VA: 0x7598c957f0
	public Void set_uvRect(Rect value) { }
	// RVA: 0x667d870 VA: 0x7598c95870
	public override Void SetNativeSize() { }
	// RVA: 0x667dbcc VA: 0x7598c95bcc
	protected override Void OnPopulateMesh(VertexHelper vh) { }
	// RVA: 0x667e754 VA: 0x7598c96754
	protected override Void OnFillVBO(List`1 vbo) { }
	// RVA: 0x667dc5c VA: 0x7598c95c5c
	private Void _OnFillVBO(List`1 vbo) { }
	// RVA: 0x667e758 VA: 0x7598c96758
	private Vector4 GetDrawingDimensions(ScaleMode scaleMode, ref Rect uvRect) { }
	// RVA: 0x667ee1c VA: 0x7598c96e1c
	public Void .ctor() { }
	// RVA: 0x667eef4 VA: 0x7598c96ef4
	private static Void .cctor() { }
}
```