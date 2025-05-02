# SandboxV2TopBarFloatPanelView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonExpeditionEffectFloatPanel _expeditionFloatPanel`

- `SandboxV2DungeonEventEffectFloatPanel _eventFloatPanel`

- `SandboxV2DungeonLogisticsEffectFloatPanel _logisticsFloatPanel`

- `SandboxV2DungeonSphereFloatPanel _sphereFloatPanel`

- `SandboxV2DungeonRiftEffectFloatPanel _riftEffectFloatPanel`

- `Boolean m_isInited`

- `SandboxV2DungeonViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _InitIfNot()`

- `Void OnExpeditionClick()`

- `Void OnEventClick()`

- `Void OnSphereClick()`

- `Void OnLogisticsClick()`

- `Void OnRiftEffectsClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2TopBarFloatPanelView : MonoBehaviour, IHotfixable
{
	private SandboxV2DungeonExpeditionEffectFloatPanel _expeditionFloatPanel; // 0x18
	private SandboxV2DungeonEventEffectFloatPanel _eventFloatPanel; // 0x20
	private SandboxV2DungeonLogisticsEffectFloatPanel _logisticsFloatPanel; // 0x28
	private SandboxV2DungeonSphereFloatPanel _sphereFloatPanel; // 0x30
	private SandboxV2DungeonRiftEffectFloatPanel _riftEffectFloatPanel; // 0x38
	private Boolean m_isInited; // 0x40
	private SandboxV2DungeonViewModel m_cachedViewModel; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnExpeditionClick; // 0x10
	private static DelegateBridge __Hotfix0_OnEventClick; // 0x18
	private static DelegateBridge __Hotfix0_OnSphereClick; // 0x20
	private static DelegateBridge __Hotfix0_OnLogisticsClick; // 0x28
	private static DelegateBridge __Hotfix0_OnRiftEffectsClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x254c97c VA: 0x7594b6497c
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x254ca90 VA: 0x7594b64a90
	private Void _InitIfNot() { }
	// RVA: 0x254cb74 VA: 0x7594b64b74
	public Void OnExpeditionClick() { }
	// RVA: 0x254cc48 VA: 0x7594b64c48
	public Void OnEventClick() { }
	// RVA: 0x254cd1c VA: 0x7594b64d1c
	public Void OnSphereClick() { }
	// RVA: 0x254cdbc VA: 0x7594b64dbc
	public Void OnLogisticsClick() { }
	// RVA: 0x254ce5c VA: 0x7594b64e5c
	public Void OnRiftEffectsClick() { }
	// RVA: 0x254cefc VA: 0x7594b64efc
	public Void .ctor() { }
}
```