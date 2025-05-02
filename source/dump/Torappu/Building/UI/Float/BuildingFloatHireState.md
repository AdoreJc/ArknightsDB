# BuildingFloatHireState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Image _avatarIcon`

- `Text _downCountTime`

- `Text _statePercent`

- `Image _stateBar`

- `GameObject _emptyPart`

- `GameObject _avatarPart`

- `GameObject _noAvatarPart`

- `GameObject _hiringPart`

- `GameObject _hiredPart`

- `GameObject _pausePart`

- `Text _hiredText`

- `GameObject _iconTimeArrow`

- `BuildingHireRefreshCountView _refreshCount`

- `HiringSnapshot m_hireSnapshot`

- `CountDownTask m_hiringCountDown`


## Methods

- `Void EventOnHireSelect()`

- `Void Update()`

- `Void _RenderCountDownValue()`

- `Void _RefreshView()`

- `Boolean _IsTotalEmpty(PlayerBuildingHire)`

- `Void <_RefreshView>b__21_0(TickValue)`

- `Void <_RefreshView>b__21_1(TickValue)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatHireState : BuildingFloatVaultInfoState
{
	private Image _avatarIcon; // 0xa0
	private Text _downCountTime; // 0xa8
	private Text _statePercent; // 0xb0
	private Image _stateBar; // 0xb8
	private GameObject _emptyPart; // 0xc0
	private GameObject _avatarPart; // 0xc8
	private GameObject _noAvatarPart; // 0xd0
	private GameObject _hiringPart; // 0xd8
	private GameObject _hiredPart; // 0xe0
	private GameObject _pausePart; // 0xe8
	private Text _hiredText; // 0xf0
	private GameObject _iconTimeArrow; // 0xf8
	private BuildingHireRefreshCountView _refreshCount; // 0x100
	private HiringSnapshot m_hireSnapshot; // 0x108
	private CountDownTask m_hiringCountDown; // 0x138
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_EventOnHireSelect; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__RenderCountDownValue; // 0x18
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x20
	private static DelegateBridge __Hotfix0__RefreshView; // 0x28
	private static DelegateBridge __Hotfix0__IsTotalEmpty; // 0x30
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected override FloatState state { get; }

	// RVA: 0x3e1c61c VA: 0x759643461c
	protected override FloatState get_state() { }
	// RVA: 0x3e1c684 VA: 0x7596434684
	public Void EventOnHireSelect() { }
	// RVA: 0x3e1c7b4 VA: 0x75964347b4
	private Void Update() { }
	// RVA: 0x3e1c830 VA: 0x7596434830
	private Void _RenderCountDownValue() { }
	// RVA: 0x3e1cae4 VA: 0x7596434ae4
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1cb94 VA: 0x7596434b94
	private Void _RefreshView() { }
	// RVA: 0x3e1d5c0 VA: 0x75964355c0
	private Boolean _IsTotalEmpty(PlayerBuildingHire playerHire) { }
	// RVA: 0x3e1d6c4 VA: 0x75964356c4
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e1d750 VA: 0x7596435750
	public Void .ctor() { }
	// RVA: 0x3e1d824 VA: 0x7596435824
	private Void <_RefreshView>b__21_0(TickValue _) { }
	// RVA: 0x3e1d828 VA: 0x7596435828
	private Void <_RefreshView>b__21_1(TickValue _) { }
	// RVA: 0x3e1d82c VA: 0x759643582c
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e1d838 VA: 0x7596435838
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
}
```