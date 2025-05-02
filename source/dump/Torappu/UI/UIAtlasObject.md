# UIAtlasObject

**Namespace:** `Torappu.UI`


## Fields

- `String _workDir`

- `Boolean _alphaSplit`

- `AtlasSize _maxSize`

- `AtlasCheckInfo _sign`


## Methods

- `Void _InitIfNot()`

- `SpriteRenderData GUID2Sprite(String)`

- `SpriteRenderData GetSpriteByName(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAtlasObject : ScriptableObject, IHotfixable
{
	private List`1 _sprites; // 0x18
	private List`1 _atlases; // 0x20
	private String _workDir; // 0x28
	private Boolean _alphaSplit; // 0x30
	private AtlasSize _maxSize; // 0x34
	private AtlasCheckInfo _sign; // 0x38
	private Dictionary`2 m_guidToSprite; // 0x40
	private Dictionary`2 m_nameToSprite; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GUID2Sprite; // 0x8
	private static DelegateBridge __Hotfix0_GetSpriteByName; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x210c8a4 VA: 0x75947248a4
	private Void _InitIfNot() { }
	// RVA: 0x210a19c VA: 0x759472219c
	public SpriteRenderData GUID2Sprite(String guid) { }
	// RVA: 0x210cae0 VA: 0x7594724ae0
	public SpriteRenderData GetSpriteByName(String name) { }
	// RVA: 0x210cc44 VA: 0x7594724c44
	public Void .ctor() { }
}
```