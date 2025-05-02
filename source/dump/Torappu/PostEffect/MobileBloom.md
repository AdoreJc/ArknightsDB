# MobileBloom

**Namespace:** `Torappu.PostEffect`


## Fields

- `Settings _settings`

- `Int32 m_thresholdShaderId`

- `Int32 m_parameterShaderId`

- `Int32 m_bloomTexShaderId`


## Properties

- `Settings settings`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.PostEffect
public class MobileBloom : PostEffectBase
{
	private const String SHADER_NAME; // 0x0
	private const String KEYWORD_FASTEST_BLUR_ON; // 0x0
	private Settings _settings; // 0x50
	private Int32 m_thresholdShaderId; // 0x58
	private Int32 m_parameterShaderId; // 0x5c
	private Int32 m_bloomTexShaderId; // 0x60
	private Nullable`1 m_cachedBlurQuality; // 0x64
	private static DelegateBridge __Hotfix0_get_settings; // 0x0
	private static DelegateBridge __Hotfix0_set_settings; // 0x8
	private static DelegateBridge __Hotfix0_get_shaderName; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnPostEffect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Settings settings { get; set; }
	protected override String shaderName { get; }

	// RVA: 0x354c4c8 VA: 0x7595b644c8
	public Settings get_settings() { }
	// RVA: 0x354c530 VA: 0x7595b64530
	public Void set_settings(Settings value) { }
	// RVA: 0x354c5b4 VA: 0x7595b645b4
	protected override String get_shaderName() { }
	// RVA: 0x354c630 VA: 0x7595b64630
	protected override Void OnInit() { }
	// RVA: 0x354c704 VA: 0x7595b64704
	protected override Void OnPostEffect(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x354cbd0 VA: 0x7595b64bd0
	public Void .ctor() { }
}
```