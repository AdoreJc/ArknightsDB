# CharacterAudioHooker

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean TryHookAudio(String, String, out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CharacterAudioHooker : MonoBehaviour
{
	private ReplacePair[] _replaceAudioPairs; // 0x18

	public IEnumerable`1 replaceAudioPairs { get; }

	// RVA: 0x1b743bc VA: 0x759418c3bc
	public IEnumerable`1 get_replaceAudioPairs() { }
	// RVA: 0x1b743c4 VA: 0x759418c3c4
	public Boolean TryHookAudio(String signal, String subSingal, out String newSignal, out String newSubSignal) { }
	// RVA: 0x1b74514 VA: 0x759418c514
	public Void .ctor() { }
}
```