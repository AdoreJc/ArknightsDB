# WeeklyGroupZoneItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _goDisablePart`

- `GameObject _goWillOpenPart`

- `GameObject _goLockPart`

- `GameObject _goForceOpenPart`

- `GameObject _goNormalPart`

- `Text _textOpenTime`

- `Image _imgBg`

- `Text _textName`

- `Text _textUnlockInfo`

- `Text _unlockStageParam`

- `WeeklyGroupZoneIconWidget _iconWidget`

- `Boolean m_isUnlock`

- `WeeklyZoneViewModel m_zoneModel`

- `GameObject m_timelyObj`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Int32, ZoneViewModel)`

- `String _ParseOpenText(WeekStruct`1)`

- `Void OnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class WeeklyGroupZoneItem : MonoBehaviour, IHotfixable
{
	private GameObject _goDisablePart; // 0x18
	private GameObject _goWillOpenPart; // 0x20
	private GameObject _goLockPart; // 0x28
	private GameObject _goForceOpenPart; // 0x30
	private GameObject _goNormalPart; // 0x38
	private Text _textOpenTime; // 0x40
	private Image _imgBg; // 0x48
	private Text _textName; // 0x50
	private Text _textUnlockInfo; // 0x58
	private Text _unlockStageParam; // 0x60
	private WeeklyGroupZoneIconWidget _iconWidget; // 0x68
	private const Single NORMAL_PART_ALPHA; // 0x0
	private Boolean m_isUnlock; // 0x70
	private Action`1 <onItemClick>k__BackingField; // 0x78
	private WeeklyZoneViewModel m_zoneModel; // 0x80
	private GameObject m_timelyObj; // 0x88
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__ParseOpenText; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2ef6a7c VA: 0x759550ea7c
	private Action`1 get_onItemClick() { }
	// RVA: 0x2ef6ae4 VA: 0x759550eae4
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2ef6b68 VA: 0x759550eb68
	public Void Render(Int32 position, ZoneViewModel zoneModel) { }
	// RVA: 0x2ef7228 VA: 0x759550f228
	private String _ParseOpenText(WeekStruct`1 weekInfo) { }
	// RVA: 0x2ef74f4 VA: 0x759550f4f4
	public Void OnItemClick() { }
	// RVA: 0x2ef75ac VA: 0x759550f5ac
	public Void .ctor() { }
}
```