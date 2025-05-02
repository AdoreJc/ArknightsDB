# Act13sideDailyMissionReplaceState

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideDailyMissionReplaceView _view`

- `RectTransform _backBtnRt`

- `Boolean m_hasInited`

- `Act13sideDailyMissionReplaceStateBean m_stateBean`

- `TemplateActivityController m_stageController`


## Properties

- `TemplateActivityController actController`

- `String activityId`


## Methods

- `Void _InitIfNot()`

- `Void _SelectItem(Int32, Boolean)`

- `Void OnBtnReplaceClick()`

- `TemplateActivityController get_actController()`

- `String get_activityId()`

- `T _FetchStageController()`

- `Void <OnBtnReplaceClick>b__9_0(Act13SideDailyMissionReplaceResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionReplaceState : PopupFloatState
{
	private Act13sideDailyMissionReplaceView _view; // 0x70
	private RectTransform _backBtnRt; // 0x78
	private Boolean m_hasInited; // 0x80
	private Act13sideDailyMissionReplaceStateBean m_stateBean; // 0x88
	private TemplateActivityController m_stageController; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SelectItem; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnReplaceClick; // 0x20
	private static DelegateBridge __Hotfix0_get_actController; // 0x28
	private static DelegateBridge __Hotfix0_get_activityId; // 0x30
	private static DelegateBridge __Hotfix0__FetchStageController; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected TemplateActivityController actController { get; }
	protected String activityId { get; }

	// RVA: 0x342ae2c VA: 0x7595a42e2c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x342ae94 VA: 0x7595a42e94
	protected override Void OnEnter() { }
	// RVA: 0x342af38 VA: 0x7595a42f38
	private Void _InitIfNot() { }
	// RVA: 0x342b1a8 VA: 0x7595a431a8
	private Void _SelectItem(Int32 index, Boolean isSelect) { }
	// RVA: 0x342b294 VA: 0x7595a43294
	public Void OnBtnReplaceClick() { }
	// RVA: 0x342b514 VA: 0x7595a43514
	protected TemplateActivityController get_actController() { }
	// RVA: 0x342b0d8 VA: 0x7595a430d8
	protected String get_activityId() { }
	// RVA: 0x VA: 0x0
	private T _FetchStageController() { }
	// RVA: 0x342b5ec VA: 0x7595a435ec
	public Void .ctor() { }
	// RVA: 0x342b698 VA: 0x7595a43698
	private Void <OnBtnReplaceClick>b__9_0(Act13SideDailyMissionReplaceResponse response) { }
	// RVA: 0x342b7a0 VA: 0x7595a437a0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```