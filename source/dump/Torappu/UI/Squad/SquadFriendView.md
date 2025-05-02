# SquadFriendView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadFriendTabGroupView _tabGroupView`

- `RectTransform _friendContainer`

- `SimpleLayoutContent _simpleLayout`

- `UIFriendEvent _applyAssistEvent`

- `Text _titleText`

- `Text _remainRefreshTimes`

- `GameObject _refreshButton`

- `GameObject _refreshGroup`

- `CountDownTask m_countDownTask`

- `DateTime m_refreshDataTime`

- `Boolean m_isRefreshPending`

- `AssistAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void Clear()`

- `Void _RenderCountDownValue(TickValue)`

- `Void ApplyTabData(List`1, ProfessionCategory, Action`1)`

- `Void UpdateSelectProfessionTab(ProfessionCategory)`

- `Void ApplyData(GetFriendAssistCharListResponse, EvolvePhaseAndLevel, IPlugin)`

- `Void _InitIfNot()`

- `Void _ClearFriendList()`

- `Void _DealRefreshStatus(DateTime)`

- `Void _EnableRefreshButton()`

- `Void Update()`

- `Void _OnTabSelected(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendView : MonoBehaviour, IHotfixable
{
	private SquadFriendTabGroupView _tabGroupView; // 0x18
	private RectTransform _friendContainer; // 0x20
	private SimpleLayoutContent _simpleLayout; // 0x28
	private UIFriendEvent _applyAssistEvent; // 0x30
	private Text _titleText; // 0x38
	private Text _remainRefreshTimes; // 0x40
	private GameObject _refreshButton; // 0x48
	private GameObject _refreshGroup; // 0x50
	private CountDownTask m_countDownTask; // 0x58
	private DateTime m_refreshDataTime; // 0x60
	private Action`1 m_tabClickAction; // 0x68
	private Boolean m_isRefreshPending; // 0x70
	private AssistAdapter m_adapter; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_Clear; // 0x0
	private static DelegateBridge __Hotfix0__RenderCountDownValue; // 0x8
	private static DelegateBridge __Hotfix0_ApplyTabData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateSelectProfessionTab; // 0x18
	private static DelegateBridge __Hotfix0_ApplyData; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__ClearFriendList; // 0x30
	private static DelegateBridge __Hotfix0__DealRefreshStatus; // 0x38
	private static DelegateBridge __Hotfix0__EnableRefreshButton; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__OnTabSelected; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x23c9cc0 VA: 0x75949e1cc0
	public Void Clear() { }
	// RVA: 0x23c9d9c VA: 0x75949e1d9c
	private Void _RenderCountDownValue(TickValue tick) { }
	// RVA: 0x23ca010 VA: 0x75949e2010
	public Void ApplyTabData(List`1 professionList, ProfessionCategory selectProfession, Action`1 clickAction) { }
	// RVA: 0x23ca12c VA: 0x75949e212c
	public Void UpdateSelectProfessionTab(ProfessionCategory selectProfession) { }
	// RVA: 0x23ca1b4 VA: 0x75949e21b4
	public Void ApplyData(GetFriendAssistCharListResponse data, EvolvePhaseAndLevel maxEvolvePhaseAndLevel, IPlugin statePlugin) { }
	// RVA: 0x23ca388 VA: 0x75949e2388
	private Void _InitIfNot() { }
	// RVA: 0x23c9d28 VA: 0x75949e1d28
	private Void _ClearFriendList() { }
	// RVA: 0x23ca430 VA: 0x75949e2430
	private Void _DealRefreshStatus(DateTime newAllowTs) { }
	// RVA: 0x23c9f44 VA: 0x75949e1f44
	private Void _EnableRefreshButton() { }
	// RVA: 0x23ca79c VA: 0x75949e279c
	private Void Update() { }
	// RVA: 0x23ca818 VA: 0x75949e2818
	private Void _OnTabSelected(ProfessionCategory profession) { }
	// RVA: 0x23ca8d8 VA: 0x75949e28d8
	public Void .ctor() { }
}
```