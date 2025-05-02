# StageSideStoryMapDecroView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean m_isInited`

- `String m_selectZoneId`


## Methods

- `Void _InitIfNot()`

- `Void _OnZoneClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageSideStoryMapDecroView : StageSideStoryMapDecroViewBase, IHotfixable
{
	private List`1 _zoneViews; // 0x20
	private List`1 _plugins; // 0x28
	private Boolean m_isInited; // 0x30
	private String m_selectZoneId; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x8
	private static DelegateBridge __Hotfix0__OnZoneClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f197d8 VA: 0x75955317d8
	private Void _InitIfNot() { }
	// RVA: 0x2f19930 VA: 0x7595531930
	public override Void OnRefresh(List`1 viewModelList, ZoneViewModel selectViewModel) { }
	// RVA: 0x2f19dd8 VA: 0x7595531dd8
	private Void _OnZoneClicked(String zoneId) { }
	// RVA: 0x2f19f44 VA: 0x7595531f44
	public Void .ctor() { }
}
```