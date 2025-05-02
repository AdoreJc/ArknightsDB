# UIAtlasTextureRef

**Namespace:** `Torappu.UI.Atlas`


## Fields

- `AtlasInfo _atlas`

- `Int32 _index`

- `AtlasCheckInfo _sign`


## Methods

- `Void _InitIfNot()`

- `SpriteRenderData GetRenderData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Atlas
public class UIAtlasTextureRef : ScriptableObject, IHotfixable
{
	private List`1 _sprites; // 0x18
	private AtlasInfo _atlas; // 0x20
	private Int32 _index; // 0x28
	private AtlasCheckInfo _sign; // 0x30
	private Dictionary`2 m_spriteMap; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetRenderData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c5fc18 VA: 0x7595277c18
	private Void _InitIfNot() { }
	// RVA: 0x2c5fe00 VA: 0x7595277e00
	public SpriteRenderData GetRenderData(String id) { }
	// RVA: 0x2c6007c VA: 0x759527807c
	public Void .ctor() { }
}
```