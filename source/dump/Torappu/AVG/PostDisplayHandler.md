# PostDisplayHandler

**Namespace:** `Torappu.AVG`


## Fields

- `PostDisplayItem m_item`


## Properties

- `Boolean isDisposed`


## Methods

- `PostDisplayKey GetKey()`

- `Void SetTextures(Textures)`

- `Boolean get_isDisposed()`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class PostDisplayHandler : IDisposable
{
	private PostDisplayItem m_item; // 0x10

	public Boolean isDisposed { get; }

	// RVA: 0x3e984b8 VA: 0x75964b04b8
	public Void .ctor(PostDisplayItem item) { }
	// RVA: 0x3e9c344 VA: 0x75964b4344
	public PostDisplayKey GetKey() { }
	// RVA: 0x3e9c2f0 VA: 0x75964b42f0
	public Void SetTextures(Textures textures) { }
	// RVA: 0x3e9c36c VA: 0x75964b436c
	public Boolean get_isDisposed() { }
	// RVA: 0x3e9c38c VA: 0x75964b438c
	public Void Dispose() { }
}
```