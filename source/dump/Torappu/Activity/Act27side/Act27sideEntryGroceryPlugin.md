# Act27sideEntryGroceryPlugin

**Namespace:** `Torappu.Activity.Act27side`


## Fields

- `UICommonTrackPoint _mileStoneTrackPoint`

- `Text _textUnlockDesc`

- `GameObject _panelLocked`

- `GameObject _panelUnlock`

- `GameObject _panelAfterSettle`

- `String m_actId`

- `String m_toastDesc`

- `TrackPointViewProperty m_trackPointProperty`

- `Boolean m_hasInited`

- `Status m_cachedCurrStatus`


## Methods

- `Void OpenGrocery()`

- `Void _InitIfNot()`

- `Void _SendNextDayRequestAndOpenGrocery()`

- `Void _OnOpenGroceryPage(GroceryNextDayResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act27side
public class Act27sideEntryGroceryPlugin : TemplateActivityCommonPlugin, IHotfixable
{
	private UICommonTrackPoint _mileStoneTrackPoint; // 0x28
	private Text _textUnlockDesc; // 0x30
	private GameObject _panelLocked; // 0x38
	private GameObject _panelUnlock; // 0x40
	private GameObject _panelAfterSettle; // 0x48
	private String m_actId; // 0x50
	private String m_toastDesc; // 0x58
	private TrackPointViewProperty m_trackPointProperty; // 0x60
	private Boolean m_hasInited; // 0x68
	private Status m_cachedCurrStatus; // 0x6c
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OpenGrocery; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SendNextDayRequestAndOpenGrocery; // 0x18
	private static DelegateBridge __Hotfix0__OnOpenGroceryPage; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3269d58 VA: 0x7595881d58
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3269fe4 VA: 0x7595881fe4
	public Void OpenGrocery() { }
	// RVA: 0x3269f3c VA: 0x7595881f3c
	private Void _InitIfNot() { }
	// RVA: 0x326a148 VA: 0x7595882148
	private Void _SendNextDayRequestAndOpenGrocery() { }
	// RVA: 0x326a3d0 VA: 0x75958823d0
	private Void _OnOpenGroceryPage(GroceryNextDayResponse response) { }
	// RVA: 0x326a4c8 VA: 0x75958824c8
	public Void .ctor() { }
}
```