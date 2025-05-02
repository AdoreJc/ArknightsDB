# RoguelikeTopicMonthTaskState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicMonthTaskView _taskView`

- `Single _propRefreshDelay`

- `Boolean m_hasInited`

- `String m_topicId`

- `RoguelikeTopicMonthTaskStateBean m_stateBean`


## Methods

- `Void _InitIfNot(RoguelikeTopicPage)`

- `Void _UpdateTaskModel()`

- `IEnumerator _UpdateTaskModelAfterDelay()`

- `Void _SendRefreshMissionRequest(String, Int32, Action)`

- `Void _OnTaskRefresh(RoguelikeTopicMonthTaskModel)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthTaskState : PopupFloatState
{
	private RoguelikeTopicMonthTaskView _taskView; // 0x70
	private Single _propRefreshDelay; // 0x78
	private Boolean m_hasInited; // 0x7c
	private String m_topicId; // 0x80
	private RoguelikeTopicMonthTaskStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTaskModel; // 0x18
	private static DelegateBridge __Hotfix0__UpdateTaskModelAfterDelay; // 0x20
	private static DelegateBridge __Hotfix0__SendRefreshMissionRequest; // 0x28
	private static DelegateBridge __Hotfix0__OnTaskRefresh; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x265953c VA: 0x7594c7153c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26595a4 VA: 0x7594c715a4
	protected override Void OnEnter() { }
	// RVA: 0x2659890 VA: 0x7594c71890
	private Void _InitIfNot(RoguelikeTopicPage page) { }
	// RVA: 0x265999c VA: 0x7594c7199c
	private Void _UpdateTaskModel() { }
	// RVA: 0x2659ea0 VA: 0x7594c71ea0
	private IEnumerator _UpdateTaskModelAfterDelay() { }
	// RVA: 0x2659f74 VA: 0x7594c71f74
	private Void _SendRefreshMissionRequest(String topicId, Int32 index, Action onComplete) { }
	// RVA: 0x265a1fc VA: 0x7594c721fc
	private Void _OnTaskRefresh(RoguelikeTopicMonthTaskModel taskModel) { }
	// RVA: 0x265a3d0 VA: 0x7594c723d0
	public Void .ctor() { }
	// RVA: 0x265a530 VA: 0x7594c72530
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```