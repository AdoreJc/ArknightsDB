# TorappuAudioMiddleware

**Namespace:** `Torappu.Audio.Middleware`


## Methods

- `Void _ReloadBanksImpl()`

- `Boolean TryGetBankList(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware
public class TorappuAudioMiddleware : AudioMiddleware
{
	private Dictionary`2 m_banks; // 0x10
	private Dictionary`2 m_bankAlias; // 0x18
	private Bank[] m_bankList; // 0x20


	// RVA: 0x3edf20c VA: 0x75964f720c
	public override Void Init() { }
	// RVA: 0x3edf2c0 VA: 0x75964f72c0
	public override Void ReloadBanks() { }
	// RVA: 0x3edf364 VA: 0x75964f7364
	private Void _ReloadBanksImpl() { }
	// RVA: 0x3edfacc VA: 0x75964f7acc
	public override Boolean PlayEvent(String eventName, Vector3 position) { }
	// RVA: 0x3edfc90 VA: 0x75964f7c90
	public override Void PlayEvent(String eventName, Vector3 position, out AudioAtom[] atoms) { }
	// RVA: 0x3edfe64 VA: 0x75964f7e64
	public override Boolean TestEvent(String eventName) { }
	// RVA: 0x3edfe80 VA: 0x75964f7e80
	public override Void PreloadEvent(String persistTag, String eventName) { }
	// RVA: 0x3edff3c VA: 0x75964f7f3c
	public override Void UnloadPreloadedAssets(String persistTag) { }
	// RVA: 0x3edff48 VA: 0x75964f7f48
	public override Void StopPreloadedEvents(String persistTag) { }
	// RVA: 0x3edff54 VA: 0x75964f7f54
	public override Void SetListenerPosition(Vector3 worldPosition, Quaternion worldRotation) { }
	// RVA: 0x3edff5c VA: 0x75964f7f5c
	public override Void Update(Single deltaTime) { }
	// RVA: 0x3edffd0 VA: 0x75964f7fd0
	public override Void StopAll(Single fadeTime, Boolean exceptMusic) { }
	// RVA: 0x3edfbc4 VA: 0x75964f7bc4
	public Boolean TryGetBankList(String nameOrAlias, out List`1 bankList) { }
	// RVA: 0x3ee0194 VA: 0x75964f8194
	public Void .ctor() { }
}
```