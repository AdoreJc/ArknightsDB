# BlurHandler

**Namespace:** ` `


## Properties

- `Boolean isValid`


## Methods

- `Boolean get_isValid()`

- `Void ShotBlurImage(UIRenderTextureImage)`

- `Void _GetBlurCameras(IList`1)`

- `Void BindCamera(CameraWrapper)`

- `Void UnBindCamera()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlurHandler : IPageVirtualCamBinder, IHotfixable
{
	private List`1 m_blurOnlyCameras; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_isValid; // 0x8
	private static DelegateBridge __Hotfix0_ShotBlurImage; // 0x10
	private static DelegateBridge __Hotfix0__GetBlurCameras; // 0x18
	private static DelegateBridge __Hotfix0_BindCamera; // 0x20
	private static DelegateBridge __Hotfix0_UnBindCamera; // 0x28

	public Boolean isValid { get; }

	// RVA: 0x3371dc8 VA: 0x7595989dc8
	public Void .ctor() { }
	// RVA: 0x3371b40 VA: 0x7595989b40
	public Boolean get_isValid() { }
	// RVA: 0x3371bcc VA: 0x7595989bcc
	public Void ShotBlurImage(UIRenderTextureImage blurTarget) { }
	// RVA: 0x3371e8c VA: 0x7595989e8c
	private Void _GetBlurCameras(IList`1 cameras) { }
	// RVA: 0x3372058 VA: 0x759598a058
	public Void BindCamera(CameraWrapper camera) { }
	// RVA: 0x33720e4 VA: 0x759598a0e4
	public Void UnBindCamera() { }
}
```