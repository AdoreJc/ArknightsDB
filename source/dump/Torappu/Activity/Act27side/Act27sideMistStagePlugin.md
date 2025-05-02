# Act27sideMistStagePlugin

**Namespace:** `Torappu.Activity.Act27side`


## Fields

- `Text _mistCountText`

- `Text _mistTargetText`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act27side
public class Act27sideMistStagePlugin : SimpleActivityStageButtonOnMapPlugin, IHotfixable
{
	private const String MIST_TARGET_FORMAT; // 0x0
	private Text _mistCountText; // 0x18
	private Text _mistTargetText; // 0x20
	private static DelegateBridge __Hotfix0_RenderStage; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x326a824 VA: 0x7595882824
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x326aa5c VA: 0x7595882a5c
	public Void .ctor() { }
}
```