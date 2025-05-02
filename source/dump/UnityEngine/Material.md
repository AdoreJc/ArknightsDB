# Material

**Namespace:** `UnityEngine`


## Properties

- `Shader shader`

- `Color color`

- `Texture mainTexture`

- `Vector2 mainTextureOffset`

- `Vector2 mainTextureScale`

- `Int32 renderQueue`

- `Boolean enableInstancing`

- `Int32 passCount`


## Methods

- `Shader get_shader()`

- `Void set_shader(Shader)`

- `Color get_color()`

- `Void set_color(Color)`

- `Texture get_mainTexture()`

- `Void set_mainTexture(Texture)`

- `Vector2 get_mainTextureOffset()`

- `Void set_mainTextureOffset(Vector2)`

- `Vector2 get_mainTextureScale()`

- `Void set_mainTextureScale(Vector2)`

- `Int32 GetFirstPropertyNameIdByAttribute(ShaderPropertyFlags)`

- `Boolean HasProperty(Int32)`

- `Boolean HasProperty(String)`

- `Int32 get_renderQueue()`

- `Void set_renderQueue(Int32)`

- `Void EnableKeyword(String)`

- `Void DisableKeyword(String)`

- `Boolean IsKeywordEnabled(String)`

- `Void set_enableInstancing(Boolean)`

- `Int32 get_passCount()`

- `String GetTagImpl(String, Boolean, String)`

- `String GetTag(String, Boolean)`

- `Boolean SetPass(Int32)`

- `Void CopyPropertiesFromMaterial(Material)`

- `Void SetShaderKeywords(String[])`

- `Void set_shaderKeywords(String[])`

- `Void SetFloatImpl(Int32, Single)`

- `Void SetColorImpl(Int32, Color)`

- `Void SetMatrixImpl(Int32, Matrix4x4)`

- `Void SetTextureImpl(Int32, Texture)`

- `Void SetBufferImpl(Int32, ComputeBuffer)`

- `Single GetFloatImpl(Int32)`

- `Color GetColorImpl(Int32)`

- `Texture GetTextureImpl(Int32)`

- `Vector4 GetTextureScaleAndOffsetImpl(Int32)`

- `Void SetTextureOffsetImpl(Int32, Vector2)`

- `Void SetTextureScaleImpl(Int32, Vector2)`

- `Void SetInt(String, Int32)`

- `Void SetInt(Int32, Int32)`

- `Void SetFloat(String, Single)`

- `Void SetFloat(Int32, Single)`

- `Void SetColor(String, Color)`

- `Void SetColor(Int32, Color)`

- `Void SetVector(String, Vector4)`

- `Void SetVector(Int32, Vector4)`

- `Void SetMatrix(String, Matrix4x4)`

- `Void SetMatrix(Int32, Matrix4x4)`

- `Void SetTexture(String, Texture)`

- `Void SetTexture(Int32, Texture)`

- `Void SetBuffer(String, ComputeBuffer)`

- `Single GetFloat(String)`

- `Single GetFloat(Int32)`

- `Color GetColor(String)`

- `Color GetColor(Int32)`

- `Vector4 GetVector(String)`

- `Vector4 GetVector(Int32)`

- `Texture GetTexture(String)`

- `Texture GetTexture(Int32)`

- `Void SetTextureOffset(String, Vector2)`

- `Void SetTextureOffset(Int32, Vector2)`

- `Void SetTextureScale(String, Vector2)`

- `Void SetTextureScale(Int32, Vector2)`

- `Vector2 GetTextureOffset(String)`

- `Vector2 GetTextureOffset(Int32)`

- `Vector2 GetTextureScale(String)`

- `Vector2 GetTextureScale(Int32)`

- `Void SetColorImpl_Injected(Int32, ref)`

- `Void SetMatrixImpl_Injected(Int32, ref)`

- `Void GetColorImpl_Injected(Int32, out)`

- `Void GetTextureScaleAndOffsetImpl_Injected(Int32, out)`

- `Void SetTextureOffsetImpl_Injected(Int32, ref)`

- `Void SetTextureScaleImpl_Injected(Int32, ref)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class Material : Object
{

	public Shader shader { get; set; }
	public Color color { get; set; }
	public Texture mainTexture { get; set; }
	public Vector2 mainTextureOffset { get; set; }
	public Vector2 mainTextureScale { get; set; }
	public Int32 renderQueue { get; set; }
	public Boolean enableInstancing { set; }
	public Int32 passCount { get; }
	public String[] shaderKeywords { get; set; }

	// RVA: 0x6865174 VA: 0x7598e7d174
	private static Void CreateWithShader(Material self, Shader shader) { }
	// RVA: 0x68651b8 VA: 0x7598e7d1b8
	private static Void CreateWithMaterial(Material self, Material source) { }
	// RVA: 0x68651fc VA: 0x7598e7d1fc
	private static Void CreateWithString(Material self) { }
	// RVA: 0x6865238 VA: 0x7598e7d238
	public Void .ctor(Shader shader) { }
	// RVA: 0x68652c8 VA: 0x7598e7d2c8
	public Void .ctor(Material source) { }
	// RVA: 0x6865358 VA: 0x7598e7d358
	public Void .ctor(String contents) { }
	// RVA: 0x68653d8 VA: 0x7598e7d3d8
	public Shader get_shader() { }
	// RVA: 0x6865414 VA: 0x7598e7d414
	public Void set_shader(Shader value) { }
	// RVA: 0x6865458 VA: 0x7598e7d458
	public Color get_color() { }
	// RVA: 0x6865578 VA: 0x7598e7d578
	public Void set_color(Color value) { }
	// RVA: 0x68656cc VA: 0x7598e7d6cc
	public Texture get_mainTexture() { }
	// RVA: 0x6865830 VA: 0x7598e7d830
	public Void set_mainTexture(Texture value) { }
	// RVA: 0x68659cc VA: 0x7598e7d9cc
	public Vector2 get_mainTextureOffset() { }
	// RVA: 0x6865ad0 VA: 0x7598e7dad0
	public Void set_mainTextureOffset(Vector2 value) { }
	// RVA: 0x6865be8 VA: 0x7598e7dbe8
	public Vector2 get_mainTextureScale() { }
	// RVA: 0x6865cc4 VA: 0x7598e7dcc4
	public Void set_mainTextureScale(Vector2 value) { }
	// RVA: 0x68654e4 VA: 0x7598e7d4e4
	private Int32 GetFirstPropertyNameIdByAttribute(ShaderPropertyFlags attributeFlag) { }
	// RVA: 0x6865ddc VA: 0x7598e7dddc
	public Boolean HasProperty(Int32 nameID) { }
	// RVA: 0x6865e20 VA: 0x7598e7de20
	public Boolean HasProperty(String name) { }
	// RVA: 0x6865e90 VA: 0x7598e7de90
	public Int32 get_renderQueue() { }
	// RVA: 0x6865ecc VA: 0x7598e7decc
	public Void set_renderQueue(Int32 value) { }
	// RVA: 0x6865f10 VA: 0x7598e7df10
	public Void EnableKeyword(String keyword) { }
	// RVA: 0x6865f54 VA: 0x7598e7df54
	public Void DisableKeyword(String keyword) { }
	// RVA: 0x6865f98 VA: 0x7598e7df98
	public Boolean IsKeywordEnabled(String keyword) { }
	// RVA: 0x6865fdc VA: 0x7598e7dfdc
	public Void set_enableInstancing(Boolean value) { }
	// RVA: 0x6866020 VA: 0x7598e7e020
	public Int32 get_passCount() { }
	// RVA: 0x686605c VA: 0x7598e7e05c
	private String GetTagImpl(String tag, Boolean currentSubShaderOnly, String defaultValue) { }
	// RVA: 0x68660b8 VA: 0x7598e7e0b8
	public String GetTag(String tag, Boolean searchFallbacks) { }
	// RVA: 0x6866140 VA: 0x7598e7e140
	public Boolean SetPass(Int32 pass) { }
	// RVA: 0x6866184 VA: 0x7598e7e184
	public Void CopyPropertiesFromMaterial(Material mat) { }
	// RVA: 0x68661c8 VA: 0x7598e7e1c8
	private String[] GetShaderKeywords() { }
	// RVA: 0x6866204 VA: 0x7598e7e204
	private Void SetShaderKeywords(String[] names) { }
	// RVA: 0x6866248 VA: 0x7598e7e248
	public String[] get_shaderKeywords() { }
	// RVA: 0x6866284 VA: 0x7598e7e284
	public Void set_shaderKeywords(String[] value) { }
	// RVA: 0x68662c8 VA: 0x7598e7e2c8
	private Void SetFloatImpl(Int32 name, Single value) { }
	// RVA: 0x686631c VA: 0x7598e7e31c
	private Void SetColorImpl(Int32 name, Color value) { }
	// RVA: 0x68663cc VA: 0x7598e7e3cc
	private Void SetMatrixImpl(Int32 name, Matrix4x4 value) { }
	// RVA: 0x6866474 VA: 0x7598e7e474
	private Void SetTextureImpl(Int32 name, Texture value) { }
	// RVA: 0x68664c8 VA: 0x7598e7e4c8
	private Void SetBufferImpl(Int32 name, ComputeBuffer value) { }
	// RVA: 0x686651c VA: 0x7598e7e51c
	private Single GetFloatImpl(Int32 name) { }
	// RVA: 0x6866560 VA: 0x7598e7e560
	private Color GetColorImpl(Int32 name) { }
	// RVA: 0x6866614 VA: 0x7598e7e614
	private Texture GetTextureImpl(Int32 name) { }
	// RVA: 0x6866658 VA: 0x7598e7e658
	private Vector4 GetTextureScaleAndOffsetImpl(Int32 name) { }
	// RVA: 0x686670c VA: 0x7598e7e70c
	private Void SetTextureOffsetImpl(Int32 name, Vector2 offset) { }
	// RVA: 0x68667b8 VA: 0x7598e7e7b8
	private Void SetTextureScaleImpl(Int32 name, Vector2 scale) { }
	// RVA: 0x6866864 VA: 0x7598e7e864
	public Void SetInt(String name, Int32 value) { }
	// RVA: 0x68668f0 VA: 0x7598e7e8f0
	public Void SetInt(Int32 nameID, Int32 value) { }
	// RVA: 0x6866944 VA: 0x7598e7e944
	public Void SetFloat(String name, Single value) { }
	// RVA: 0x68669c4 VA: 0x7598e7e9c4
	public Void SetFloat(Int32 nameID, Single value) { }
	// RVA: 0x6865650 VA: 0x7598e7d650
	public Void SetColor(String name, Color value) { }
	// RVA: 0x686564c VA: 0x7598e7d64c
	public Void SetColor(Int32 nameID, Color value) { }
	// RVA: 0x6866a18 VA: 0x7598e7ea18
	public Void SetVector(String name, Vector4 value) { }
	// RVA: 0x6866a94 VA: 0x7598e7ea94
	public Void SetVector(Int32 nameID, Vector4 value) { }
	// RVA: 0x6866a98 VA: 0x7598e7ea98
	public Void SetMatrix(String name, Matrix4x4 value) { }
	// RVA: 0x6866b34 VA: 0x7598e7eb34
	public Void SetMatrix(Int32 nameID, Matrix4x4 value) { }
	// RVA: 0x686594c VA: 0x7598e7d94c
	public Void SetTexture(String name, Texture value) { }
	// RVA: 0x68658f8 VA: 0x7598e7d8f8
	public Void SetTexture(Int32 nameID, Texture value) { }
	// RVA: 0x6866b98 VA: 0x7598e7eb98
	public Void SetBuffer(String name, ComputeBuffer value) { }
	// RVA: 0x6866c18 VA: 0x7598e7ec18
	public Single GetFloat(String name) { }
	// RVA: 0x6866c88 VA: 0x7598e7ec88
	public Single GetFloat(Int32 nameID) { }
	// RVA: 0x686552c VA: 0x7598e7d52c
	public Color GetColor(String name) { }
	// RVA: 0x6865528 VA: 0x7598e7d528
	public Color GetColor(Int32 nameID) { }
	// RVA: 0x6866ccc VA: 0x7598e7eccc
	public Vector4 GetVector(String name) { }
	// RVA: 0x6866d18 VA: 0x7598e7ed18
	public Vector4 GetVector(Int32 nameID) { }
	// RVA: 0x68657c0 VA: 0x7598e7d7c0
	public Texture GetTexture(String name) { }
	// RVA: 0x686577c VA: 0x7598e7d77c
	public Texture GetTexture(Int32 nameID) { }
	// RVA: 0x6865b84 VA: 0x7598e7db84
	public Void SetTextureOffset(String name, Vector2 value) { }
	// RVA: 0x6865b80 VA: 0x7598e7db80
	public Void SetTextureOffset(Int32 nameID, Vector2 value) { }
	// RVA: 0x6865d78 VA: 0x7598e7dd78
	public Void SetTextureScale(String name, Vector2 value) { }
	// RVA: 0x6865d74 VA: 0x7598e7dd74
	public Void SetTextureScale(Int32 nameID, Vector2 value) { }
	// RVA: 0x6865a78 VA: 0x7598e7da78
	public Vector2 GetTextureOffset(String name) { }
	// RVA: 0x6865a60 VA: 0x7598e7da60
	public Vector2 GetTextureOffset(Int32 nameID) { }
	// RVA: 0x6865c78 VA: 0x7598e7dc78
	public Vector2 GetTextureScale(String name) { }
	// RVA: 0x6865c74 VA: 0x7598e7dc74
	public Vector2 GetTextureScale(Int32 nameID) { }
	// RVA: 0x6866378 VA: 0x7598e7e378
	private Void SetColorImpl_Injected(Int32 name, ref Color value) { }
	// RVA: 0x6866420 VA: 0x7598e7e420
	private Void SetMatrixImpl_Injected(Int32 name, ref Matrix4x4 value) { }
	// RVA: 0x68665c0 VA: 0x7598e7e5c0
	private Void GetColorImpl_Injected(Int32 name, out Color ret) { }
	// RVA: 0x68666b8 VA: 0x7598e7e6b8
	private Void GetTextureScaleAndOffsetImpl_Injected(Int32 name, out Vector4 ret) { }
	// RVA: 0x6866764 VA: 0x7598e7e764
	private Void SetTextureOffsetImpl_Injected(Int32 name, ref Vector2 offset) { }
	// RVA: 0x6866810 VA: 0x7598e7e810
	private Void SetTextureScaleImpl_Injected(Int32 name, ref Vector2 scale) { }
}
```