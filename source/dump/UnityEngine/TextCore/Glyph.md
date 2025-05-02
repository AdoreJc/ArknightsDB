# Glyph

**Namespace:** `UnityEngine.TextCore`


## Fields

- `UInt32 m_Index`

- `GlyphMetrics m_Metrics`

- `GlyphRect m_GlyphRect`

- `Single m_Scale`

- `Int32 m_AtlasIndex`

- `GlyphClassDefinitionType m_ClassDefinitionType`


## Properties

- `UInt32 index`

- `GlyphMetrics metrics`

- `GlyphRect glyphRect`

- `Int32 atlasIndex`


## Methods

- `UInt32 get_index()`

- `GlyphMetrics get_metrics()`

- `GlyphRect get_glyphRect()`

- `Int32 get_atlasIndex()`

- `Void set_atlasIndex(Int32)`


## Dump
```C#
// Dll : UnityEngine.TextCoreFontEngineModule.dll
// Namespace : UnityEngine.TextCore
public class Glyph
{
	private UInt32 m_Index; // 0x10
	private GlyphMetrics m_Metrics; // 0x14
	private GlyphRect m_GlyphRect; // 0x28
	private Single m_Scale; // 0x38
	private Int32 m_AtlasIndex; // 0x3c
	private GlyphClassDefinitionType m_ClassDefinitionType; // 0x40

	public UInt32 index { get; }
	public GlyphMetrics metrics { get; }
	public GlyphRect glyphRect { get; }
	public Int32 atlasIndex { get; set; }

	// RVA: 0x68e2eb4 VA: 0x7598efaeb4
	public UInt32 get_index() { }
	// RVA: 0x68e2ebc VA: 0x7598efaebc
	public GlyphMetrics get_metrics() { }
	// RVA: 0x68e2ed0 VA: 0x7598efaed0
	public GlyphRect get_glyphRect() { }
	// RVA: 0x68e2edc VA: 0x7598efaedc
	public Int32 get_atlasIndex() { }
	// RVA: 0x68e2ee4 VA: 0x7598efaee4
	public Void set_atlasIndex(Int32 value) { }
	// RVA: 0x68e2eec VA: 0x7598efaeec
	public Void .ctor() { }
	// RVA: 0x68e2f14 VA: 0x7598efaf14
	internal Void .ctor(GlyphMarshallingStruct glyphStruct) { }
	// RVA: 0x68e2fa0 VA: 0x7598efafa0
	public Void .ctor(UInt32 index, GlyphMetrics metrics, GlyphRect glyphRect, Single scale, Int32 atlasIndex) { }
}
```