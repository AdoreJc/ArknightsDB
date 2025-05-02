# BlurCamBinder

**Namespace:** ` `


## Methods

- `Void BindCamera(CameraWrapper)`

- `Void UnBindCamera()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlurCamBinder : IPageVirtualCamBinder, IHotfixable
{
	private List`1 m_blurCameras; // 0x10
	private static DelegateBridge __Hotfix0_get_blurCameras; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_BindCamera; // 0x10
	private static DelegateBridge __Hotfix0_UnBindCamera; // 0x18

	public List`1 blurCameras { get; }

	// RVA: 0x2989044 VA: 0x7594fa1044
	public List`1 get_blurCameras() { }
	// RVA: 0x29883e0 VA: 0x7594fa03e0
	public Void .ctor() { }
	// RVA: 0x2989470 VA: 0x7594fa1470
	public Void BindCamera(CameraWrapper camera) { }
	// RVA: 0x29894fc VA: 0x7594fa14fc
	public Void UnBindCamera() { }
}
```