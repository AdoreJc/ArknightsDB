# SandboxV2DungeonMaterialViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String topicId`

- `UIItemViewModel goldItemViewModel`

- `UIItemViewModel dimensionCoinItemViewModel`


## Methods

- `UIItemViewModel _GetMaterialItemViewModel(String)`

- `Void LoadData(String, SandboxV2Data, PlayerSandboxV2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMaterialViewModel : IHotfixable
{
	public String topicId; // 0x10
	public UIItemViewModel goldItemViewModel; // 0x18
	public UIItemViewModel dimensionCoinItemViewModel; // 0x20
	public ListDict`2 materials; // 0x28
	private const String IGNOR_MAT_SUBTYPE; // 0x0
	private static DelegateBridge __Hotfix0__GetMaterialItemViewModel; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x25b1a10 VA: 0x7594bc9a10
	private UIItemViewModel _GetMaterialItemViewModel(String itemId) { }
	// RVA: 0x25b1b10 VA: 0x7594bc9b10
	public Void LoadData(String topicId, SandboxV2Data topicDetailData, PlayerSandboxV2 playerTopicData) { }
	// RVA: 0x25b2034 VA: 0x7594bca034
	public Void .ctor() { }
}
```