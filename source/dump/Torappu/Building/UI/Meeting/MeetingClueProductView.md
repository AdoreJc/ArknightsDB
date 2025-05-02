# MeetingClueProductView

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _stopCharacterPanel`

- `GameObject _stopRoomPanel`

- `GameObject _runningCharacterPanel`

- `GameObject _runningRoomPanel`

- `GameObject _emptyCharacterPanel`

- `GameObject _emptyRoomPanel`

- `MeetingClueRestTimeLabel _restTimeLabel`

- `StretchProgressBar _productProgressBar`

- `Text _creditCharacterProduct`

- `Text _creditRoomProduct`

- `Image _roomProductIcon`

- `Single _updateInterval`

- `Image _blurBG`

- `Button _fetchButton`

- `GameObject _newLabel`

- `GameObject _storageFullHint`

- `CanvasGroup _canvasGroup`

- `Single _fadeDuration`

- `Text _fetchButtonText`

- `IMeetingSession m_session`

- `Single m_timer`

- `Boolean m_shown`

- `Boolean m_needUpdateProgress`

- `Boolean m_storageFull`

- `Boolean m_tweening`

- `Action m_onCloseCallback`


## Properties

- `Boolean shown`


## Methods

- `Void Setup(IMeetingSession)`

- `Void _SetupView()`

- `Void _RefreshRoomClue()`

- `Void Show(Action)`

- `Void Hide()`

- `Boolean get_shown()`

- `Boolean _RefreshProgressBar()`

- `Void UpdateFetchCharacterProduct()`

- `Void Update()`

- `Void OnFetchRoomProductClueButtonPressed()`

- `Void OnCloseButtonPressed()`

- `Void <Show>b__29_1(Single)`

- `Void <Show>b__29_2()`

- `Void <Hide>b__30_1(Single)`

- `Void <Hide>b__30_2()`

- `Void <OnFetchRoomProductClueButtonPressed>b__36_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class MeetingClueProductView : MonoBehaviour
{
	private GameObject _stopCharacterPanel; // 0x18
	private GameObject _stopRoomPanel; // 0x20
	private GameObject _runningCharacterPanel; // 0x28
	private GameObject _runningRoomPanel; // 0x30
	private GameObject _emptyCharacterPanel; // 0x38
	private GameObject _emptyRoomPanel; // 0x40
	private MeetingClueRestTimeLabel _restTimeLabel; // 0x48
	private StretchProgressBar _productProgressBar; // 0x50
	private Text _creditCharacterProduct; // 0x58
	private Text _creditRoomProduct; // 0x60
	private Image _roomProductIcon; // 0x68
	private Single _updateInterval; // 0x70
	private Image _blurBG; // 0x78
	private Button _fetchButton; // 0x80
	private GameObject _newLabel; // 0x88
	private GameObject _storageFullHint; // 0x90
	private CanvasGroup _canvasGroup; // 0x98
	private Single _fadeDuration; // 0xa0
	private Text _fetchButtonText; // 0xa8
	private IMeetingSession m_session; // 0xb0
	private Single m_timer; // 0xb8
	private Boolean m_shown; // 0xbc
	private Boolean m_needUpdateProgress; // 0xbd
	private Boolean m_storageFull; // 0xbe
	private Boolean m_tweening; // 0xbf
	private Action m_onCloseCallback; // 0xc0

	public Boolean shown { get; }

	// RVA: 0x3df7a00 VA: 0x759640fa00
	public Void Setup(IMeetingSession session) { }
	// RVA: 0x3df7a20 VA: 0x759640fa20
	private Void _SetupView() { }
	// RVA: 0x3df8a34 VA: 0x7596410a34
	private Void _RefreshRoomClue() { }
	// RVA: 0x3df8d3c VA: 0x7596410d3c
	public Void Show(Action onClose) { }
	// RVA: 0x3df8f90 VA: 0x7596410f90
	public Void Hide() { }
	// RVA: 0x3df9248 VA: 0x7596411248
	public Boolean get_shown() { }
	// RVA: 0x3df84a8 VA: 0x75964104a8
	private Boolean _RefreshProgressBar() { }
	// RVA: 0x3df9250 VA: 0x7596411250
	public Void UpdateFetchCharacterProduct() { }
	// RVA: 0x3df9254 VA: 0x7596411254
	private Void Update() { }
	// RVA: 0x3df92ac VA: 0x75964112ac
	public Void OnFetchRoomProductClueButtonPressed() { }
	// RVA: 0x3df955c VA: 0x759641155c
	public Void OnCloseButtonPressed() { }
	// RVA: 0x3df956c VA: 0x759641156c
	public Void .ctor() { }
	// RVA: 0x3df9588 VA: 0x7596411588
	private Void <Show>b__29_1(Single val) { }
	// RVA: 0x3df95a4 VA: 0x75964115a4
	private Void <Show>b__29_2() { }
	// RVA: 0x3df95ac VA: 0x75964115ac
	private Void <Hide>b__30_1(Single val) { }
	// RVA: 0x3df95c8 VA: 0x75964115c8
	private Void <Hide>b__30_2() { }
	// RVA: 0x3df95f0 VA: 0x75964115f0
	private Void <OnFetchRoomProductClueButtonPressed>b__36_0(Int32 result) { }
}
```