# AudioMessagePlayer

**Namespace:** `Torappu.Audio`


## Methods

- `Void AudioUISignal(String)`

- `Void AudioSystemSignal(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioMessagePlayer : MonoBehaviour, IHotfixable
{
	private static DelegateBridge __Hotfix0_AudioUISignal; // 0x0
	private static DelegateBridge __Hotfix0_AudioSystemSignal; // 0x8
	private static DelegateBridge __Hotfix0__TryParseCombinedSignals; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3eb7258 VA: 0x75964cf258
	public Void AudioUISignal(String combinedSignals) { }
	// RVA: 0x3eb748c VA: 0x75964cf48c
	public Void AudioSystemSignal(String combinedSignals) { }
	// RVA: 0x3eb7328 VA: 0x75964cf328
	private static Boolean _TryParseCombinedSignals(String combinedSignal, out String signal, out String subsignal) { }
	// RVA: 0x3eb755c VA: 0x75964cf55c
	public Void .ctor() { }
}
```