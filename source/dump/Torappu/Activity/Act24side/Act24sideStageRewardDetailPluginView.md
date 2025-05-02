# Act24sideStageRewardDetailPluginView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `RectTransform _viewRoot`

- `SimpleLayoutContent _firstCompleteList`

- `SimpleLayoutContent _normalList`

- `Boolean m_hasInited`

- `String m_actId`

- `StageData m_stageData`

- `RewardListAdapter m_firstCompleteListAdapter`

- `RewardListAdapter m_normalListAdapter`

- `Boolean m_getFlag`

- `Boolean m_completeFlag`


## Methods

- `Void _InitData()`

- `Int32 _SortReward(MeldingDataStruct, MeldingDataStruct)`

- `MeldingDataStruct _CreateMeldingStruct(DisplayDetailRewards)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStageRewardDetailPluginView : StageRewardDetailPluginView
{
	private RectTransform _viewRoot; // 0x18
	private SimpleLayoutContent _firstCompleteList; // 0x20
	private SimpleLayoutContent _normalList; // 0x28
	private Boolean m_hasInited; // 0x30
	private String m_actId; // 0x38
	private StageData m_stageData; // 0x40
	private RewardListAdapter m_firstCompleteListAdapter; // 0x48
	private RewardListAdapter m_normalListAdapter; // 0x50
	private List`1 m_firstCompleteRewardList; // 0x58
	private List`1 m_normalRewardList; // 0x60
	private Boolean m_getFlag; // 0x68
	private Boolean m_completeFlag; // 0x69
	private static DelegateBridge __Hotfix0_Dispose; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitData; // 0x10
	private static DelegateBridge __Hotfix0__SortReward; // 0x18
	private static DelegateBridge __Hotfix0__CreateMeldingStruct; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32e2d48 VA: 0x75958fad48
	public override Void Dispose() { }
	// RVA: 0x32e2dac VA: 0x75958fadac
	public override Void Render(String actId, StageData stageData, Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x32e2ff0 VA: 0x75958faff0
	private Void _InitData() { }
	// RVA: 0x32e36c8 VA: 0x75958fb6c8
	private Int32 _SortReward(MeldingDataStruct x, MeldingDataStruct y) { }
	// RVA: 0x32e353c VA: 0x75958fb53c
	private MeldingDataStruct _CreateMeldingStruct(DisplayDetailRewards rewardData) { }
	// RVA: 0x32e335c VA: 0x75958fb35c
	private Void _InitIfNot() { }
	// RVA: 0x32e392c VA: 0x75958fb92c
	public Void .ctor() { }
}
```