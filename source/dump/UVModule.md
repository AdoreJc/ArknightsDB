# UVModule

**Namespace:** ` `


## Fields

- `TextureSheetAnimationModule m_module`

- `MinMaxCurve m_frameOverTime`

- `MinMaxCurve m_startFrame`

- `Texture mainTexture`

- `Boolean <enabled>k__BackingField`

- `ParticleSystemAnimationMode <mode>k__BackingField`


## Properties

- `Boolean enabled`

- `ParticleSystemAnimationMode mode`


## Methods

- `Boolean get_enabled()`

- `Void set_enabled(Boolean)`

- `ParticleSystemAnimationMode get_mode()`

- `Void set_mode(ParticleSystemAnimationMode)`

- `Void PrepareForRender(ContextData)`

- `Void Update(ContextData)`

- `Void _UpdateSpritesTpl(ContextData)`

- `Void _UpdateSingleRowTpl(ContextData)`

- `Void _UpdateWholeSheetTpl(ContextData)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class UVModule
{
	private LocalGenericPool`1 m_rectDataPool; // 0x10
	private TextureSheetAnimationModule m_module; // 0x18
	private MinMaxCurve m_frameOverTime; // 0x20
	private MinMaxCurve m_startFrame; // 0x40
	public List`1 spriteRectData; // 0x60
	public List`1 normalizedSheetIndex; // 0x68
	public Texture mainTexture; // 0x70
	private Boolean <enabled>k__BackingField; // 0x78
	private ParticleSystemAnimationMode <mode>k__BackingField; // 0x7c

	public Boolean enabled { get; set; }
	public ParticleSystemAnimationMode mode { get; set; }

	// RVA: 0x67a5ed4 VA: 0x7598dbded4
	public Boolean get_enabled() { }
	// RVA: 0x67a5edc VA: 0x7598dbdedc
	private Void set_enabled(Boolean value) { }
	// RVA: 0x67a5ee8 VA: 0x7598dbdee8
	public ParticleSystemAnimationMode get_mode() { }
	// RVA: 0x67a5ef0 VA: 0x7598dbdef0
	private Void set_mode(ParticleSystemAnimationMode value) { }
	// RVA: 0x67a5ef8 VA: 0x7598dbdef8
	public Void PrepareForRender(ContextData context) { }
	// RVA: 0x67a65f4 VA: 0x7598dbe5f4
	public Void Update(ContextData context) { }
	// RVA: 0x67a66a4 VA: 0x7598dbe6a4
	private Void _UpdateSpritesTpl(ContextData context) { }
	// RVA: 0x67a6a38 VA: 0x7598dbea38
	private Void _UpdateSingleRowTpl(ContextData context) { }
	// RVA: 0x67a7078 VA: 0x7598dbf078
	private Void _UpdateWholeSheetTpl(ContextData context) { }
	// RVA: 0x67a7400 VA: 0x7598dbf400
	public Void .ctor() { }
}
```