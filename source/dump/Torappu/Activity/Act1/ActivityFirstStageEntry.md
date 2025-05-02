# ActivityFirstStageEntry

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `GameObject _maskDetail`

- `Text _coinText`

- `Text _timeBar`

- `Text _timeRemain`

- `GameObject _mapAbleState`

- `GameObject _mapDisableState`

- `DateTime m_cacheEndTime`

- `ActivityBasicInfo m_cacheBasicInfo`


## Methods

- `Void InitData()`

- `Void EventOnButtonClicked()`

- `Void EventOnMissionShopClicked()`

- `Void EventOnDetailClicked()`

- `Void EventOnToZoneMapClicked()`

- `Void FixedUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstStageEntry : ActivityStageSingleComponent
{
	private GameObject _maskDetail; // 0x20
	private Text _coinText; // 0x28
	private Text _timeBar; // 0x30
	private Text _timeRemain; // 0x38
	private GameObject _mapAbleState; // 0x40
	private GameObject _mapDisableState; // 0x48
	private DateTime m_cacheEndTime; // 0x50
	private ActivityBasicInfo m_cacheBasicInfo; // 0x58
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_EventOnButtonClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnMissionShopClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnDetailClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnToZoneMapClicked; // 0x20
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x28
	private static DelegateBridge __Hotfix0__FormatEndTime; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3489d38 VA: 0x7595aa1d38
	public Void InitData() { }
	// RVA: 0x348a8f4 VA: 0x7595aa28f4
	public Void EventOnButtonClicked() { }
	// RVA: 0x348a9a0 VA: 0x7595aa29a0
	public Void EventOnMissionShopClicked() { }
	// RVA: 0x348aa4c VA: 0x7595aa2a4c
	public Void EventOnDetailClicked() { }
	// RVA: 0x348aaf8 VA: 0x7595aa2af8
	public Void EventOnToZoneMapClicked() { }
	// RVA: 0x348abcc VA: 0x7595aa2bcc
	private Void FixedUpdate() { }
	// RVA: 0x348acd4 VA: 0x7595aa2cd4
	private static String _FormatEndTime(DateTime endTime) { }
	// RVA: 0x348af7c VA: 0x7595aa2f7c
	public Void .ctor() { }
}
```