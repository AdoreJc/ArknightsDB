# AssistReportState

**Namespace:** `Torappu.Building.UI.Assist`


## Fields

- `BuildingCharSelectMaskPlugin _maskPlugin`

- `AssistReportDailyView _dailyView`

- `AssistAssistantContainer _assistantContainer`

- `Animator _spreadAnimator`

- `Int32 m_cachedClickedSlotIndex`

- `Boolean m_initFlag`


## Properties

- `Boolean usePluginWorkingPanel`

- `Boolean usePluginDormLockPanel`

- `Int32 CachedSlotIndex`


## Methods

- `Boolean get_usePluginWorkingPanel()`

- `Boolean get_usePluginDormLockPanel()`

- `Int32 get_CachedSlotIndex()`

- `RoomType GetCurrentRoomType()`

- `Boolean CheckIfCharValid(Int32)`

- `Void _InitIfNot()`

- `Void AnimatorSpread()`

- `Void AnimatorUnspread()`

- `Void _SendRequest()`

- `Void _OnPlayerDataChanged()`

- `Void _OnAssistSlotClicked(Int32)`

- `Void _OnJumpToCharSelect(CharSelectStateBean)`

- `Void <RegisterToDataListener>b__23_0(IStateBean)`

- `Void <_SendRequest>b__29_0(BuildingAssistReportResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Assist
public class AssistReportState : State, IBuildingCharSelectContext
{
	private const String SPREADPARAM; // 0x0
	private BuildingCharSelectMaskPlugin _maskPlugin; // 0x50
	private AssistReportDailyView _dailyView; // 0x58
	private AssistAssistantContainer _assistantContainer; // 0x60
	private Transform[] _dailyViewContainer; // 0x68
	private Animator _spreadAnimator; // 0x70
	private RectTransform[] rectTransformList; // 0x78
	private List`1 m_assistantViews; // 0x80
	private Int32 m_cachedClickedSlotIndex; // 0x88
	private List`1 m_tempListForExclusiveInstIds; // 0x90
	private Boolean m_initFlag; // 0x98
	private static DelegateBridge __Hotfix0_get_usePluginWorkingPanel; // 0x0
	private static DelegateBridge __Hotfix0_get_usePluginDormLockPanel; // 0x8
	private static DelegateBridge __Hotfix0_get_CachedSlotIndex; // 0x10
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x18
	private static DelegateBridge __Hotfix0_GetCurrentRoomType; // 0x20
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_GetAssistantUnlock; // 0x58
	private static DelegateBridge __Hotfix0_AnimatorSpread; // 0x60
	private static DelegateBridge __Hotfix0_AnimatorUnspread; // 0x68
	private static DelegateBridge __Hotfix0__SendRequest; // 0x70
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x78
	private static DelegateBridge __Hotfix0__OnAssistSlotClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnJumpToCharSelect; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Boolean usePluginWorkingPanel { get; }
	public Boolean usePluginDormLockPanel { get; }
	public Int32 CachedSlotIndex { get; }

	// RVA: 0x3e300fc VA: 0x75964480fc
	public Boolean get_usePluginWorkingPanel() { }
	// RVA: 0x3e30160 VA: 0x7596448160
	public Boolean get_usePluginDormLockPanel() { }
	// RVA: 0x3e301c4 VA: 0x75964481c4
	public Int32 get_CachedSlotIndex() { }
	// RVA: 0x3e3022c VA: 0x759644822c
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x3e30294 VA: 0x7596448294
	public RoomType GetCurrentRoomType() { }
	// RVA: 0x3e302fc VA: 0x75964482fc
	public Boolean CheckIfCharValid(Int32 instId) { }
	// RVA: 0x3e30588 VA: 0x7596448588
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3e305ec VA: 0x75964485ec
	protected override Void OnEnter() { }
	// RVA: 0x3e30950 VA: 0x7596448950
	protected override Void OnResume() { }
	// RVA: 0x3e30bdc VA: 0x7596448bdc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3e30d54 VA: 0x7596448d54
	private Void _InitIfNot() { }
	// RVA: 0x3e30f40 VA: 0x7596448f40
	public static Int32 GetAssistantUnlock(Int32 assistantId) { }
	// RVA: 0x3e3102c VA: 0x759644902c
	public Void AnimatorSpread() { }
	// RVA: 0x3e31290 VA: 0x7596449290
	public Void AnimatorUnspread() { }
	// RVA: 0x3e30784 VA: 0x7596448784
	private Void _SendRequest() { }
	// RVA: 0x3e313b0 VA: 0x75964493b0
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3e31420 VA: 0x7596449420
	private Void _OnAssistSlotClicked(Int32 index) { }
	// RVA: 0x3e3163c VA: 0x759644963c
	private Void _OnJumpToCharSelect(CharSelectStateBean stateBean) { }
	// RVA: 0x3e3189c VA: 0x759644989c
	public Void .ctor() { }
	// RVA: 0x3e31960 VA: 0x7596449960
	private Void <RegisterToDataListener>b__23_0(IStateBean stateBean) { }
	// RVA: 0x3e319e0 VA: 0x75964499e0
	private Void <_SendRequest>b__29_0(BuildingAssistReportResponse response) { }
	// RVA: 0x3e31dcc VA: 0x7596449dcc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e31dd4 VA: 0x7596449dd4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x3e31ddc VA: 0x7596449ddc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```