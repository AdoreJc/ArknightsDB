# Act9D0MistStagePlugin

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `GameObject _panelMist`

- `Text _mistCountText`

- `Text _mistTargetText`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MistStagePlugin : SimpleActivityStageButtonOnMapPlugin, IHotfixable
{
	private const String MIST_TARGET_FORMAT; // 0x0
	private GameObject _panelMist; // 0x18
	private Text _mistCountText; // 0x20
	private Text _mistTargetText; // 0x28
	private static DelegateBridge __Hotfix0_RenderStage; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x319a7c0 VA: 0x75957b27c0
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x319aa94 VA: 0x75957b2a94
	public Void .ctor() { }
}
```