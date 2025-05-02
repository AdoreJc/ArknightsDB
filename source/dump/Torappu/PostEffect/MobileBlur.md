# MobileBlur

**Namespace:** `Torappu.PostEffect`


## Fields

- `Settings _settings`

- `Int32 m_parameterShaderId`


## Properties

- `Settings settings`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.PostEffect
public class MobileBlur : PostEffectBase
{
	public const String SHADER_NAME; // 0x0
	private Settings _settings; // 0x50
	private Int32 m_parameterShaderId; // 0x58
	private static DelegateBridge __Hotfix0_get_settings; // 0x0
	private static DelegateBridge __Hotfix0_set_settings; // 0x8
	private static DelegateBridge __Hotfix0_get_shaderName; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnPostEffect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Settings settings { get; set; }
	protected override String shaderName { get; }

	// RVA: 0x354ccf0 VA: 0x7595b64cf0
	public Settings get_settings() { }
	// RVA: 0x354cd58 VA: 0x7595b64d58
	public Void set_settings(Settings value) { }
	// RVA: 0x354cddc VA: 0x7595b64ddc
	protected override String get_shaderName() { }
	// RVA: 0x354ce58 VA: 0x7595b64e58
	protected override Void OnInit() { }
	// RVA: 0x354cee0 VA: 0x7595b64ee0
	protected override Void OnPostEffect(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x354d218 VA: 0x7595b65218
	public Void .ctor() { }
}
```