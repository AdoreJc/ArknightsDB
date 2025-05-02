# Act38sideEntryFireworkPuzzlePlugin

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `GameObject _panelLocked`

- `GameObject _panelUnlock`

- `GameObject _panelClosed`

- `Text _textUnlockDesc`

- `GameObject _panelNew`

- `Status m_cachedCurrStatus`

- `String m_cachedLockedToast`

- `String m_cachedClosedToast`

- `String m_cachedActId`

- `String m_cachedCrossDayTrackId`

- `Boolean m_hasDailyTrack`


## Methods

- `Void EventOnPuzzleClicked()`

- `Void _OnGetInfoProceed(FireworkPuzzleGetInfoResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideEntryFireworkPuzzlePlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private GameObject _panelLocked; // 0x28
	private GameObject _panelUnlock; // 0x30
	private GameObject _panelClosed; // 0x38
	private Text _textUnlockDesc; // 0x40
	private GameObject _panelNew; // 0x48
	private Status m_cachedCurrStatus; // 0x50
	private String m_cachedLockedToast; // 0x58
	private String m_cachedClosedToast; // 0x60
	private String m_cachedActId; // 0x68
	private String m_cachedCrossDayTrackId; // 0x70
	private Boolean m_hasDailyTrack; // 0x78
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_EventOnPuzzleClicked; // 0x8
	private static DelegateBridge __Hotfix0__OnGetInfoProceed; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x323dc8c VA: 0x7595855c8c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x323de9c VA: 0x7595855e9c
	public Void EventOnPuzzleClicked() { }
	// RVA: 0x323e0ec VA: 0x75958560ec
	private Void _OnGetInfoProceed(FireworkPuzzleGetInfoResponse response) { }
	// RVA: 0x323e228 VA: 0x7595856228
	public Void .ctor() { }
}
```