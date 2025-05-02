# DynamicPageLoader

**Namespace:** `Torappu.UI.Page`


## Methods

- `Void _LoadDynamicPagesFromActAssetMap()`

- `UIPage _LoadPageAsset(String, String)`

- `Void UnloadUnusedPages(IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Page
public class DynamicPageLoader : IUIPageRouter
{
	private List`1 m_pageConfigs; // 0x10
	private ListDict`2 m_loadedPages; // 0x18


	// RVA: 0x2c4732c VA: 0x759525f32c
	public Void .ctor(UIDynamicPageHub dynamicPageHub) { }
	// RVA: 0x2c475b4 VA: 0x759525f5b4
	private Void _LoadDynamicPagesFromActAssetMap() { }
	// RVA: 0x2c47878 VA: 0x759525f878
	private UIPage _LoadPageAsset(String name, String resPath) { }
	// RVA: 0x2c47970 VA: 0x759525f970
	public IList`1 GetPages() { }
	// RVA: 0x2c47978 VA: 0x759525f978
	public Void UnloadUnusedPages(IList`1 usedPages) { }
}
```