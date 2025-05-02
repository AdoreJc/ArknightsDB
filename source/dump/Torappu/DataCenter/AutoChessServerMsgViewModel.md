# AutoChessServerMsgViewModel

**Namespace:** `Torappu.DataCenter`


## Properties

- `CommonResponseViewModel talentResponse`

- `RoundBattleFinishResponseViewModel finishResponse`

- `CommonResponseViewModel startResponse`

- `CommonResponseViewModel refreshResponse`

- `CommonResponseViewModel frozResponse`

- `CommonResponseViewModel upgradeResponse`


## Methods

- `CommonResponseViewModel get_talentResponse()`

- `RoundBattleFinishResponseViewModel get_finishResponse()`

- `CommonResponseViewModel get_startResponse()`

- `CommonResponseViewModel get_refreshResponse()`

- `CommonResponseViewModel get_frozResponse()`

- `CommonResponseViewModel get_upgradeResponse()`

- `Void LoadData(AutoChessServiceMsg, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataCenter
public class AutoChessServerMsgViewModel : AutoChessViewModelBase
{
	private Dictionary`2 m_models; // 0x18
	private static DelegateBridge __Hotfix0_get_talentResponse; // 0x0
	private static DelegateBridge __Hotfix0_get_finishResponse; // 0x8
	private static DelegateBridge __Hotfix0_get_startResponse; // 0x10
	private static DelegateBridge __Hotfix0_get_refreshResponse; // 0x18
	private static DelegateBridge __Hotfix0_get_frozResponse; // 0x20
	private static DelegateBridge __Hotfix0_get_upgradeResponse; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public CommonResponseViewModel talentResponse { get; }
	public RoundBattleFinishResponseViewModel finishResponse { get; }
	public CommonResponseViewModel startResponse { get; }
	public CommonResponseViewModel refreshResponse { get; }
	public CommonResponseViewModel frozResponse { get; }
	public CommonResponseViewModel upgradeResponse { get; }

	// RVA: 0x3e3bed4 VA: 0x7596453ed4
	public CommonResponseViewModel get_talentResponse() { }
	// RVA: 0x3e3bfb0 VA: 0x7596453fb0
	public RoundBattleFinishResponseViewModel get_finishResponse() { }
	// RVA: 0x3e3c08c VA: 0x759645408c
	public CommonResponseViewModel get_startResponse() { }
	// RVA: 0x3e3c168 VA: 0x7596454168
	public CommonResponseViewModel get_refreshResponse() { }
	// RVA: 0x3e3c244 VA: 0x7596454244
	public CommonResponseViewModel get_frozResponse() { }
	// RVA: 0x3e3c320 VA: 0x7596454320
	public CommonResponseViewModel get_upgradeResponse() { }
	// RVA: 0x3e3c3fc VA: 0x75964543fc
	public Void LoadData(AutoChessServiceMsg msg, ValueBundle data) { }
	// RVA: 0x3e3c560 VA: 0x7596454560
	public Void .ctor() { }
}
```