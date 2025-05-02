# Act12D6OuterBuffDetailView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Image _imgLevelBg`

- `Image _imgLevel`

- `Image _imgIcon`

- `Text _txtLevel`

- `Text _txtPrevLevel`

- `Text _txtNameLevel`

- `Text _txtDesc`

- `ScrollRect _effects`

- `Text _confirmTip`

- `GameObject _effectTxtObj`

- `UIStringEvent <onClicked>k__BackingField`

- `Boolean m_isFullFlag`

- `String m_buffId`

- `Int32 m_cachedNextLevel`

- `Int32 m_cachedFullLevel`


## Properties

- `UIStringEvent onClicked`


## Methods

- `UIStringEvent get_onClicked()`

- `Void set_onClicked(UIStringEvent)`

- `Void Render(Act12D6OuterBuffDetailStateBean)`

- `Void _ScrollToNextInfo()`

- `Void _OnScrollRectTween(Single)`

- `Void EventOnClicked()`

- `Single <_OnScrollRectTween>b__20_0()`

- `Void <_OnScrollRectTween>b__20_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6OuterBuffDetailView : MonoBehaviour, IHotfixable
{
	private Image _imgLevelBg; // 0x18
	private Image _imgLevel; // 0x20
	private Image _imgIcon; // 0x28
	private Text _txtLevel; // 0x30
	private Text _txtPrevLevel; // 0x38
	private Text _txtNameLevel; // 0x40
	private Text _txtDesc; // 0x48
	private ScrollRect _effects; // 0x50
	private Text _confirmTip; // 0x58
	private GameObject _effectTxtObj; // 0x60
	private UIStringEvent <onClicked>k__BackingField; // 0x68
	private Boolean m_isFullFlag; // 0x70
	private String m_buffId; // 0x78
	private Int32 m_cachedNextLevel; // 0x80
	private Int32 m_cachedFullLevel; // 0x84
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__ScrollToNextInfo; // 0x18
	private static DelegateBridge __Hotfix0__OnScrollRectTween; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public UIStringEvent onClicked { get; set; }

	// RVA: 0x3477144 VA: 0x7595a8f144
	public UIStringEvent get_onClicked() { }
	// RVA: 0x34771ac VA: 0x7595a8f1ac
	public Void set_onClicked(UIStringEvent value) { }
	// RVA: 0x3477230 VA: 0x7595a8f230
	public Void Render(Act12D6OuterBuffDetailStateBean stateBean) { }
	// RVA: 0x34778c4 VA: 0x7595a8f8c4
	private Void _ScrollToNextInfo() { }
	// RVA: 0x3477944 VA: 0x7595a8f944
	private Void _OnScrollRectTween(Single pos) { }
	// RVA: 0x3477ab8 VA: 0x7595a8fab8
	public Void EventOnClicked() { }
	// RVA: 0x3477b60 VA: 0x7595a8fb60
	public Void .ctor() { }
	// RVA: 0x3477bd0 VA: 0x7595a8fbd0
	private Single <_OnScrollRectTween>b__20_0() { }
	// RVA: 0x3477bec VA: 0x7595a8fbec
	private Void <_OnScrollRectTween>b__20_1(Single val) { }
}
```