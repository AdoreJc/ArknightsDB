# SpriteHub

**Namespace:** `Torappu`


## Fields

- `Boolean _caseSensitive`


## Methods

- `Boolean TryGetSprite(String, out)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SpriteHub : MonoISpriteHub
{
	private Boolean _caseSensitive; // 0x18
	private Sprite[] _sprites; // 0x20
	private Dictionary`2 m_spriteHub; // 0x28


	// RVA: 0x2f36bc4 VA: 0x759554ebc4
	public IEnumerator`1 GetEnumerator() { }
	// RVA: 0x2f36f00 VA: 0x759554ef00
	public Boolean TryGetSprite(String id, out Sprite sprite) { }
	// RVA: 0x2f36c60 VA: 0x759554ec60
	private Void _InitIfNot() { }
	// RVA: 0x2f36b50 VA: 0x759554eb50
	public Void .ctor() { }
}
```