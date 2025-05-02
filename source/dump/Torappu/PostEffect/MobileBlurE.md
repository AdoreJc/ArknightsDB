# MobileBlurE

**Namespace:** `Torappu.PostEffect`


## Fields

- `Settings _settings`

- `Int32 m_parameterShaderId`

- `Int32 m_maskShaderId`


## Properties

- `Settings settings`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`

- `Int32 _GetPassOffset(BlurType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.PostEffect
public class MobileBlurE : PostEffectBaseE
{
	public const String SHADER_NAME; // 0x0
	private Settings _settings; // 0x50
	private Int32 m_parameterShaderId; // 0x58
	private Int32 m_maskShaderId; // 0x5c
	private static DelegateBridge __Hotfix0_get_settings; // 0x0
	private static DelegateBridge __Hotfix0_set_settings; // 0x8
	private static DelegateBridge __Hotfix0_get_shaderName; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnPostEffect; // 0x20
	private static DelegateBridge __Hotfix0__GetPassOffset; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Settings settings { get; set; }
	protected override String shaderName { get; }

	// RVA: 0x354d2a0 VA: 0x7595b652a0
	public Settings get_settings() { }
	// RVA: 0x354d308 VA: 0x7595b65308
	public Void set_settings(Settings value) { }
	// RVA: 0x354d38c VA: 0x7595b6538c
	protected override String get_shaderName() { }
	// RVA: 0x354d408 VA: 0x7595b65408
	protected override Void OnInit() { }
	// RVA: 0x354d4b4 VA: 0x7595b654b4
	protected override Void OnPostEffect(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x354d850 VA: 0x7595b65850
	private Int32 _GetPassOffset(BlurType blurType) { }
	// RVA: 0x354d8cc VA: 0x7595b658cc
	public Void .ctor() { }
}
```