# StageZoneHomeEntryMedalView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelUncomplete`

- `Image _imgMedalProgress`

- `Text _textCount`

- `Color _colorCountHilight`

- `GameObject _panelComplete`

- `Image _imgMedal`

- `GameObject _panelDarkBkg`

- `ZoneHomeEntryMedalStatus m_cachedStatus`

- `Boolean m_disableDarkBkg`


## Properties

- `Boolean disableDarkBkg`


## Methods

- `Boolean get_disableDarkBkg()`

- `Void set_disableDarkBkg(Boolean)`

- `Void Render(ZoneHomeEntryMedalStatus)`

- `Void _UpdateViewByStatus()`

- `Void _UpdateUncompleteStatus()`

- `Void _UpdateCompleteStatus()`

- `Void _UpdateDarkBkgStatus()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeEntryMedalView : MonoBehaviour, IHotfixable
{
	private GameObject _panelUncomplete; // 0x18
	private Image _imgMedalProgress; // 0x20
	private Text _textCount; // 0x28
	private Color _colorCountHilight; // 0x30
	private GameObject _panelComplete; // 0x40
	private Image _imgMedal; // 0x48
	private GameObject _panelDarkBkg; // 0x50
	private ZoneHomeEntryMedalStatus m_cachedStatus; // 0x58
	private Boolean m_disableDarkBkg; // 0x80
	private static DelegateBridge __Hotfix0_get_disableDarkBkg; // 0x0
	private static DelegateBridge __Hotfix0_set_disableDarkBkg; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateViewByStatus; // 0x18
	private static DelegateBridge __Hotfix0__UpdateUncompleteStatus; // 0x20
	private static DelegateBridge __Hotfix0__UpdateCompleteStatus; // 0x28
	private static DelegateBridge __Hotfix0__UpdateDarkBkgStatus; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean disableDarkBkg { get; set; }

	// RVA: 0x2eff9d8 VA: 0x75955179d8
	public Boolean get_disableDarkBkg() { }
	// RVA: 0x2effa40 VA: 0x7595517a40
	public Void set_disableDarkBkg(Boolean value) { }
	// RVA: 0x2efcf4c VA: 0x7595514f4c
	public Void Render(ZoneHomeEntryMedalStatus newStatus) { }
	// RVA: 0x2effb3c VA: 0x7595517b3c
	private Void _UpdateViewByStatus() { }
	// RVA: 0x2effd20 VA: 0x7595517d20
	private Void _UpdateUncompleteStatus() { }
	// RVA: 0x2effc14 VA: 0x7595517c14
	private Void _UpdateCompleteStatus() { }
	// RVA: 0x2effac4 VA: 0x7595517ac4
	private Void _UpdateDarkBkgStatus() { }
	// RVA: 0x2efff40 VA: 0x7595517f40
	public Void .ctor() { }
}
```