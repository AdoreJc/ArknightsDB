# MobileFishEye

**Namespace:** `Torappu.PostEffect`


## Fields

- `Settings _settings`

- `Boolean _useDepth`

- `Boolean _useStencil`

- `Int32 m_transPowerShaderId`

- `Int32 m_distortionAmountShaderId`

- `Int32 m_inOutSwitchShaderId`

- `Int32 m_rbChannelOffsetShaderId`


## Properties

- `Settings settings`


## Methods

- `Settings get_settings()`

- `Void set_settings(Settings)`

- `Void _InitDepthBuffer()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.PostEffect
public class MobileFishEye : PostEffectBaseE
{
	public const String SHADER_NAME; // 0x0
	private Settings _settings; // 0x50
	private Boolean _useDepth; // 0x58
	private Boolean _useStencil; // 0x59
	private Int32 m_transPowerShaderId; // 0x5c
	private Int32 m_distortionAmountShaderId; // 0x60
	private Int32 m_inOutSwitchShaderId; // 0x64
	private Int32 m_rbChannelOffsetShaderId; // 0x68
	private static DelegateBridge __Hotfix0_get_settings; // 0x0
	private static DelegateBridge __Hotfix0_set_settings; // 0x8
	private static DelegateBridge __Hotfix0_get_shaderName; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_OnPostEffect; // 0x20
	private static DelegateBridge __Hotfix0__InitDepthBuffer; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Settings settings { get; set; }
	protected override String shaderName { get; }

	// RVA: 0x354d958 VA: 0x7595b65958
	public Settings get_settings() { }
	// RVA: 0x354d9c0 VA: 0x7595b659c0
	public Void set_settings(Settings value) { }
	// RVA: 0x354da44 VA: 0x7595b65a44
	protected override String get_shaderName() { }
	// RVA: 0x354dac0 VA: 0x7595b65ac0
	protected override Void OnInit() { }
	// RVA: 0x354dc48 VA: 0x7595b65c48
	protected override Void OnPostEffect(RenderTexture source, RenderTexture destination) { }
	// RVA: 0x354dbc4 VA: 0x7595b65bc4
	private Void _InitDepthBuffer() { }
	// RVA: 0x354de04 VA: 0x7595b65e04
	public Void .ctor() { }
}
```