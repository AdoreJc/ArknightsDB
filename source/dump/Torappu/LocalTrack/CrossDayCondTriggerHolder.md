# CrossDayCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Fields

- `Boolean m_typeInited`


## Methods

- `Void OnEnterGame()`

- `Void OnCrossDay()`

- `Void _UpdateTracks()`

- `Void _InitCrossDayTypesIfNot()`

- `Void _LoadTypeDataFromActivity()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class CrossDayCondTriggerHolder : TrackTriggerHolder`1, IVersionTrackTriggerHolder
{
	public const String CROSS_DAY_TRACK_TYPE_FORMAT; // 0x0
	private ListDict`2 m_triggerTypes; // 0x20
	private Dictionary`2 m_typeTrackDataMap; // 0x28
	private Boolean m_typeInited; // 0x30
	private static DelegateBridge __Hotfix0_OnTriggerAdded; // 0x0
	private static DelegateBridge __Hotfix0_OnEnterGame; // 0x8
	private static DelegateBridge __Hotfix0_OnCrossDay; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTracks; // 0x18
	private static DelegateBridge __Hotfix0__InitCrossDayTypesIfNot; // 0x20
	private static DelegateBridge __Hotfix0__LoadTypeDataFromActivity; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3f17000 VA: 0x759652f000
	protected override Void OnTriggerAdded(CrossDayCondTrigger trigger) { }
	// RVA: 0x3f17240 VA: 0x759652f240
	public Void OnEnterGame() { }
	// RVA: 0x3f175bc VA: 0x759652f5bc
	public Void OnCrossDay() { }
	// RVA: 0x3f172a8 VA: 0x759652f2a8
	private Void _UpdateTracks() { }
	// RVA: 0x3f1715c VA: 0x759652f15c
	private Void _InitCrossDayTypesIfNot() { }
	// RVA: 0x3f17624 VA: 0x759652f624
	private Void _LoadTypeDataFromActivity() { }
	// RVA: 0x3f1793c VA: 0x759652f93c
	public Void .ctor() { }
}
```