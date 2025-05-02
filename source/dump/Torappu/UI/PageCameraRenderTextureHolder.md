# PageCameraRenderTextureHolder

**Namespace:** `Torappu.UI`


## Fields

- `GenRTFormat _genRTFormat`

- `FilterMode _filterMode`

- `Camera m_rtCamera`

- `RenderTexture m_activeRT`


## Properties

- `RenderTexture activeRenderTexture`


## Methods

- `RenderTexture get_activeRenderTexture()`

- `Boolean IsCollectable()`

- `Void _RequestRenderTexture()`

- `Void _ReleaseRenderTexture()`

- `RenderTextureFormat _GetSupportedTextureFormat()`

- `Void <>xLuaBaseProxy_OnAwake()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class PageCameraRenderTextureHolder : PageComponent, IPageCameraMarker, IPageComponentMarker, IHotfixable
{
	private GenRTFormat _genRTFormat; // 0x20
	private FilterMode _filterMode; // 0x30
	private Camera m_rtCamera; // 0x38
	private RenderTexture m_activeRT; // 0x40
	private static DelegateBridge __Hotfix0_get_activeRenderTexture; // 0x0
	private static DelegateBridge __Hotfix0_IsCollectable; // 0x8
	private static DelegateBridge __Hotfix0_OnAwake; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__RequestRenderTexture; // 0x28
	private static DelegateBridge __Hotfix0__ReleaseRenderTexture; // 0x30
	private static DelegateBridge __Hotfix0__GetSupportedTextureFormat; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public RenderTexture activeRenderTexture { get; }

	// RVA: 0x21970c4 VA: 0x75947af0c4
	public RenderTexture get_activeRenderTexture() { }
	// RVA: 0x219712c VA: 0x75947af12c
	public Boolean IsCollectable() { }
	// RVA: 0x2197190 VA: 0x75947af190
	protected override Void OnAwake() { }
	// RVA: 0x219722c VA: 0x75947af22c
	protected override Void OnCreate() { }
	// RVA: 0x21973a8 VA: 0x75947af3a8
	protected override Void OnDestroy() { }
	// RVA: 0x21972a0 VA: 0x75947af2a0
	private Void _RequestRenderTexture() { }
	// RVA: 0x219741c VA: 0x75947af41c
	private Void _ReleaseRenderTexture() { }
	// RVA: 0x2197514 VA: 0x75947af514
	private RenderTextureFormat _GetSupportedTextureFormat() { }
	// RVA: 0x2197590 VA: 0x75947af590
	public Void .ctor() { }
	// RVA: 0x2197608 VA: 0x75947af608
	private Void <>xLuaBaseProxy_OnAwake() { }
	// RVA: 0x2197610 VA: 0x75947af610
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2197618 VA: 0x75947af618
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```