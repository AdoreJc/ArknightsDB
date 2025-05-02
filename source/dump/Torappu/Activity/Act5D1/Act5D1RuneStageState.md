# Act5D1RuneStageState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1RuneStageStateBean _stateBean`

- `Act5D1RuneStageRuneContainer _runeContainer`

- `Act5D1RuneStageSelectRuneContainer _selectedContainer`

- `Act5D1RuneStageDetailContainer _detailContainer`

- `Act5D1RuneStagePreview _stagePreview`

- `Image _backImage`

- `Text _pointText`

- `Text _pointText2`

- `Act5D1ResourceBar _resourceBar`

- `String m_stageId`

- `String m_runeId`

- `Tween m_pointTextTween`

- `Int32 m_currentPoint`


## Methods

- `Void RefreshPointInfo()`

- `Void Refresh()`

- `Void OnClick(String)`

- `Void OnClickToEnemyHandBook()`

- `Void ToDetailState()`

- `Void CleanAllSelect()`

- `Void OpenSquadPage()`

- `BattleActivityMeta _GenerateActMeta4BattleFinish(String)`

- `DataBundle _GenerateDataBundleToRuneStage(String)`

- `Void _TweenPointText(Int32)`

- `Void _SetPointText(Int32)`

- `Void <RegisterToDataListener>b__14_0(IStateBean)`

- `Void <OnEnter>b__20_0()`

- `Int32 <_TweenPointText>b__30_0()`

- `Void <_TweenPointText>b__30_1(Int32)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStageState : PopupFadeState
{
	public static Color NEW_HAND_COLOR; // 0x0
	public static Color WARNING_COLOR; // 0x10
	private Act5D1RuneStageStateBean _stateBean; // 0x70
	private Act5D1RuneStageRuneContainer _runeContainer; // 0x78
	private Act5D1RuneStageSelectRuneContainer _selectedContainer; // 0x80
	private Act5D1RuneStageDetailContainer _detailContainer; // 0x88
	private Act5D1RuneStagePreview _stagePreview; // 0x90
	private Image _backImage; // 0x98
	private Text _pointText; // 0xa0
	private Text _pointText2; // 0xa8
	private Act5D1ResourceBar _resourceBar; // 0xb0
	private String m_stageId; // 0xb8
	private String m_runeId; // 0xc0
	private const Single DUR_PER_POINT; // 0x0
	private const Single MAX_DUR_POINT; // 0x0
	private Tween m_pointTextTween; // 0xc8
	private Int32 m_currentPoint; // 0xd0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnResume; // 0x30
	private static DelegateBridge __Hotfix0_RefreshPointInfo; // 0x38
	private static DelegateBridge __Hotfix0_Refresh; // 0x40
	private static DelegateBridge __Hotfix0_OnClick; // 0x48
	private static DelegateBridge __Hotfix0_OnClickToEnemyHandBook; // 0x50
	private static DelegateBridge __Hotfix0_OnEnter; // 0x58
	private static DelegateBridge __Hotfix0_ToDetailState; // 0x60
	private static DelegateBridge __Hotfix0_CleanAllSelect; // 0x68
	private static DelegateBridge __Hotfix0_OpenSquadPage; // 0x70
	private static DelegateBridge __Hotfix0__GenerateActMeta4BattleFinish; // 0x78
	private static DelegateBridge __Hotfix0__GenerateDataBundleToRuneStage; // 0x80
	private static DelegateBridge __Hotfix0__TweenPointText; // 0x88
	private static DelegateBridge __Hotfix0__SetPointText; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x31cf5fc VA: 0x75957e75fc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31cf674 VA: 0x75957e7674
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31cf7fc VA: 0x75957e77fc
	protected override Void OnResume() { }
	// RVA: 0x31cf964 VA: 0x75957e7964
	public Void RefreshPointInfo() { }
	// RVA: 0x31cf880 VA: 0x75957e7880
	public Void Refresh() { }
	// RVA: 0x31cfd8c VA: 0x75957e7d8c
	public Void OnClick(String runeId) { }
	// RVA: 0x31d01d8 VA: 0x75957e81d8
	public Void OnClickToEnemyHandBook() { }
	// RVA: 0x31d073c VA: 0x75957e873c
	protected override Void OnEnter() { }
	// RVA: 0x31d0830 VA: 0x75957e8830
	public Void ToDetailState() { }
	// RVA: 0x31d094c VA: 0x75957e894c
	public Void CleanAllSelect() { }
	// RVA: 0x31d0a4c VA: 0x75957e8a4c
	public Void OpenSquadPage() { }
	// RVA: 0x31d0ed0 VA: 0x75957e8ed0
	private BattleActivityMeta _GenerateActMeta4BattleFinish(String activityId) { }
	// RVA: 0x31d0f94 VA: 0x75957e8f94
	private DataBundle _GenerateDataBundleToRuneStage(String activityId) { }
	// RVA: 0x31cfae8 VA: 0x75957e7ae8
	private Void _TweenPointText(Int32 targetValue) { }
	// RVA: 0x31d1094 VA: 0x75957e9094
	private Void _SetPointText(Int32 value) { }
	// RVA: 0x31d11d8 VA: 0x75957e91d8
	public Void .ctor() { }
	// RVA: 0x31d1258 VA: 0x75957e9258
	private static Void .cctor() { }
	// RVA: 0x31d12bc VA: 0x75957e92bc
	private Void <RegisterToDataListener>b__14_0(IStateBean stateBean) { }
	// RVA: 0x31d1364 VA: 0x75957e9364
	private Void <OnEnter>b__20_0() { }
	// RVA: 0x31d13a8 VA: 0x75957e93a8
	private Int32 <_TweenPointText>b__30_0() { }
	// RVA: 0x31d13b0 VA: 0x75957e93b0
	private Void <_TweenPointText>b__30_1(Int32 val) { }
	// RVA: 0x31d13b4 VA: 0x75957e93b4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x31d13bc VA: 0x75957e93bc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x31d13c4 VA: 0x75957e93c4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```