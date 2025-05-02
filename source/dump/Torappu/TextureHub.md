# TextureHub

**Namespace:** `Torappu`


## Fields

- `Texture _default`


## Methods

- `Boolean TryGetTexture(String, out)`

- `Texture GetTextureOrDefault(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TextureHub : MonoBehaviour
{
	private Texture _default; // 0x18
	private Texture[] _textures; // 0x20
	private Dictionary`2 m_textureHub; // 0x28


	// RVA: 0x3108360 VA: 0x7595720360
	public Boolean TryGetTexture(String id, out Texture tex) { }
	// RVA: 0x3108568 VA: 0x7595720568
	public Texture GetTextureOrDefault(String id) { }
	// RVA: 0x3108404 VA: 0x7595720404
	private Void _InitIfNot() { }
	// RVA: 0x31085a0 VA: 0x75957205a0
	public Void .ctor() { }
}
```