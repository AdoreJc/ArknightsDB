# PagePlugin

**Namespace:** ` `


## Fields

- `Int32 m_instId`

- `String m_name`

- `PagePluginCtrl m_host`

- `Boolean m_hasPerspectiveCam`


## Methods

- `Void _PauseStateFromPage(UIPageTransType, Boolean)`

- `Void _SetActivePerspectiveCamFromPage(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PagePlugin : Plugin
{
	private Int32 m_instId; // 0x18
	private String m_name; // 0x20
	private PagePluginCtrl m_host; // 0x28
	private Boolean m_hasPerspectiveCam; // 0x30


	// RVA: 0x1bdd9e4 VA: 0x75941f59e4
	public Void .ctor(PagePluginCtrl host, UIPage page) { }
	// RVA: 0x1bdda34 VA: 0x75941f5a34
	public override Boolean OverrideStart(Action onStart) { }
	// RVA: 0x1bddb68 VA: 0x75941f5b68
	public override Boolean OverrideStop(Action onStop) { }
	// RVA: 0x1bddaac VA: 0x75941f5aac
	private Void _PauseStateFromPage(UIPageTransType transType, Boolean needPause) { }
	// RVA: 0x1bddb40 VA: 0x75941f5b40
	private Void _SetActivePerspectiveCamFromPage(Boolean active) { }
	// RVA: 0x1bdddc8 VA: 0x75941f5dc8
	public override Boolean OverrideCreate(Action`1 onCreate, DataBundle savedInst) { }
	// RVA: 0x1bde0c8 VA: 0x75941f60c8
	public override Void OnDestroy() { }
}
```