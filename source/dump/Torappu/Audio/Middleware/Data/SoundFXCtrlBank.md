# SoundFXCtrlBank

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `Bank m_targetBank`

- `String targetBank`

- `Boolean ctrlStop`

- `Single ctrlStopFadetime`


## Methods

- `Boolean _InitTargetBank()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class SoundFXCtrlBank : Bank
{
	private Bank m_targetBank; // 0x30
	public String targetBank; // 0x38
	public Boolean ctrlStop; // 0x40
	public Single ctrlStopFadetime; // 0x44
	private static DelegateBridge __Hotfix0_Play; // 0x0
	private static DelegateBridge __Hotfix0__InitTargetBank; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3ee2808 VA: 0x75964fa808
	public override AudioAtom Play(Vector3 position) { }
	// RVA: 0x3ee28c8 VA: 0x75964fa8c8
	private Boolean _InitTargetBank() { }
	// RVA: 0x3ee2a30 VA: 0x75964faa30
	public Void .ctor() { }
}
```