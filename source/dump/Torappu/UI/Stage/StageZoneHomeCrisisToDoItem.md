# StageZoneHomeCrisisToDoItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textTitle`

- `Text _textStageName`

- `Sprite _trainingSprite`

- `ZoneHomeToDoCrisisV2Model m_viewModel`


## Methods

- `Void _UpdateTrainingInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeCrisisToDoItem : StageZoneHomeToDoItemPlugin
{
	private Text _textTitle; // 0x28
	private Text _textStageName; // 0x30
	private Sprite _trainingSprite; // 0x38
	private ZoneHomeToDoCrisisV2Model m_viewModel; // 0x40
	private static DelegateBridge __Hotfix0_LoadMainSprite; // 0x0
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x8
	private static DelegateBridge __Hotfix0__UpdateTrainingInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f0fd7c VA: 0x7595527d7c
	protected override Sprite LoadMainSprite() { }
	// RVA: 0x2f0fecc VA: 0x7595527ecc
	protected override Void OnDataUpdated() { }
	// RVA: 0x2f0ffe8 VA: 0x7595527fe8
	private Void _UpdateTrainingInfo() { }
	// RVA: 0x2f100d0 VA: 0x75955280d0
	public Void .ctor() { }
}
```