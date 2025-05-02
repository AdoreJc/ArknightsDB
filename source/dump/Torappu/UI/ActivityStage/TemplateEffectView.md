# TemplateEffectView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `ScreenEffectHolder _effectHolder`

- `RendererCollection m_rendererCollection`

- `Int32 m_disable`


## Methods

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void SetEffectEnable(DisableSource, Boolean)`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateEffectView : ActivityStageComponent
{
	private ScreenEffectHolder _effectHolder; // 0x20
	private RendererCollection m_rendererCollection; // 0x28
	private Int32 m_disable; // 0x30
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_SetEffectEnable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x30aa490 VA: 0x75956c2490
	protected override Void OnLoaded() { }
	// RVA: 0x30aa7c8 VA: 0x75956c27c8
	protected override Void BeforeUnload() { }
	// RVA: 0x30aaa18 VA: 0x75956c2a18
	private Void OnEnable() { }
	// RVA: 0x30aaa88 VA: 0x75956c2a88
	private Void OnDestroy() { }
	// RVA: 0x309f9a0 VA: 0x75956b79a0
	public Void SetEffectEnable(DisableSource source, Boolean enable) { }
	// RVA: 0x30aab10 VA: 0x75956c2b10
	public Void .ctor() { }
	// RVA: 0x30aab80 VA: 0x75956c2b80
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x30aab88 VA: 0x75956c2b88
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```