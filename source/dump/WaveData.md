# WaveData

**Namespace:** ` `


## Fields

- `Single preDelay`

- `Single postDelay`

- `Single maxTimeWaitingForNextWave`

- `String advancedWaveTag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class WaveData
{
	public Single preDelay; // 0x10
	public Single postDelay; // 0x14
	public Single maxTimeWaitingForNextWave; // 0x18
	public FragmentData[] fragments; // 0x20
	public String advancedWaveTag; // 0x28


	// RVA: 0x34a4228 VA: 0x7595abc228
	public Void .ctor() { }
}
```