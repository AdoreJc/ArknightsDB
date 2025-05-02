# RL02BGMModuleWithSan

**Namespace:** `Torappu.UI.Roguelike.RL02`


## Fields

- `LowpassEffect m_musicEffect`


## Methods

- `String _GetBgmSignalWithLowSanByZoneId(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL02
public class RL02BGMModuleWithSan : RoguelikeBGMModule
{
	private LowpassEffect m_musicEffect; // 0x38
	private static DelegateBridge __Hotfix0_OnTriggerSignal; // 0x0
	private static DelegateBridge __Hotfix0__GetBgmSignalWithLowSanByZoneId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b605d4 VA: 0x75951785d4
	protected override Void OnTriggerSignal() { }
	// RVA: 0x2b60920 VA: 0x7595178920
	private String _GetBgmSignalWithLowSanByZoneId(String topicId, String zoneId) { }
	// RVA: 0x2b60a8c VA: 0x7595178a8c
	public Void .ctor() { }
}
```