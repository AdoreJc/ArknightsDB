# Act17D0EffectView

**Namespace:** `Torappu.Activity.Act17D0`


## Fields

- `ScreenEffectHolder _effectHolder`

- `RendererCollection m_rendererCollection`


## Methods

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void _DisableEffect(Object)`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17D0
public class Act17D0EffectView : ActivityStageComponent
{
	private ScreenEffectHolder _effectHolder; // 0x20
	private RendererCollection m_rendererCollection; // 0x28
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__DisableEffect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x341f404 VA: 0x7595a37404
	protected override Void OnLoaded() { }
	// RVA: 0x341f744 VA: 0x7595a37744
	protected override Void BeforeUnload() { }
	// RVA: 0x341f9f0 VA: 0x7595a379f0
	private Void OnEnable() { }
	// RVA: 0x341fab0 VA: 0x7595a37ab0
	private Void OnDestroy() { }
	// RVA: 0x341fb38 VA: 0x7595a37b38
	private Void _DisableEffect(Object _) { }
	// RVA: 0x341fc10 VA: 0x7595a37c10
	public Void .ctor() { }
	// RVA: 0x341fc80 VA: 0x7595a37c80
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x341fc88 VA: 0x7595a37c88
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```