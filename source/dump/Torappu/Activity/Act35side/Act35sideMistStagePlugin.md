# Act35sideMistStagePlugin

**Namespace:** `Torappu.Activity.Act35side`


## Fields

- `Text _mistCountText`

- `Text _mistTargetText`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act35side
public class Act35sideMistStagePlugin : SimpleActivityStageButtonOnMapPlugin, IHotfixable
{
	private const String MIST_TARGET_FORMAT; // 0x0
	private Text _mistCountText; // 0x18
	private Text _mistTargetText; // 0x20
	private static DelegateBridge __Hotfix0_RenderStage; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32529b0 VA: 0x759586a9b0
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x3252b78 VA: 0x759586ab78
	public Void .ctor() { }
}
```