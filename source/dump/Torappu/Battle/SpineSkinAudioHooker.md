# SpineSkinAudioHooker

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean TryHookAudio(String, String, String, out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SpineSkinAudioHooker : MonoBehaviour, IHotfixable
{
	private ReplacePair[] _replaceAudioPairs; // 0x18
	private static DelegateBridge __Hotfix0_get_replaceAudioPairs; // 0x0
	private static DelegateBridge __Hotfix0_TryHookAudio; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public IEnumerable`1 replaceAudioPairs { get; }

	// RVA: 0x1b748dc VA: 0x759418c8dc
	public IEnumerable`1 get_replaceAudioPairs() { }
	// RVA: 0x1b74944 VA: 0x759418c944
	public Boolean TryHookAudio(String signal, String subSingal, String skin, out String newSignal, out String newSubSignal) { }
	// RVA: 0x1b74b20 VA: 0x759418cb20
	public Void .ctor() { }
}
```