# DisplayIMGUI

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _mediaPlayer`

- `Boolean _displayInEditor`

- `ScaleMode _scaleMode`

- `Color _color`

- `Boolean _alphaBlend`

- `Boolean _useDepth`

- `Int32 _depth`

- `Boolean _fullScreen`

- `Single _x`

- `Single _y`

- `Single _width`

- `Single _height`

- `Material _material`


## Methods

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Shader GetRequiredShader()`

- `Void Update()`

- `Void OnGUI()`

- `Rect GetRect()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class DisplayIMGUI : MonoBehaviour
{
	private const String PropChromaTexName; // 0x0
	private const String PropYpCbCrTransformName; // 0x0
	public MediaPlayer _mediaPlayer; // 0x18
	public Boolean _displayInEditor; // 0x20
	public ScaleMode _scaleMode; // 0x24
	public Color _color; // 0x28
	public Boolean _alphaBlend; // 0x38
	private Boolean _useDepth; // 0x39
	public Int32 _depth; // 0x3c
	public Boolean _fullScreen; // 0x40
	public Single _x; // 0x44
	public Single _y; // 0x48
	public Single _width; // 0x4c
	public Single _height; // 0x50
	private static Int32 _propAlphaPack; // 0x0
	private static Int32 _propVertScale; // 0x4
	private static Int32 _propApplyGamma; // 0x8
	private static Int32 _propChromaTex; // 0xc
	private static Int32 _propYpCbCrTransform; // 0x10
	private static Shader _shaderAlphaPacking; // 0x18
	private Material _material; // 0x58


	// RVA: 0x667abdc VA: 0x7598c92bdc
	private Void Awake() { }
	// RVA: 0x667ad0c VA: 0x7598c92d0c
	private Void Start() { }
	// RVA: 0x667ae5c VA: 0x7598c92e5c
	private Void OnDestroy() { }
	// RVA: 0x667aefc VA: 0x7598c92efc
	private Shader GetRequiredShader() { }
	// RVA: 0x667b14c VA: 0x7598c9314c
	private Void Update() { }
	// RVA: 0x667b44c VA: 0x7598c9344c
	private Void OnGUI() { }
	// RVA: 0x667bcac VA: 0x7598c93cac
	public Rect GetRect() { }
	// RVA: 0x667bd8c VA: 0x7598c93d8c
	public Void .ctor() { }
}
```