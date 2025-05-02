# PagePluginCtrl

**Namespace:** ` `


## Fields

- `EnableStateWithKey m_pauseByPage`

- `UIPageCameraProvider m_cameraProvider`


## Properties

- `UIPageCameraProvider camProvider`


## Methods

- `UIPageCameraProvider get_camProvider()`

- `Void set_camProvider(UIPageCameraProvider)`

- `Void UpdatePauseStateFromPage(String, Boolean)`

- `Void UpdatePerspectiveCamFromPage(Int32, Boolean)`

- `Void AddVirtualCamPage(IVirtualCameraPage)`

- `Void RemoveVirtualCamPage(IVirtualCameraPage)`

- `Void DisposePageVirtualCameras()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PagePluginCtrl : PluginController
{
	private HashSet`1 m_perspectiveCamUsedPageInstIds; // 0x10
	private EnableStateWithKey m_pauseByPage; // 0x18
	private UIPageCameraProvider m_cameraProvider; // 0x20
	private List`1 m_virtualCameraPages; // 0x28

	public UIPageCameraProvider camProvider { get; set; }

	// RVA: 0x1bde240 VA: 0x75941f6240
	public UIPageCameraProvider get_camProvider() { }
	// RVA: 0x1bde248 VA: 0x75941f6248
	public Void set_camProvider(UIPageCameraProvider value) { }
	// RVA: 0x1bddbe0 VA: 0x75941f5be0
	public Void UpdatePauseStateFromPage(String pageName, Boolean needPause) { }
	// RVA: 0x1bddc94 VA: 0x75941f5c94
	public Void UpdatePerspectiveCamFromPage(Int32 instId, Boolean active) { }
	// RVA: 0x1bddfc0 VA: 0x75941f5fc0
	public Void AddVirtualCamPage(IVirtualCameraPage page) { }
	// RVA: 0x1bde180 VA: 0x75941f6180
	public Void RemoveVirtualCamPage(IVirtualCameraPage page) { }
	// RVA: 0x1bdd854 VA: 0x75941f5854
	public Void DisposePageVirtualCameras() { }
	// RVA: 0x1bde250 VA: 0x75941f6250
	protected override Void AddPlugin(UIPage page, Action`2 pluginSetter) { }
	// RVA: 0x1bdd454 VA: 0x75941f5454
	public Void .ctor() { }
}
```