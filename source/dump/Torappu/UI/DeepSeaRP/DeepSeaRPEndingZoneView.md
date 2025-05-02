# DeepSeaRPEndingZoneView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Boolean _needShowLockMask`

- `Text _txtZoneNameNormal`

- `Text _txtZoneNameSelect`

- `Button _btnClickArea`

- `GameObject _objNormPart`

- `GameObject _objSelectPart`

- `GameObject _objInfoPart`

- `Text _txtInfo`

- `String m_zoneId`


## Properties

- `String zoneId`


## Methods

- `Void set_onZoneClicked(Action`1)`

- `String get_zoneId()`

- `Void Render(DeepSeaRPZoneMapModel, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPEndingZoneView : MonoBehaviour, IHotfixable
{
	private Boolean _needShowLockMask; // 0x18
	private Text _txtZoneNameNormal; // 0x20
	private Text _txtZoneNameSelect; // 0x28
	private Button _btnClickArea; // 0x30
	private GameObject _objNormPart; // 0x38
	private GameObject _objSelectPart; // 0x40
	private GameObject _objInfoPart; // 0x48
	private Text _txtInfo; // 0x50
	private Action`1 <onZoneClicked>k__BackingField; // 0x58
	private String m_zoneId; // 0x60
	private static DelegateBridge __Hotfix0_get_onZoneClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onZoneClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneId; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onZoneClicked { get; set; }
	public String zoneId { get; }

	// RVA: 0x29d9580 VA: 0x7594ff1580
	private Action`1 get_onZoneClicked() { }
	// RVA: 0x29d93d4 VA: 0x7594ff13d4
	public Void set_onZoneClicked(Action`1 value) { }
	// RVA: 0x29d95e8 VA: 0x7594ff15e8
	public String get_zoneId() { }
	// RVA: 0x29d91ac VA: 0x7594ff11ac
	public Void Render(DeepSeaRPZoneMapModel model, Boolean isSelected) { }
	// RVA: 0x29d9650 VA: 0x7594ff1650
	public Void EventOnClicked() { }
	// RVA: 0x29d9704 VA: 0x7594ff1704
	public Void .ctor() { }
}
```