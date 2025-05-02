# SandboxV2DungeonMiscLogisticsEffectItemViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `ProfessionCategory profession`

- `Int32 sortId`

- `String baseDesc`

- `Int32 charBeanCount`


## Properties

- `String desc`


## Methods

- `String get_desc()`

- `Int32 CompareTo(SandboxV2DungeonMiscLogisticsEffectItemViewModel)`

- `Void LoadData(SandboxV2LogisticsData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMiscLogisticsEffectItemViewModel : IComparable`1, IHotfixable
{
	public ProfessionCategory profession; // 0x10
	public Int32 sortId; // 0x14
	public String baseDesc; // 0x18
	public String[] levelParams; // 0x20
	public Int32 charBeanCount; // 0x28
	private static DelegateBridge __Hotfix0_get_desc; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String desc { get; }

	// RVA: 0x25b296c VA: 0x7594bca96c
	public String get_desc() { }
	// RVA: 0x25b2ad8 VA: 0x7594bcaad8
	public Int32 CompareTo(SandboxV2DungeonMiscLogisticsEffectItemViewModel other) { }
	// RVA: 0x25b2b64 VA: 0x7594bcab64
	public Void LoadData(SandboxV2LogisticsData logisticsData) { }
	// RVA: 0x25b2c10 VA: 0x7594bcac10
	public Void .ctor() { }
}
```