# DialogExecutorBase

**Namespace:** `Torappu.Battle.Dialog`


## Properties

- `DialogController controller`

- `DirectAssetLoader assetLoader`


## Methods

- `DialogController get_controller()`

- `DirectAssetLoader get_assetLoader()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Dialog
public class DialogExecutorBase : MonoBehaviour, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_get_type; // 0x8
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x10
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_StartSignal; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected DialogController controller { get; }
	public virtual BattleDialogType type { get; }
	protected DirectAssetLoader assetLoader { get; }

	// RVA: 0x1d2063c VA: 0x759433863c
	protected DialogController get_controller() { }
	// RVA: 0x1d206c8 VA: 0x75943386c8
	public virtual BattleDialogType get_type() { }
	// RVA: 0x1d20730 VA: 0x7594338730
	protected DirectAssetLoader get_assetLoader() { }
	// RVA: 0x1d207c8 VA: 0x75943387c8
	public virtual Dictionary`2 GetExecutors() { }
	// RVA: 0x1d208d8 VA: 0x75943388d8
	public virtual Void Init() { }
	// RVA: 0x1d2093c VA: 0x759433893c
	public virtual Void StartSignal(BattleDialogParam param) { }
	// RVA: 0x1d209b4 VA: 0x75943389b4
	public Void .ctor() { }
}
```