# DynamicSpriteHolder

**Namespace:** `Torappu.UI.DynamicSprite`


## Fields

- `String _packingTag`


## Methods

- `Void _InitIfNot()`

- `Sprite GetSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DynamicSprite
public class DynamicSpriteHolder : MonoBehaviour
{
	private String _packingTag; // 0x18
	private List`1 _sprites; // 0x20
	private Dictionary`2 m_spriteHub; // 0x28


	// RVA: 0x2c46900 VA: 0x759525e900
	private Void _InitIfNot() { }
	// RVA: 0x2c466f4 VA: 0x759525e6f4
	public Sprite GetSprite(String id) { }
	// RVA: 0x2c46a34 VA: 0x759525ea34
	public Void .ctor() { }
}
```