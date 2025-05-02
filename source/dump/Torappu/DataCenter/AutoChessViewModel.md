# AutoChessViewModel

**Namespace:** `Torappu.DataCenter`


## Fields

- `AutoChessServerMsgViewModel serverMsg`

- `GameStatus status`


## Methods

- `Void LoadData(AutoChessGame, ActivityAutoChessVerify1Data)`

- `Void LoadBattle(AutoChessGame)`

- `Void LoadServerMsg(AutoChessServiceMsg, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataCenter
public class AutoChessViewModel : AutoChessViewModelBase
{
	public AutoChessServerMsgViewModel serverMsg; // 0x18
	public GameStatus status; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_LoadBattle; // 0x8
	private static DelegateBridge __Hotfix0_LoadServerMsg; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e3cadc VA: 0x7596454adc
	public Void LoadData(AutoChessGame game, ActivityAutoChessVerify1Data gamedata) { }
	// RVA: 0x3e3cb7c VA: 0x7596454b7c
	public Void LoadBattle(AutoChessGame game) { }
	// RVA: 0x3e3cc10 VA: 0x7596454c10
	public Void LoadServerMsg(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x3e3ccc8 VA: 0x7596454cc8
	public Void .ctor() { }
}
```