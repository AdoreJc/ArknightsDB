# Act9D0EntryZoneGroupView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `GameObject _panelAllTimeout`

- `Boolean _disableAllTimeout`

- `Act9D0StageController m_actController`


## Methods

- `Void InitAndBindView(Act9D0StageController)`

- `Void _OnZoneViewClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0EntryZoneGroupView : DataBinder`1
{
	private GameObject _panelAllTimeout; // 0x20
	private Boolean _disableAllTimeout; // 0x28
	private List`1 _zoneViewList; // 0x30
	private Act9D0StageController m_actController; // 0x38
	private static DelegateBridge __Hotfix0_InitAndBindView; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnZoneViewClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x319cccc VA: 0x75957b4ccc
	public Void InitAndBindView(Act9D0StageController controller) { }
	// RVA: 0x31a3ecc VA: 0x75957bbecc
	public override Void OnValueChanged(Act9D0ZoneDescGroupViewProperty property) { }
	// RVA: 0x31a478c VA: 0x75957bc78c
	private Void _OnZoneViewClicked(String zoneId) { }
	// RVA: 0x31a4860 VA: 0x75957bc860
	public Void .ctor() { }
}
```