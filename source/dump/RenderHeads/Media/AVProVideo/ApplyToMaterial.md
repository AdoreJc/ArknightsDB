# ApplyToMaterial

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _media`

- `Texture2D _defaultTexture`

- `Material _material`

- `String _texturePropertyName`

- `Vector2 _offset`

- `Vector2 _scale`

- `Boolean _isDirty`

- `Texture _lastTextureApplied`

- `Int32 _propTexture`

- `Texture _originalTexture`

- `Vector2 _originalScale`

- `Vector2 _originalOffset`


## Properties

- `MediaPlayer Player`

- `Texture2D DefaultTexture`

- `Material Material`

- `String TexturePropertyName`

- `Vector2 Offset`

- `Vector2 Scale`


## Methods

- `MediaPlayer get_Player()`

- `Void set_Player(MediaPlayer)`

- `Texture2D get_DefaultTexture()`

- `Void set_DefaultTexture(Texture2D)`

- `Material get_Material()`

- `Void set_Material(Material)`

- `String get_TexturePropertyName()`

- `Void set_TexturePropertyName(String)`

- `Vector2 get_Offset()`

- `Void set_Offset(Vector2)`

- `Vector2 get_Scale()`

- `Void set_Scale(Vector2)`

- `Void Awake()`

- `Void ChangeMediaPlayer(MediaPlayer)`

- `Void ForceUpdate()`

- `Void OnMediaPlayerEvent(MediaPlayer, EventType, ErrorCode)`

- `Void LateUpdate()`

- `Void ApplyMapping(Texture, Boolean, Int32)`

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void SaveProperties()`

- `Void RestoreProperties()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class ApplyToMaterial : MonoBehaviour
{
	private MediaPlayer _media; // 0x18
	private Texture2D _defaultTexture; // 0x20
	private Material _material; // 0x28
	private String _texturePropertyName; // 0x30
	private Vector2 _offset; // 0x38
	private Vector2 _scale; // 0x40
	private Boolean _isDirty; // 0x48
	private Texture _lastTextureApplied; // 0x50
	private Int32 _propTexture; // 0x58
	private Texture _originalTexture; // 0x60
	private Vector2 _originalScale; // 0x68
	private Vector2 _originalOffset; // 0x70
	private static Int32 _propStereo; // 0x0
	private static Int32 _propAlphaPack; // 0x4
	private static Int32 _propApplyGamma; // 0x8
	private static Int32 _propLayout; // 0xc
	private static Int32 _propCroppingScalars; // 0x10
	private const String PropChromaTexName; // 0x0
	private static Int32 _propChromaTex; // 0x14
	private const String PropYpCbCrTransformName; // 0x0
	private static Int32 _propYpCbCrTransform; // 0x18
	private const String PropUseYpCbCrName; // 0x0
	private static Int32 _propUseYpCbCr; // 0x1c

	public MediaPlayer Player { get; set; }
	public Texture2D DefaultTexture { get; set; }
	public Material Material { get; set; }
	public String TexturePropertyName { get; set; }
	public Vector2 Offset { get; set; }
	public Vector2 Scale { get; set; }

	// RVA: 0x6663a34 VA: 0x7598c7ba34
	public MediaPlayer get_Player() { }
	// RVA: 0x6663a3c VA: 0x7598c7ba3c
	public Void set_Player(MediaPlayer value) { }
	// RVA: 0x6663bf4 VA: 0x7598c7bbf4
	public Texture2D get_DefaultTexture() { }
	// RVA: 0x6663bfc VA: 0x7598c7bbfc
	public Void set_DefaultTexture(Texture2D value) { }
	// RVA: 0x6663c8c VA: 0x7598c7bc8c
	public Material get_Material() { }
	// RVA: 0x6663c94 VA: 0x7598c7bc94
	public Void set_Material(Material value) { }
	// RVA: 0x6663d24 VA: 0x7598c7bd24
	public String get_TexturePropertyName() { }
	// RVA: 0x6663d2c VA: 0x7598c7bd2c
	public Void set_TexturePropertyName(String value) { }
	// RVA: 0x6663d84 VA: 0x7598c7bd84
	public Vector2 get_Offset() { }
	// RVA: 0x6663d8c VA: 0x7598c7bd8c
	public Void set_Offset(Vector2 value) { }
	// RVA: 0x6663dc4 VA: 0x7598c7bdc4
	public Vector2 get_Scale() { }
	// RVA: 0x6663dcc VA: 0x7598c7bdcc
	public Void set_Scale(Vector2 value) { }
	// RVA: 0x6663e04 VA: 0x7598c7be04
	private Void Awake() { }
	// RVA: 0x6663a40 VA: 0x7598c7ba40
	private Void ChangeMediaPlayer(MediaPlayer player) { }
	// RVA: 0x66640a8 VA: 0x7598c7c0a8
	public Void ForceUpdate() { }
	// RVA: 0x66645a8 VA: 0x7598c7c5a8
	private Void OnMediaPlayerEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x66640b4 VA: 0x7598c7c0b4
	private Void LateUpdate() { }
	// RVA: 0x66645c8 VA: 0x7598c7c5c8
	private Void ApplyMapping(Texture texture, Boolean requiresYFlip, Int32 plane) { }
	// RVA: 0x6664d4c VA: 0x7598c7cd4c
	private Void Start() { }
	// RVA: 0x6664e88 VA: 0x7598c7ce88
	private Void OnEnable() { }
	// RVA: 0x6664eb8 VA: 0x7598c7ceb8
	private Void OnDisable() { }
	// RVA: 0x6664d64 VA: 0x7598c7cd64
	private Void SaveProperties() { }
	// RVA: 0x6664ebc VA: 0x7598c7cebc
	private Void RestoreProperties() { }
	// RVA: 0x6664fd0 VA: 0x7598c7cfd0
	public Void .ctor() { }
}
```