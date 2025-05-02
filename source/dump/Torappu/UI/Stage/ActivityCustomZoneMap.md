# ActivityCustomZoneMap

**Namespace:** `Torappu.UI.Stage`


## Methods

- `Void Render(ActivityCustomZoneMapViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneMap : MonoBehaviour, IActivityCustomZoneMap, IHotfixable
{
	private ActivityCustomZoneMapBasePlugin[] _plugins; // 0x18
	private ActivityCustomZoneStageButton[] _stageButtons; // 0x20
	private static DelegateBridge __Hotfix0_get_stageButtons; // 0x0
	private static DelegateBridge __Hotfix0_get_plugins; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public ActivityCustomZoneStageButton[] stageButtons { get; }
	public ActivityCustomZoneMapBasePlugin[] plugins { get; }

	// RVA: 0x2f801ec VA: 0x75955981ec
	public ActivityCustomZoneStageButton[] get_stageButtons() { }
	// RVA: 0x2f80254 VA: 0x7595598254
	public ActivityCustomZoneMapBasePlugin[] get_plugins() { }
	// RVA: 0x2f802bc VA: 0x75955982bc
	public Void Render(ActivityCustomZoneMapViewModel model, Boolean isFastMode) { }
	// RVA: 0x2f806c8 VA: 0x75955986c8
	public Void .ctor() { }
}
```