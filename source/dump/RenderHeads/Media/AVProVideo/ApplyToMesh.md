# ApplyToMesh

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _media`

- `Texture2D _defaultTexture`

- `Renderer _mesh`

- `String _texturePropertyName`

- `Vector2 _offset`

- `Vector2 _scale`

- `Boolean _isDirty`

- `Texture _lastTextureApplied`

- `Int32 _propTexture`


## Properties

- `MediaPlayer Player`

- `Texture2D DefaultTexture`

- `Renderer MeshRenderer`

- `String TexturePropertyName`

- `Vector2 Offset`

- `Vector2 Scale`


## Methods

- `MediaPlayer get_Player()`

- `Void set_Player(MediaPlayer)`

- `Texture2D get_DefaultTexture()`

- `Void set_DefaultTexture(Texture2D)`

- `Renderer get_MeshRenderer()`

- `Void set_MeshRenderer(Renderer)`

- `String get_TexturePropertyName()`

- `Void set_TexturePropertyName(String)`

- `Vector2 get_Offset()`

- `Void set_Offset(Vector2)`

- `Vector2 get_Scale()`

- `Void set_Scale(Vector2)`

- `Void Awake()`

- `Void ForceUpdate()`

- `Void OnMediaPlayerEvent(MediaPlayer, EventType, ErrorCode)`

- `Void ChangeMediaPlayer(MediaPlayer)`

- `Void LateUpdate()`

- `Void ApplyMapping(Texture, Boolean, Int32)`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class ApplyToMesh : MonoBehaviour
{
	private MediaPlayer _media; // 0x18
	private Texture2D _defaultTexture; // 0x20
	private Renderer _mesh; // 0x28
	private String _texturePropertyName; // 0x30
	private Vector2 _offset; // 0x38
	private Vector2 _scale; // 0x40
	private Boolean _isDirty; // 0x48
	private Texture _lastTextureApplied; // 0x50
	private Int32 _propTexture; // 0x58
	private static Int32 _propStereo; // 0x0
	private static Int32 _propAlphaPack; // 0x4
	private static Int32 _propApplyGamma; // 0x8
	private static Int32 _propLayout; // 0xc
	private const String PropChromaTexName; // 0x0
	private static Int32 _propChromaTex; // 0x10
	private const String PropYpCbCrTransformName; // 0x0
	private static Int32 _propYpCbCrTransform; // 0x14
	private const String PropUseYpCbCrName; // 0x0
	private static Int32 _propUseYpCbCr; // 0x18
	private static Int32 _propCroppingScalars; // 0x1c

	public MediaPlayer Player { get; set; }
	public Texture2D DefaultTexture { get; set; }
	public Renderer MeshRenderer { get; set; }
	public String TexturePropertyName { get; set; }
	public Vector2 Offset { get; set; }
	public Vector2 Scale { get; set; }

	// RVA: 0x6675fdc VA: 0x7598c8dfdc
	public MediaPlayer get_Player() { }
	// RVA: 0x6675fe4 VA: 0x7598c8dfe4
	public Void set_Player(MediaPlayer value) { }
	// RVA: 0x6676194 VA: 0x7598c8e194
	public Texture2D get_DefaultTexture() { }
	// RVA: 0x667619c VA: 0x7598c8e19c
	public Void set_DefaultTexture(Texture2D value) { }
	// RVA: 0x667622c VA: 0x7598c8e22c
	public Renderer get_MeshRenderer() { }
	// RVA: 0x6676234 VA: 0x7598c8e234
	public Void set_MeshRenderer(Renderer value) { }
	// RVA: 0x66762c4 VA: 0x7598c8e2c4
	public String get_TexturePropertyName() { }
	// RVA: 0x66762cc VA: 0x7598c8e2cc
	public Void set_TexturePropertyName(String value) { }
	// RVA: 0x6676324 VA: 0x7598c8e324
	public Vector2 get_Offset() { }
	// RVA: 0x667632c VA: 0x7598c8e32c
	public Void set_Offset(Vector2 value) { }
	// RVA: 0x6676364 VA: 0x7598c8e364
	public Vector2 get_Scale() { }
	// RVA: 0x667636c VA: 0x7598c8e36c
	public Void set_Scale(Vector2 value) { }
	// RVA: 0x66763a4 VA: 0x7598c8e3a4
	private Void Awake() { }
	// RVA: 0x66766bc VA: 0x7598c8e6bc
	public Void ForceUpdate() { }
	// RVA: 0x6676b38 VA: 0x7598c8eb38
	private Void OnMediaPlayerEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x6675fe8 VA: 0x7598c8dfe8
	private Void ChangeMediaPlayer(MediaPlayer player) { }
	// RVA: 0x66766c8 VA: 0x7598c8e6c8
	private Void LateUpdate() { }
	// RVA: 0x6676b58 VA: 0x7598c8eb58
	private Void ApplyMapping(Texture texture, Boolean requiresYFlip, Int32 plane) { }
	// RVA: 0x667720c VA: 0x7598c8f20c
	private Void OnEnable() { }
	// RVA: 0x6677370 VA: 0x7598c8f370
	private Void OnDisable() { }
	// RVA: 0x6677380 VA: 0x7598c8f380
	private Void OnDestroy() { }
	// RVA: 0x6677388 VA: 0x7598c8f388
	public Void .ctor() { }
}
```