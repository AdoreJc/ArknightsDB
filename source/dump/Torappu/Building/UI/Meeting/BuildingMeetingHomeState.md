# BuildingMeetingHomeState

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `Image _blueBackground`

- `MeetingCharacterView _characterView0`

- `MeetingCharacterView _characterView1`

- `PrefabInstHolder _topMenuHolder`

- `MeetingClueStorageView _storageView`

- `MeetingClueReceiveView _receiveView`

- `MeetingClueRemoveHintView _clueRemoveHint`

- `MeetingClueProductView _clueProductView`

- `BuildingRoomLevelView _roomLevelView`

- `Text _roomTitle`

- `Image _productProgress`

- `GameObject _newProductLabel`

- `GameObject _newRecvLabel`

- `GameObject _newSendLabel`

- `RectTransform _characterPanel`

- `RectTransform _slotsPanel`

- `RectTransform _rightTopPanel`

- `RectTransform _rightBottomPanel`

- `RectTransform _rightSidePanel`

- `AnimationCurve _panelMoveCurve`

- `RectTransform _receiveAllButtonRect`

- `Single _leftOffsetDistance`

- `Single _rightOffsetDistance`

- `Single _rightSideOffsetDistance`

- `Single _panelMoveDuration`

- `Button _unlockTransferButton`

- `Text _unlockEquipedCount`

- `Text _unlockNeededCount`

- `GameObject _transferringPanel`

- `Single _updateInterval`

- `Image _productProgressImage`

- `MeetingClueConnectLineController _connectLineController`

- `BuildingTwoContentNotify _notify`

- `IMeetingSession m_currentSession`

- `Boolean m_offsetMoved`

- `Boolean m_tweeing`

- `Single m_timer`

- `Vector2 m_characterPanelBasePosition`

- `Vector2 m_slotsPanelBasePosition`

- `Vector2 m_rightTopPanelBasePosition`

- `Vector2 m_rightBottomPanelBasePosition`

- `Vector2 m_rightSidePanelBasePosition`

- `Vector2 m_characterPanelTargetPosition`

- `Vector2 m_slotPanelTargetPosition`

- `Vector2 m_rightTopPanelTargetPosition`

- `Vector2 m_rightBottomPanelTargetPosition`

- `Vector2 m_rightSidePanelTargetPosition`


## Methods

- `Void Awake()`

- `Void _InitTopMenu()`

- `Void _UpdatePlayerStatus()`

- `Void _TryReceiveTransferRewards()`

- `IEnumerator _OpenTransferResultPage()`

- `Void _SetupStationaryCharacter()`

- `Void _SetupSlots(Boolean)`

- `Void _SetupUnlockTransferButton()`

- `Void _UpdateProductProgress()`

- `Void _OnClueSlotPressed(Int32)`

- `Void _OnStorageCluePressed(IMeetingClue, MeetingClueItemView)`

- `Void _OnStorageRemoveCluePressed(IMeetingClue, MeetingClueItemView)`

- `Void _OnStorageUnequipCluePressed(IMeetingClue, MeetingClueItemView)`

- `Void _SetupNewLabels()`

- `Void _SetupTitle()`

- `Void SetupView()`

- `Void _SetOffsetMovePosition(Single)`

- `Void _SetOffsetMoved(Boolean)`

- `Void OnProductButtonPressed()`

- `Void OnRecvButtonPressed()`

- `Void OnSendButtonPressed()`

- `Void Update()`

- `Void OnDestroy()`

- `Void OnDetailButtonPressed()`

- `Void OnBackgroundPressed()`

- `Void OnUnlockButtonPressed()`

- `Void OnStationCharacterButton0Pressed()`

- `Void OnStationCharacterButton1Pressed()`

- `Void <_InitTopMenu>b__50_0(GameObject)`

- `Void <_InitTopMenu>b__50_1()`

- `Void <_TryReceiveTransferRewards>b__54_0(Int32)`

- `Void <_OnStorageCluePressed>b__61_0(Int32)`

- `Void <_OnStorageUnequipCluePressed>b__63_0(Int32)`

- `Void <OnProductButtonPressed>b__69_0()`

- `Void <OnRecvButtonPressed>b__70_0(Int32)`

- `Void <OnSendButtonPressed>b__71_0(Int32)`

- `Void <OnUnlockButtonPressed>b__76_0(Int32)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMeetingHomeState : State
{
	private Image _blueBackground; // 0x50
	private MeetingCharacterView _characterView0; // 0x58
	private MeetingCharacterView _characterView1; // 0x60
	private PrefabInstHolder _topMenuHolder; // 0x68
	private MeetingClueSlotView[] _slotViews; // 0x70
	private MeetingClueStorageView _storageView; // 0x78
	private MeetingClueReceiveView _receiveView; // 0x80
	private MeetingClueRemoveHintView _clueRemoveHint; // 0x88
	private MeetingClueProductView _clueProductView; // 0x90
	private BuildingRoomLevelView _roomLevelView; // 0x98
	private Text _roomTitle; // 0xa0
	private Image _productProgress; // 0xa8
	private GameObject _newProductLabel; // 0xb0
	private GameObject _newRecvLabel; // 0xb8
	private GameObject _newSendLabel; // 0xc0
	private RectTransform _characterPanel; // 0xc8
	private RectTransform _slotsPanel; // 0xd0
	private RectTransform _rightTopPanel; // 0xd8
	private RectTransform _rightBottomPanel; // 0xe0
	private RectTransform _rightSidePanel; // 0xe8
	private AnimationCurve _panelMoveCurve; // 0xf0
	private RectTransform _receiveAllButtonRect; // 0xf8
	private Single _leftOffsetDistance; // 0x100
	private Single _rightOffsetDistance; // 0x104
	private Single _rightSideOffsetDistance; // 0x108
	private Single _panelMoveDuration; // 0x10c
	private Button _unlockTransferButton; // 0x110
	private Text _unlockEquipedCount; // 0x118
	private Text _unlockNeededCount; // 0x120
	private GameObject _transferringPanel; // 0x128
	private Single _updateInterval; // 0x130
	private Image _productProgressImage; // 0x138
	private MeetingClueConnectLineController _connectLineController; // 0x140
	private BuildingTwoContentNotify _notify; // 0x148
	private IMeetingSession m_currentSession; // 0x150
	private Boolean m_offsetMoved; // 0x158
	private Boolean m_tweeing; // 0x159
	private Single m_timer; // 0x15c
	private Vector2 m_characterPanelBasePosition; // 0x160
	private Vector2 m_slotsPanelBasePosition; // 0x168
	private Vector2 m_rightTopPanelBasePosition; // 0x170
	private Vector2 m_rightBottomPanelBasePosition; // 0x178
	private Vector2 m_rightSidePanelBasePosition; // 0x180
	private Vector2 m_characterPanelTargetPosition; // 0x188
	private Vector2 m_slotPanelTargetPosition; // 0x190
	private Vector2 m_rightTopPanelTargetPosition; // 0x198
	private Vector2 m_rightBottomPanelTargetPosition; // 0x1a0
	private Vector2 m_rightSidePanelTargetPosition; // 0x1a8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0__UpdatePlayerStatus; // 0x28
	private static DelegateBridge __Hotfix0__TryReceiveTransferRewards; // 0x30
	private static DelegateBridge __Hotfix0__OpenTransferResultPage; // 0x38
	private static DelegateBridge __Hotfix0__SetupStationaryCharacter; // 0x40
	private static DelegateBridge __Hotfix0__SetupSlots; // 0x48
	private static DelegateBridge __Hotfix0__SetupUnlockTransferButton; // 0x50
	private static DelegateBridge __Hotfix0__UpdateProductProgress; // 0x58
	private static DelegateBridge __Hotfix0__OnClueSlotPressed; // 0x60
	private static DelegateBridge __Hotfix0__OnStorageCluePressed; // 0x68
	private static DelegateBridge __Hotfix0__OnStorageRemoveCluePressed; // 0x70
	private static DelegateBridge __Hotfix0__OnStorageUnequipCluePressed; // 0x78
	private static DelegateBridge __Hotfix0__SetupNewLabels; // 0x80
	private static DelegateBridge __Hotfix0__SetupTitle; // 0x88
	private static DelegateBridge __Hotfix0_SetupView; // 0x90
	private static DelegateBridge __Hotfix0__SetOffsetMovePosition; // 0x98
	private static DelegateBridge __Hotfix0__SetOffsetMoved; // 0xa0
	private static DelegateBridge __Hotfix0_OnProductButtonPressed; // 0xa8
	private static DelegateBridge __Hotfix0_OnRecvButtonPressed; // 0xb0
	private static DelegateBridge __Hotfix0_OnSendButtonPressed; // 0xb8
	private static DelegateBridge __Hotfix0_Update; // 0xc0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xc8
	private static DelegateBridge __Hotfix0_OnDetailButtonPressed; // 0xd0
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0xd8
	private static DelegateBridge __Hotfix0_OnUnlockButtonPressed; // 0xe0
	private static DelegateBridge __Hotfix0_OnStationCharacterButton0Pressed; // 0xe8
	private static DelegateBridge __Hotfix0_OnStationCharacterButton1Pressed; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8


	// RVA: 0x3def320 VA: 0x7596407320
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3def384 VA: 0x7596407384
	private Void Awake() { }
	// RVA: 0x3def4f4 VA: 0x75964074f4
	private Void _InitTopMenu() { }
	// RVA: 0x3def5b8 VA: 0x75964075b8
	protected override Void OnEnter() { }
	// RVA: 0x3def864 VA: 0x7596407864
	protected override Void OnResume() { }
	// RVA: 0x3def7f4 VA: 0x75964077f4
	private Void _UpdatePlayerStatus() { }
	// RVA: 0x3def9b0 VA: 0x75964079b0
	private Void _TryReceiveTransferRewards() { }
	// RVA: 0x3defb5c VA: 0x7596407b5c
	private IEnumerator _OpenTransferResultPage() { }
	// RVA: 0x3defc30 VA: 0x7596407c30
	private Void _SetupStationaryCharacter() { }
	// RVA: 0x3df030c VA: 0x759640830c
	private Void _SetupSlots(Boolean keepSelection) { }
	// RVA: 0x3df0a5c VA: 0x7596408a5c
	private Void _SetupUnlockTransferButton() { }
	// RVA: 0x3df0d38 VA: 0x7596408d38
	private Void _UpdateProductProgress() { }
	// RVA: 0x3df124c VA: 0x759640924c
	private Void _OnClueSlotPressed(Int32 index) { }
	// RVA: 0x3df1700 VA: 0x7596409700
	private Void _OnStorageCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df1848 VA: 0x7596409848
	private Void _OnStorageRemoveCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df1a04 VA: 0x7596409a04
	private Void _OnStorageUnequipCluePressed(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3df1b4c VA: 0x7596409b4c
	private Void _SetupNewLabels() { }
	// RVA: 0x3df1d38 VA: 0x7596409d38
	private Void _SetupTitle() { }
	// RVA: 0x3def8f4 VA: 0x75964078f4
	private Void SetupView() { }
	// RVA: 0x3df1e30 VA: 0x7596409e30
	private Void _SetOffsetMovePosition(Single val) { }
	// RVA: 0x3df144c VA: 0x759640944c
	private Void _SetOffsetMoved(Boolean moved) { }
	// RVA: 0x3df1fb8 VA: 0x7596409fb8
	public Void OnProductButtonPressed() { }
	// RVA: 0x3df2090 VA: 0x759640a090
	public Void OnRecvButtonPressed() { }
	// RVA: 0x3df21b8 VA: 0x759640a1b8
	public Void OnSendButtonPressed() { }
	// RVA: 0x3df22e0 VA: 0x759640a2e0
	private Void Update() { }
	// RVA: 0x3df23ac VA: 0x759640a3ac
	private Void OnDestroy() { }
	// RVA: 0x3df24b0 VA: 0x759640a4b0
	public Void OnDetailButtonPressed() { }
	// RVA: 0x3df264c VA: 0x759640a64c
	public Void OnBackgroundPressed() { }
	// RVA: 0x3df26cc VA: 0x759640a6cc
	public Void OnUnlockButtonPressed() { }
	// RVA: 0x3df27f4 VA: 0x759640a7f4
	public Void OnStationCharacterButton0Pressed() { }
	// RVA: 0x3df28dc VA: 0x759640a8dc
	public Void OnStationCharacterButton1Pressed() { }
	// RVA: 0x3df29c4 VA: 0x759640a9c4
	public Void .ctor() { }
	// RVA: 0x3df2a48 VA: 0x759640aa48
	private Void <_InitTopMenu>b__50_0(GameObject obj) { }
	// RVA: 0x3df2b0c VA: 0x759640ab0c
	private Void <_InitTopMenu>b__50_1() { }
	// RVA: 0x3df2b4c VA: 0x759640ab4c
	private Void <_TryReceiveTransferRewards>b__54_0(Int32 result) { }
	// RVA: 0x3df2d2c VA: 0x759640ad2c
	private Void <_OnStorageCluePressed>b__61_0(Int32 result) { }
	// RVA: 0x3df2d60 VA: 0x759640ad60
	private Void <_OnStorageUnequipCluePressed>b__63_0(Int32 result) { }
	// RVA: 0x3df2d94 VA: 0x759640ad94
	private Void <OnProductButtonPressed>b__69_0() { }
	// RVA: 0x3df2db0 VA: 0x759640adb0
	private Void <OnRecvButtonPressed>b__70_0(Int32 result) { }
	// RVA: 0x3df319c VA: 0x759640b19c
	private Void <OnSendButtonPressed>b__71_0(Int32 result) { }
	// RVA: 0x3df3218 VA: 0x759640b218
	private Void <OnUnlockButtonPressed>b__76_0(Int32 result) { }
	// RVA: 0x3df325c VA: 0x759640b25c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3df3264 VA: 0x759640b264
	private Void <>xLuaBaseProxy_OnResume() { }
}
```