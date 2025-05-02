# Texture

**Namespace:** `UnityEngine`


## Properties

- `TextureWrapMode wrapMode`

- `TextureWrapMode wrapModeU`

- `TextureWrapMode wrapModeV`

- `TextureWrapMode wrapModeW`

- `FilterMode filterMode`

- `Int32 anisoLevel`

- `Single mipMapBias`

- `Vector2 texelSize`


## Methods

- `Int32 GetDataWidth()`

- `Int32 GetDataHeight()`

- `TextureDimension GetDimension()`

- `TextureWrapMode get_wrapMode()`

- `Void set_wrapMode(TextureWrapMode)`

- `TextureWrapMode get_wrapModeU()`

- `Void set_wrapModeU(TextureWrapMode)`

- `TextureWrapMode get_wrapModeV()`

- `Void set_wrapModeV(TextureWrapMode)`

- `TextureWrapMode get_wrapModeW()`

- `Void set_wrapModeW(TextureWrapMode)`

- `FilterMode get_filterMode()`

- `Void set_filterMode(FilterMode)`

- `Int32 get_anisoLevel()`

- `Void set_anisoLevel(Int32)`

- `Void set_mipMapBias(Single)`

- `Vector2 get_texelSize()`

- `IntPtr GetNativeTexturePtr()`

- `Int32 Internal_GetActiveTextureColorSpace()`

- `Void get_texelSize_Injected(out)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Texture : Object
{
	public static readonly Int32 GenerateAllMips; // 0x0

	public virtual GraphicsFormat graphicsFormat { get; }
	public virtual Int32 width { get; set; }
	public virtual Int32 height { get; set; }
	public virtual TextureDimension dimension { get; set; }
	public virtual Boolean isReadable { get; }
	public TextureWrapMode wrapMode { get; set; }
	public TextureWrapMode wrapModeU { get; set; }
	public TextureWrapMode wrapModeV { get; set; }
	public TextureWrapMode wrapModeW { get; set; }
	public FilterMode filterMode { get; set; }
	public Int32 anisoLevel { get; set; }
	public Single mipMapBias { set; }
	public Vector2 texelSize { get; }
	internal ColorSpace activeTextureColorSpace { get; }

	// RVA: 0x686be08 VA: 0x7598e83e08
	protected Void .ctor() { }
	// RVA: 0x686be60 VA: 0x7598e83e60
	public virtual GraphicsFormat get_graphicsFormat() { }
	// RVA: 0x686beb8 VA: 0x7598e83eb8
	private Int32 GetDataWidth() { }
	// RVA: 0x686bef4 VA: 0x7598e83ef4
	private Int32 GetDataHeight() { }
	// RVA: 0x686bf30 VA: 0x7598e83f30
	private TextureDimension GetDimension() { }
	// RVA: 0x686bf6c VA: 0x7598e83f6c
	public virtual Int32 get_width() { }
	// RVA: 0x686bfa8 VA: 0x7598e83fa8
	public virtual Void set_width(Int32 value) { }
	// RVA: 0x686bfe8 VA: 0x7598e83fe8
	public virtual Int32 get_height() { }
	// RVA: 0x686c024 VA: 0x7598e84024
	public virtual Void set_height(Int32 value) { }
	// RVA: 0x686c064 VA: 0x7598e84064
	public virtual TextureDimension get_dimension() { }
	// RVA: 0x686c0a0 VA: 0x7598e840a0
	public virtual Void set_dimension(TextureDimension value) { }
	// RVA: 0x686c0e0 VA: 0x7598e840e0
	public virtual Boolean get_isReadable() { }
	// RVA: 0x686c11c VA: 0x7598e8411c
	public TextureWrapMode get_wrapMode() { }
	// RVA: 0x686c158 VA: 0x7598e84158
	public Void set_wrapMode(TextureWrapMode value) { }
	// RVA: 0x686c19c VA: 0x7598e8419c
	public TextureWrapMode get_wrapModeU() { }
	// RVA: 0x686c1d8 VA: 0x7598e841d8
	public Void set_wrapModeU(TextureWrapMode value) { }
	// RVA: 0x686c21c VA: 0x7598e8421c
	public TextureWrapMode get_wrapModeV() { }
	// RVA: 0x686c258 VA: 0x7598e84258
	public Void set_wrapModeV(TextureWrapMode value) { }
	// RVA: 0x686c29c VA: 0x7598e8429c
	public TextureWrapMode get_wrapModeW() { }
	// RVA: 0x686c2d8 VA: 0x7598e842d8
	public Void set_wrapModeW(TextureWrapMode value) { }
	// RVA: 0x686c31c VA: 0x7598e8431c
	public FilterMode get_filterMode() { }
	// RVA: 0x686c358 VA: 0x7598e84358
	public Void set_filterMode(FilterMode value) { }
	// RVA: 0x686c39c VA: 0x7598e8439c
	public Int32 get_anisoLevel() { }
	// RVA: 0x686c3d8 VA: 0x7598e843d8
	public Void set_anisoLevel(Int32 value) { }
	// RVA: 0x686c41c VA: 0x7598e8441c
	public Void set_mipMapBias(Single value) { }
	// RVA: 0x686c468 VA: 0x7598e84468
	public Vector2 get_texelSize() { }
	// RVA: 0x686c4f8 VA: 0x7598e844f8
	public IntPtr GetNativeTexturePtr() { }
	// RVA: 0x686c534 VA: 0x7598e84534
	private Int32 Internal_GetActiveTextureColorSpace() { }
	// RVA: 0x686c570 VA: 0x7598e84570
	internal ColorSpace get_activeTextureColorSpace() { }
	// RVA: 0x686c5b8 VA: 0x7598e845b8
	internal TextureColorSpace GetTextureColorSpace(Boolean linear) { }
	// RVA: 0x686c5c4 VA: 0x7598e845c4
	internal TextureColorSpace GetTextureColorSpace(GraphicsFormat format) { }
	// RVA: 0x686c624 VA: 0x7598e84624
	internal Boolean ValidateFormat(TextureFormat format) { }
	// RVA: 0x686c7dc VA: 0x7598e847dc
	internal Boolean ValidateFormat(GraphicsFormat format, FormatUsage usage) { }
	// RVA: 0x686c98c VA: 0x7598e8498c
	internal UnityException CreateNonReadableException(Texture t) { }
	// RVA: 0x686ca30 VA: 0x7598e84a30
	internal UnityException CreateNativeArrayLengthOverflowException() { }
	// RVA: 0x686caa4 VA: 0x7598e84aa4
	private static Void .cctor() { }
	// RVA: 0x686c4b4 VA: 0x7598e844b4
	private Void get_texelSize_Injected(out Vector2 ret) { }
}
```