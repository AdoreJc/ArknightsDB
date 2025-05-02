# VoucherSkinPage

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `UIRenderTextureImage _imageBlurBkg`

- `VoucherSkinHomeViewProperty m_homeProp`


## Properties

- `VoucherSkinHomeViewProperty homeProp`


## Methods

- `VoucherSkinHomeViewProperty get_homeProp()`

- `UIRenderTextureImage GetBlurBkg()`

- `Void _FetchServerData(Action)`

- `IEnumerator _RouteToHomeCoroutine()`

- `Void <InitStateEngine>b__6_0()`

- `IEnumerator <>n__0()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinPage : StateEnginePage, IFadeInPushWithBlurBkg, IHotfixable
{
	private UIRenderTextureImage _imageBlurBkg; // 0xe8
	public VoucherSkinHomeViewProperty m_homeProp; // 0xf0
	private static DelegateBridge __Hotfix0_get_homeProp; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurBkg; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0__FetchServerData; // 0x18
	private static DelegateBridge __Hotfix0__RouteToHomeCoroutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public VoucherSkinHomeViewProperty homeProp { get; }

	// RVA: 0x229197c VA: 0x75948a997c
	public VoucherSkinHomeViewProperty get_homeProp() { }
	// RVA: 0x2293b68 VA: 0x75948abb68
	public UIRenderTextureImage GetBlurBkg() { }
	// RVA: 0x2293bd0 VA: 0x75948abbd0
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2293ca4 VA: 0x75948abca4
	private Void _FetchServerData(Action onFinished) { }
	// RVA: 0x2293ed8 VA: 0x75948abed8
	private IEnumerator _RouteToHomeCoroutine() { }
	// RVA: 0x2293fac VA: 0x75948abfac
	public Void .ctor() { }
	// RVA: 0x2294058 VA: 0x75948ac058
	private Void <InitStateEngine>b__6_0() { }
	// RVA: 0x2294078 VA: 0x75948ac078
	private IEnumerator <>n__0() { }
	// RVA: 0x2294080 VA: 0x75948ac080
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```