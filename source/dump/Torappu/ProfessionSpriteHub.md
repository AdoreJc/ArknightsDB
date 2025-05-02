# ProfessionSpriteHub

**Namespace:** `Torappu`


## Methods

- `Boolean TryGetSprite(ProfessionCategory, out)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ProfessionSpriteHub : MonoISpriteHub
{
	private DataPair[] _sprites; // 0x18
	private Dictionary`2 m_spriteHub; // 0x20


	// RVA: 0x310563c VA: 0x759571d63c
	public Boolean TryGetSprite(ProfessionCategory key, out Sprite sprite) { }
	// RVA: 0x31056ac VA: 0x759571d6ac
	private Void _InitIfNot() { }
	// RVA: 0x3105808 VA: 0x759571d808
	public Void .ctor() { }
}
```