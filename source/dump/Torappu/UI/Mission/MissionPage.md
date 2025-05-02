# MissionPage

**Namespace:** `Torappu.UI.Mission`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `MissionState _defaultState`

- `Canvas _canvas`

- `RectTransform _dialogContainer`

- `DataBundle m_dataBundleCache`

- `UICompDialogMgr m_dialogMgr`


## Properties

- `UICompDialogMgr dialogMgr`


## Methods

- `UICompDialogMgr get_dialogMgr()`

- `Void _OnInitTopMenu(GameObject)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnOpenCharShowPage(String)`

- `Void _EventOnOpenGuideRewardPreview()`

- `Void _EventOnOpenFullOpenDialog()`

- `Void <_OnInitTopMenu>b__15_0()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionPage : StateEnginePage, IValueMsgReceiver
{
	public const Int32 MSG_OPEN_GUIDE_REWARD_PREVIEW; // 0x0
	public const Int32 MSG_OPEN_CHAR_SHOW_PAGE; // 0x0
	public const Int32 MSG_OPEN_FULL_OPEN_DLG; // 0x0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private MissionState _defaultState; // 0xf0
	private Canvas _canvas; // 0xf8
	private RectTransform _dialogContainer; // 0x100
	private DataBundle m_dataBundleCache; // 0x108
	private UICompDialogMgr m_dialogMgr; // 0x110
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x20
	private static DelegateBridge __Hotfix0__LoadInitMissionPageType; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0__EventOnOpenCharShowPage; // 0x38
	private static DelegateBridge __Hotfix0__EventOnOpenGuideRewardPreview; // 0x40
	private static DelegateBridge __Hotfix0__EventOnOpenFullOpenDialog; // 0x48
	private static DelegateBridge __Hotfix0_DataBundleToMissionPage; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override AVGPageKey avgPage { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x2742d78 VA: 0x7594d5ad78
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x2742de0 VA: 0x7594d5ade0
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2742e48 VA: 0x7594d5ae48
	protected override Void OnStart() { }
	// RVA: 0x27430a8 VA: 0x7594d5b0a8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x27431a0 VA: 0x7594d5b1a0
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2742f60 VA: 0x7594d5af60
	private Nullable`1 _LoadInitMissionPageType(DataBundle dataBundle) { }
	// RVA: 0x27432e8 VA: 0x7594d5b2e8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27434d4 VA: 0x7594d5b4d4
	private Void _EventOnOpenCharShowPage(String charId) { }
	// RVA: 0x27433d0 VA: 0x7594d5b3d0
	private Void _EventOnOpenGuideRewardPreview() { }
	// RVA: 0x27435e4 VA: 0x7594d5b5e4
	private Void _EventOnOpenFullOpenDialog() { }
	// RVA: 0x27436e8 VA: 0x7594d5b6e8
	public static DataBundle DataBundleToMissionPage(MissionPageType missionType) { }
	// RVA: 0x27437a8 VA: 0x7594d5b7a8
	public Void .ctor() { }
	// RVA: 0x2743818 VA: 0x7594d5b818
	private Void <_OnInitTopMenu>b__15_0() { }
	// RVA: 0x2743820 VA: 0x7594d5b820
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x2743828 VA: 0x7594d5b828
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2743830 VA: 0x7594d5b830
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```