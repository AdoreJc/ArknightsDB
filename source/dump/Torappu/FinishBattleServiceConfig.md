# FinishBattleServiceConfig

**Namespace:** `Torappu`


## Fields

- `String m_serviceCode`


## Properties

- `BattleController battleController`


## Methods

- `BattleController get_battleController()`

- `Void SendFinishBattleService(IFinishBattleServiceSender, Boolean)`

- `Object TouchReqService()`

- `Object TouchPostService()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class FinishBattleServiceConfig`2 : IFinishBattleServiceConfig
{
	private String m_serviceCode; // 0x0

	public virtual String overrideContinueServiceCode { get; }
	public virtual Int32 overrideMaxRetryCount { get; }
	protected BattleController battleController { get; }

	// RVA: 0x VA: 0x0
	public virtual String get_overrideContinueServiceCode() { }
	// RVA: 0x VA: 0x0
	public virtual Int32 get_overrideMaxRetryCount() { }
	// RVA: 0x VA: 0x0
	public virtual Void OnParseRequest(TRequest request) { }
	// RVA: 0x VA: 0x0
	public virtual Void SendContinueBattleService(IFinishBattleServiceSender sender, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	protected BattleController get_battleController() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(String serviceCode) { }
	// RVA: 0x VA: 0x0
	public Void SendFinishBattleService(IFinishBattleServiceSender sender, Boolean isRetry) { }
	// RVA: 0x VA: 0x0
	public Object TouchReqService() { }
	// RVA: 0x VA: 0x0
	public Object TouchPostService() { }
}
```