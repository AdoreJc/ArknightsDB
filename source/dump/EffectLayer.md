# EffectLayer

**Namespace:** ` `


## Fields

- `RawImage _layerImage`

- `Camera _layerCamera`

- `BlendMode _srcBlend`

- `BlendMode _dstBlend`

- `Int32 _renderTextureMaxSize`

- `RenderTexture m_rt`

- `Material m_mt`


## Methods

- `Void Setup(CharacterTransView)`

- `Void Shutdown()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EffectLayer
{
	private const String SHADER_PATH; // 0x0
	private RawImage _layerImage; // 0x10
	private Camera _layerCamera; // 0x18
	private BlendMode _srcBlend; // 0x20
	private BlendMode _dstBlend; // 0x24
	private Int32 _renderTextureMaxSize; // 0x28
	private RenderTexture m_rt; // 0x30
	private Material m_mt; // 0x38


	// RVA: 0x2d6c494 VA: 0x7595384494
	public Void Setup(CharacterTransView transView) { }
	// RVA: 0x2d6c90c VA: 0x759538490c
	public Void Shutdown() { }
	// RVA: 0x2d6df5c VA: 0x7595385f5c
	public Void .ctor() { }
}
```