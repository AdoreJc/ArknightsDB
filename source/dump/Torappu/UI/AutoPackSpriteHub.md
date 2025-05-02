# AutoPackSpriteHub

**Namespace:** `Torappu.UI`


## Fields

- `String _rootPackingTag`

- `Int32 _cntPerAtlas`

- `PicSize _standardPicSize`

- `CompressType _compressType`

- `AtlasSize _atlasSize`

- `MeshType _meshType`

- `Boolean _useCntPerAtlas`

- `Int32 _maxFileSize`

- `TexSize _maxTextureSize`

- `String _extraTagRegex`

- `ExtractTagConfig _extractTagConfig`

- `String _atlasOutputPath`

- `String _configName`


## Methods

- `Void _InitMapIfNot()`

- `Void CheckReferences()`

- `Void Bake()`

- `Boolean ContainsKey(String)`

- `Boolean TryGetValue(String, out)`

- `Boolean TryLoadSprite(String, ILoadAsset, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AutoPackSpriteHub : ScriptableObject, ISpriteHub
{
	private const Int32 DEFAULT_MAX_FILE_SIZE; // 0x0
	private String _rootPackingTag; // 0x18
	private Int32 _cntPerAtlas; // 0x20
	private PicSize _standardPicSize; // 0x24
	private List`1 _extraPicSize; // 0x30
	private CompressType _compressType; // 0x38
	private AtlasSize _atlasSize; // 0x3c
	private MeshType _meshType; // 0x40
	private Boolean _useCntPerAtlas; // 0x44
	private Int32 _maxFileSize; // 0x48
	private TexSize _maxTextureSize; // 0x4c
	private String _extraTagRegex; // 0x50
	private ExtractTagConfig _extractTagConfig; // 0x58
	private String _atlasOutputPath; // 0x60
	private String _configName; // 0x68
	private List`1 _keys; // 0x70
	private List`1 _values; // 0x78
	private Dictionary`2 m_map; // 0x80


	// RVA: 0x21c0014 VA: 0x75947d8014
	private Void _InitMapIfNot() { }
	// RVA: 0x21c02bc VA: 0x75947d82bc
	public Void CheckReferences() { }
	// RVA: 0x21c02c0 VA: 0x75947d82c0
	public Void Bake() { }
	// RVA: 0x21c02c4 VA: 0x75947d82c4
	public Boolean ContainsKey(String key) { }
	// RVA: 0x21c0344 VA: 0x75947d8344
	public Boolean TryGetValue(String key, out String value) { }
	// RVA: 0x21c03e8 VA: 0x75947d83e8
	public Boolean TryLoadSprite(String id, ILoadAsset assetLoader, out Sprite result) { }
	// RVA: 0x21c0554 VA: 0x75947d8554
	public Void .ctor() { }
}
```