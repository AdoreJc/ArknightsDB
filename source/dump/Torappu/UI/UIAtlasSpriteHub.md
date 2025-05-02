# UIAtlasSpriteHub

**Namespace:** `Torappu.UI`


## Fields

- `String _inputSpriteDir`

- `String _outputAtlasDir`

- `String _rootAtlasName`

- `PicSize _spriteSize`

- `Int32 _cntPerAtlas`

- `AtlasSize _maxAtlasSize`


## Methods

- `Void _InitIfNot()`

- `Boolean TryGetAtlasPath(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAtlasSpriteHub : ScriptableObject, IHotfixable
{
	private List`1 _sprites; // 0x18
	private List`1 _atlases; // 0x20
	private String _inputSpriteDir; // 0x28
	private String _outputAtlasDir; // 0x30
	private String _rootAtlasName; // 0x38
	private PicSize _spriteSize; // 0x40
	private Int32 _cntPerAtlas; // 0x48
	private AtlasSize _maxAtlasSize; // 0x4c
	private Dictionary`2 m_spriteToTexture; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_TryGetAtlasPath; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x210ccc4 VA: 0x7594724cc4
	private Void _InitIfNot() { }
	// RVA: 0x210cecc VA: 0x7594724ecc
	public Boolean TryGetAtlasPath(String id, out String resPath) { }
	// RVA: 0x210cfb4 VA: 0x7594724fb4
	public Void .ctor() { }
}
```