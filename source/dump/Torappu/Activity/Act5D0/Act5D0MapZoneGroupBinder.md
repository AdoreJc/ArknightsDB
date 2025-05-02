# Act5D0MapZoneGroupBinder

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `Boolean m_isInited`

- `String m_selectZoneId`


## Methods

- `Void _InitIfNot()`

- `Void _OnZoneClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MapZoneGroupBinder : DataBinder`1
{
	private List`1 _zoneViews; // 0x20
	private Boolean m_isInited; // 0x28
	private String m_selectZoneId; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnZoneClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31bf590 VA: 0x75957d7590
	private Void _InitIfNot() { }
	// RVA: 0x31bf6e8 VA: 0x75957d76e8
	public override Void OnValueChanged(Act5D0ZoneDescGroupViewProperty property) { }
	// RVA: 0x31bfa34 VA: 0x75957d7a34
	private Void _OnZoneClicked(String zoneId) { }
	// RVA: 0x31bfb84 VA: 0x75957d7b84
	public Void .ctor() { }
}
```