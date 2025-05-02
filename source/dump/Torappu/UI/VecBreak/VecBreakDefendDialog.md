# VecBreakDefendDialog

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Text _upperText`

- `SimpleLayoutContent _prevCharList`

- `SimpleLayoutContent _currCharList`

- `Boolean m_hasInited`

- `Action m_onConfirm`

- `Int32 m_defendLimit`

- `String m_toastText`

- `CharListAdapter m_prevCharListAdapter`

- `CharListAdapter m_newCharListAdapter`


## Methods

- `Void _InitIfNot()`

- `Void _OnConfirm(String, String, List`1)`

- `Void OnCancelClicked()`

- `Void OnConfirmClicked()`

- `Void <_OnConfirm>b__14_0(VecBreakSetDefendResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefendDialog : UICustomDialog`1
{
	private Text _upperText; // 0x70
	private SimpleLayoutContent _prevCharList; // 0x78
	private SimpleLayoutContent _currCharList; // 0x80
	private Boolean m_hasInited; // 0x88
	private Action m_onConfirm; // 0x90
	private Int32 m_defendLimit; // 0x98
	private String m_toastText; // 0xa0
	private List`1 m_prevCharModelList; // 0xa8
	private List`1 m_newCharModelList; // 0xb0
	private CharListAdapter m_prevCharListAdapter; // 0xb8
	private CharListAdapter m_newCharListAdapter; // 0xc0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnConfirm; // 0x10
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22c79a4 VA: 0x75948df9a4
	protected override Void OnRender(Options options) { }
	// RVA: 0x22c7bc0 VA: 0x75948dfbc0
	private Void _InitIfNot() { }
	// RVA: 0x22c7ddc VA: 0x75948dfddc
	private Void _OnConfirm(String actId, String stageId, List`1 newSquad) { }
	// RVA: 0x22c8228 VA: 0x75948e0228
	public Void OnCancelClicked() { }
	// RVA: 0x22c82ac VA: 0x75948e02ac
	public Void OnConfirmClicked() { }
	// RVA: 0x22c8330 VA: 0x75948e0330
	public Void .ctor() { }
	// RVA: 0x22c83c0 VA: 0x75948e03c0
	private Void <_OnConfirm>b__14_0(VecBreakSetDefendResponse response) { }
}
```