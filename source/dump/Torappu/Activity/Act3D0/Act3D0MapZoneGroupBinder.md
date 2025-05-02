# Act3D0MapZoneGroupBinder

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Boolean m_isInited`

- `String m_selectZoneId`


## Methods

- `Void _InitIfNot()`

- `Void _OnZoneClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MapZoneGroupBinder : DataBinder`1, IHotfixable
{
	private List`1 _zoneViews; // 0x20
	private Boolean m_isInited; // 0x28
	private String m_selectZoneId; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnZoneClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3234ab0 VA: 0x759584cab0
	private Void _InitIfNot() { }
	// RVA: 0x3234c08 VA: 0x759584cc08
	public override Void OnValueChanged(Act3D0ZoneDescGroupViewProperty property) { }
	// RVA: 0x3234eec VA: 0x759584ceec
	private Void _OnZoneClicked(String zoneId) { }
	// RVA: 0x323503c VA: 0x759584d03c
	public Void .ctor() { }
}
```