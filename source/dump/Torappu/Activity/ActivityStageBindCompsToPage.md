# ActivityStageBindCompsToPage

**Namespace:** `Torappu.Activity`


## Fields

- `RendererCollection m_rendererCollection`


## Methods

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityStageBindCompsToPage : ActivityStageComponent
{
	private Canvas[] _canvases; // 0x20
	private Renderer[] _renderers; // 0x28
	private RendererCollection m_rendererCollection; // 0x30
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30bc964 VA: 0x75956d4964
	protected override Void OnLoaded() { }
	// RVA: 0x30bcbd4 VA: 0x75956d4bd4
	protected override Void BeforeUnload() { }
	// RVA: 0x30bcd84 VA: 0x75956d4d84
	private Void OnDestroy() { }
	// RVA: 0x30bce0c VA: 0x75956d4e0c
	public Void .ctor() { }
	// RVA: 0x30bce78 VA: 0x75956d4e78
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x30bce7c VA: 0x75956d4e7c
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```