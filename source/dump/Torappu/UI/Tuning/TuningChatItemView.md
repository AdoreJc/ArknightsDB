# TuningChatItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Image _avatar`

- `GameObject _bgNormal`

- `GameObject _bgMajor`

- `GameObject _bgHidden`

- `GameObject _panelFault`

- `CanvasGroup _panelSelected`

- `CanvasGroup _panelUnselected`

- `Boolean m_isInited`

- `String m_cachedId`

- `String m_cachedSelectedId`

- `UIStateFinder m_stateFinder`

- `FadeSwitchTween m_selectTween`

- `FadeSwitchTween m_unselectTween`


## Methods

- `Void Render(TuningChatItemViewModel, String)`

- `Void _InitIfNot(String, String)`

- `Void _LoadAvatar(String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningChatItemView : MonoBehaviour, IHotfixable
{
	private Image _avatar; // 0x18
	private GameObject _bgNormal; // 0x20
	private GameObject _bgMajor; // 0x28
	private GameObject _bgHidden; // 0x30
	private GameObject _panelFault; // 0x38
	private CanvasGroup _panelSelected; // 0x40
	private CanvasGroup _panelUnselected; // 0x48
	private Boolean m_isInited; // 0x50
	private String m_cachedId; // 0x58
	private String m_cachedSelectedId; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private FadeSwitchTween m_selectTween; // 0x78
	private FadeSwitchTween m_unselectTween; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__LoadAvatar; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x231813c VA: 0x759493013c
	public Void Render(TuningChatItemViewModel viewModel, String selectedInvestId) { }
	// RVA: 0x23183c8 VA: 0x75949303c8
	private Void _InitIfNot(String investId, String selectedId) { }
	// RVA: 0x2318770 VA: 0x7594930770
	private Void _LoadAvatar(String avatarId) { }
	// RVA: 0x231886c VA: 0x759493086c
	public Void OnClick() { }
	// RVA: 0x2318994 VA: 0x7594930994
	public Void .ctor() { }
}
```