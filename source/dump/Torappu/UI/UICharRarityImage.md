# UICharRarityImage

**Namespace:** `Torappu.UI`


## Fields

- `Image m_image`

- `Boolean m_isInited`

- `RarityRank m_rarityCache`


## Properties

- `Image image`


## Methods

- `Image get_image()`

- `Void Render(RarityRank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharRarityImage : MonoBehaviour
{
	private SpriteConfig[] _spriteConfigs; // 0x18
	private Image m_image; // 0x20
	private Boolean m_isInited; // 0x28
	private RarityRank m_rarityCache; // 0x2c

	protected Image image { get; }

	// RVA: 0x2139400 VA: 0x7594751400
	protected Image get_image() { }
	// RVA: 0x212b28c VA: 0x759474328c
	public Void Render(RarityRank rarity) { }
	// RVA: 0x21394a8 VA: 0x75947514a8
	public Void .ctor() { }
}
```