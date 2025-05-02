# RL04FragmentDialog

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `UIAnimationLocation _enterAnim`

- `CanvasGroup _canvasGroup`

- `RL04FragmentWeightView _weightView`

- `RL04FragmentListView _listView`

- `UIGuidebookTrigger _guidebookTrigger`

- `RectTransform _panelBackRt`

- `RL04FragmentProperty m_property`

- `Boolean m_hasInited`

- `UICompDialogMgr m_dialogMgr`

- `Int32 m_fragmentDialogInst`

- `Int32 m_fragmentCharSelectDialogInst`

- `Tween m_enterAnim`


## Methods

- `Void EventOnBackBtnClicked()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _HandleFragmentDetailCallback(ValueBundle)`

- `Void _HandleFragmentCharSelectCallback(ValueBundle)`

- `Void _InitIfNot()`

- `Void _EventOnItemClicked(String)`

- `Void _EventOnCharCardClicked(Int32)`

- `Void _EventOnListSwitchBtnClicked()`

- `Void <>xLuaBaseProxy_OnInit()`

- `UISwitchTween <>xLuaBaseProxy_GenerateShowTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDialog : RoguelikeFragmentDialog, ICompDialogCallBack, IHotfixable
{
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	private UIAnimationLocation _enterAnim; // 0x48
	private CanvasGroup _canvasGroup; // 0x58
	private RL04FragmentWeightView _weightView; // 0x60
	private RL04FragmentListView _listView; // 0x68
	private UIGuidebookTrigger _guidebookTrigger; // 0x70
	private RectTransform _panelBackRt; // 0x78
	private RL04FragmentProperty m_property; // 0x80
	private Boolean m_hasInited; // 0x88
	private UICompDialogMgr m_dialogMgr; // 0x90
	private Int32 m_fragmentDialogInst; // 0x98
	private Int32 m_fragmentCharSelectDialogInst; // 0x9c
	private Tween m_enterAnim; // 0xa0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge __Hotfix0__HandleFragmentDetailCallback; // 0x28
	private static DelegateBridge __Hotfix0__HandleFragmentCharSelectCallback; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x40
	private static DelegateBridge __Hotfix0__EventOnCharCardClicked; // 0x48
	private static DelegateBridge __Hotfix0__EventOnListSwitchBtnClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2b23a8c VA: 0x759513ba8c
	protected override Void OnInit() { }
	// RVA: 0x2b23d80 VA: 0x759513bd80
	protected override Void OnRender(Options input) { }
	// RVA: 0x2b2401c VA: 0x759513c01c
	public override UISwitchTween GenerateShowTween() { }
	// RVA: 0x2b24154 VA: 0x759513c154
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x2b24228 VA: 0x759513c228
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2b242f4 VA: 0x759513c2f4
	private Void _HandleFragmentDetailCallback(ValueBundle output) { }
	// RVA: 0x2b243dc VA: 0x759513c3dc
	private Void _HandleFragmentCharSelectCallback(ValueBundle output) { }
	// RVA: 0x2b23b00 VA: 0x759513bb00
	private Void _InitIfNot() { }
	// RVA: 0x2b24a48 VA: 0x759513ca48
	private Void _EventOnItemClicked(String instId) { }
	// RVA: 0x2b24d54 VA: 0x759513cd54
	private Void _EventOnCharCardClicked(Int32 index) { }
	// RVA: 0x2b24f98 VA: 0x759513cf98
	private Void _EventOnListSwitchBtnClicked() { }
	// RVA: 0x2b250cc VA: 0x759513d0cc
	public Void .ctor() { }
	// RVA: 0x2b251e4 VA: 0x759513d1e4
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x2b251ec VA: 0x759513d1ec
	private UISwitchTween <>xLuaBaseProxy_GenerateShowTween() { }
}
```