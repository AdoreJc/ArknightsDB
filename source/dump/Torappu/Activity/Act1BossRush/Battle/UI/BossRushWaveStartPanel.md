# BossRushWaveStartPanel

**Namespace:** `Torappu.Activity.Act1BossRush.Battle.UI`


## Fields

- `UIPerform uiPerform`


## Methods

- `Void OnUpdateWaveInfo(Int32, Int32)`

- `Void _UpdateWaveImages(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush.Battle.UI
public class BossRushWaveStartPanel : MonoBehaviour, IHotfixable
{
	private Text[] _waveNumTexts; // 0x18
	private Text[] _waveTexts; // 0x20
	private Text[] _finalWaveTexts; // 0x28
	public UIPerform uiPerform; // 0x30
	private static DelegateBridge __Hotfix0_OnUpdateWaveInfo; // 0x0
	private static DelegateBridge __Hotfix0__UpdateWaveImages; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3198b2c VA: 0x75957b0b2c
	public Void OnUpdateWaveInfo(Int32 currWaveCnt, Int32 maxWaveCnt) { }
	// RVA: 0x3199bc8 VA: 0x75957b1bc8
	private Void _UpdateWaveImages(Boolean isLastWave) { }
	// RVA: 0x3199ccc VA: 0x75957b1ccc
	public Void .ctor() { }
}
```