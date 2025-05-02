# Act1VAutoChessEntryMainStartGameView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _hotspotObj`

- `GameObject _availPanel`

- `GameObject _countDownPanel`

- `GameObject _inGamePanel`

- `GameObject _actClosePanel`

- `GameObject _inGameRoundStatusPanel`

- `GameObject _inGameChoosingPanel`

- `GameObject _settleGamePanel`

- `Text _inGameRoundNumText`

- `Text _countDownTimeText`

- `Act1VAutoChessEntryMainViewModel m_cachedViewModel`

- `CountDownTask m_countDownTask`


## Methods

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryMainStartGameView : Act1VAutoChessEntryMainSubFrontViewComponent
{
	private GameObject _hotspotObj; // 0x38
	private GameObject _availPanel; // 0x40
	private GameObject _countDownPanel; // 0x48
	private GameObject _inGamePanel; // 0x50
	private GameObject _actClosePanel; // 0x58
	private GameObject _inGameRoundStatusPanel; // 0x60
	private GameObject _inGameChoosingPanel; // 0x68
	private GameObject _settleGamePanel; // 0x70
	private Text _inGameRoundNumText; // 0x78
	private Text _countDownTimeText; // 0x80
	private Act1VAutoChessEntryMainViewModel m_cachedViewModel; // 0x88
	private CountDownTask m_countDownTask; // 0x90
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3340e3c VA: 0x7595958e3c
	public override Void OnRender(Act1VAutoChessEntryMainViewModel viewModel) { }
	// RVA: 0x3341244 VA: 0x7595959244
	private Void Update() { }
	// RVA: 0x33412c0 VA: 0x75959592c0
	public Void .ctor() { }
}
```