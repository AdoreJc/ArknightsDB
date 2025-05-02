# DIYContext

**Namespace:** ` `


## Fields

- `UIPage m_page`

- `UIMedalDIYManager m_mgr`


## Methods

- `Void BeginDragFromToken(String)`

- `Void DragCardFromList(String, PointerEventData)`

- `Void EndDragFromToken(String)`

- `Void PointDownFromToken(String, PointerEventData)`

- `T LoadAsset(String)`

- `Sprite LoadMedalIcon(String)`

- `String GetTargetMedalId()`

- `UIPage GetPage()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DIYContext : IMedalDIYContext
{
	private UIPage m_page; // 0x10
	private UIMedalDIYManager m_mgr; // 0x18


	// RVA: 0x2769998 VA: 0x7594d81998
	public Void .ctor(UIPage page, UIMedalDIYManager mgr) { }
	// RVA: 0x276c42c VA: 0x7594d8442c
	public Void BeginDragFromToken(String medalId) { }
	// RVA: 0x276c444 VA: 0x7594d84444
	public Void DragCardFromList(String medalId, PointerEventData eventData) { }
	// RVA: 0x276c45c VA: 0x7594d8445c
	public Void EndDragFromToken(String medalId) { }
	// RVA: 0x276c474 VA: 0x7594d84474
	public Void PointDownFromToken(String medalId, PointerEventData eventData) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x276c48c VA: 0x7594d8448c
	public Sprite LoadMedalIcon(String spriteId) { }
	// RVA: 0x276c548 VA: 0x7594d84548
	public String GetTargetMedalId() { }
	// RVA: 0x276c564 VA: 0x7594d84564
	public UIPage GetPage() { }
}
```