# EmptyWavePlugin

**Namespace:** ` `


## Properties

- `Boolean hasWaveBeforeBattle`

- `Boolean hasWaveAfterBattle`


## Methods

- `Boolean get_hasWaveBeforeBattle()`

- `Boolean get_hasWaveAfterBattle()`

- `IEnumerator WaveBeforeBattle()`

- `IEnumerator WaveAfterBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class EmptyWavePlugin : IHotfixable, IWavePlugin
{
	private static DelegateBridge __Hotfix0_get_hasWaveBeforeBattle; // 0x0
	private static DelegateBridge __Hotfix0_get_hasWaveAfterBattle; // 0x8
	private static DelegateBridge __Hotfix0_WaveBeforeBattle; // 0x10
	private static DelegateBridge __Hotfix0_WaveAfterBattle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hasWaveBeforeBattle { get; }
	public Boolean hasWaveAfterBattle { get; }

	// RVA: 0x33e7564 VA: 0x75959ff564
	public Boolean get_hasWaveBeforeBattle() { }
	// RVA: 0x33e75cc VA: 0x75959ff5cc
	public Boolean get_hasWaveAfterBattle() { }
	// RVA: 0x33e7630 VA: 0x75959ff630
	public IEnumerator WaveBeforeBattle() { }
	// RVA: 0x33e76f4 VA: 0x75959ff6f4
	public IEnumerator WaveAfterBattle() { }
	// RVA: 0x33e7400 VA: 0x75959ff400
	public Void .ctor() { }
}
```