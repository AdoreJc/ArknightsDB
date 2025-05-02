# ActivityOnBattleViewModel

**Namespace:** `Torappu.UI.Home`


## Methods

- `Void LoadData()`

- `Void _LoadActivityModels()`

- `Void _LoadCrisisV2Models()`

- `Void _LoadRoguelikeModels()`

- `Void _LoadSandboxPermModels()`

- `Void _LoadMainlineModels()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class ActivityOnBattleViewModel : IHotfixable
{
	private const Int32 MAX_DISPLAY_COUNT; // 0x0
	public List`1 tabModels; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadActivityModels; // 0x8
	private static DelegateBridge __Hotfix0__LoadCrisisV2Models; // 0x10
	private static DelegateBridge __Hotfix0__LoadRoguelikeModels; // 0x18
	private static DelegateBridge __Hotfix0__LoadSandboxPermModels; // 0x20
	private static DelegateBridge __Hotfix0__LoadMainlineModels; // 0x28
	private static DelegateBridge __Hotfix0__ModelComparer; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2809d18 VA: 0x7594e21d18
	public Void LoadData() { }
	// RVA: 0x2809fe4 VA: 0x7594e21fe4
	private Void _LoadActivityModels() { }
	// RVA: 0x280ac2c VA: 0x7594e22c2c
	private Void _LoadCrisisV2Models() { }
	// RVA: 0x280a404 VA: 0x7594e22404
	private Void _LoadRoguelikeModels() { }
	// RVA: 0x280ae30 VA: 0x7594e22e30
	private Void _LoadSandboxPermModels() { }
	// RVA: 0x280a778 VA: 0x7594e22778
	private Void _LoadMainlineModels() { }
	// RVA: 0x280b238 VA: 0x7594e23238
	private static Int32 _ModelComparer(Options lhs, Options rhs) { }
	// RVA: 0x280b344 VA: 0x7594e23344
	public Void .ctor() { }
}
```