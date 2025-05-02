# ShaderInfoStorage

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `UIRAtlasAllocator m_Allocator`

- `Texture2D m_Texture`


## Methods

- `Void CreateOrExpandTexture()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class ShaderInfoStorage`1 : BaseShaderInfoStorage
{
	private readonly Int32 m_InitialSize; // 0x0
	private readonly Int32 m_MaxSize; // 0x0
	private readonly TextureFormat m_Format; // 0x0
	private readonly Func`2 m_Convert; // 0x0
	private UIRAtlasAllocator m_Allocator; // 0x0
	private Texture2D m_Texture; // 0x0
	private NativeArray`1 m_Texels; // 0x0

	public override Texture2D texture { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor(TextureFormat format, Func`2 convert, Int32 initialSize, Int32 maxSize) { }
	// RVA: 0x VA: 0x0
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x VA: 0x0
	public override Texture2D get_texture() { }
	// RVA: 0x VA: 0x0
	public override Boolean AllocateRect(Int32 width, Int32 height, out RectInt uvs) { }
	// RVA: 0x VA: 0x0
	public override Void SetTexel(Int32 x, Int32 y, Color color) { }
	// RVA: 0x VA: 0x0
	public override Void UpdateTexture() { }
	// RVA: 0x VA: 0x0
	private Void CreateOrExpandTexture() { }
	// RVA: 0x VA: 0x0
	private static Void CpuBlit(NativeArray`1 src, Int32 srcWidth, Int32 srcHeight, NativeArray`1 dst, Int32 dstWidth, Int32 dstHeight) { }
}
```