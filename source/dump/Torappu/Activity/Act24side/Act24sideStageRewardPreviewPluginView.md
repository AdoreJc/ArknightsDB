# Act24sideStageRewardPreviewPluginView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `StageRewardPreviewItem _normalRewardView`

- `SimpleLayoutContent _meldingList`

- `GameObject _meldingListGo`

- `String m_actId`

- `StageViewModel m_stageModel`

- `Boolean m_hasInited`

- `MeldingListAdapter m_meldingListAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateNormalRewardList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideStageRewardPreviewPluginView : StageRewardPreviewPluginView
{
	private StageRewardPreviewItem _normalRewardView; // 0x20
	private SimpleLayoutContent _meldingList; // 0x28
	private GameObject _meldingListGo; // 0x30
	private List`1 m_normalRewardList; // 0x38
	private List`1 m_meldingRewardList; // 0x40
	private String m_actId; // 0x48
	private StageViewModel m_stageModel; // 0x50
	private Boolean m_hasInited; // 0x58
	private MeldingListAdapter m_meldingListAdapter; // 0x60
	private static DelegateBridge __Hotfix0_Dispose; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateNormalRewardList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32e3c60 VA: 0x75958fbc60
	public override Void Dispose() { }
	// RVA: 0x32e3cc4 VA: 0x75958fbcc4
	public override Void Render(StageViewModel selectedStage) { }
	// RVA: 0x32e409c VA: 0x75958fc09c
	private Void _InitIfNot() { }
	// RVA: 0x32e3ed0 VA: 0x75958fbed0
	private Void _UpdateNormalRewardList() { }
	// RVA: 0x32e4200 VA: 0x75958fc200
	public Void .ctor() { }
}
```