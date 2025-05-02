# DynamicPageConfig

**Namespace:** ` `


## Fields

- `String m_name`

- `String m_resPath`

- `DynamicPageLoader m_loader`


## Methods

- `String GetName()`

- `UIPage LoadPage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DynamicPageConfig : IUIPageConfig
{
	private String m_name; // 0x10
	private String m_resPath; // 0x18
	private DynamicPageLoader m_loader; // 0x20


	// RVA: 0x2c47554 VA: 0x759525f554
	public Void .ctor(DynamicPageLoader loader, String name, String resPath) { }
	// RVA: 0x2c47b48 VA: 0x759525fb48
	public String GetName() { }
	// RVA: 0x2c47b50 VA: 0x759525fb50
	public UIPage LoadPage() { }
}
```