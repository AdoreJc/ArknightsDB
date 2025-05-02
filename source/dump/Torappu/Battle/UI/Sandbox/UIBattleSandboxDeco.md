# UIBattleSandboxDeco

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Image _decoImg`

- `Transform _root`


## Properties

- `SandboxV2Data dataTable`


## Methods

- `SandboxV2Data get_dataTable()`

- `Void <>xLuaBaseProxy_OnUpdate(Card)`

- `GameObject <>xLuaBaseProxy_GetPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxDeco : UICardPlugin, IHotfixable
{
	private Image _decoImg; // 0x18
	private Transform _root; // 0x20
	private List`1 _trapLevelHint; // 0x28
	private static DelegateBridge __Hotfix0_get_dataTable; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public SandboxV2Data dataTable { get; }

	// RVA: 0x20c182c VA: 0x75946d982c
	public SandboxV2Data get_dataTable() { }
	// RVA: 0x20c18c4 VA: 0x75946d98c4
	public override Void OnUpdate(Card card) { }
	// RVA: 0x20c1a44 VA: 0x75946d9a44
	public override GameObject GetPrefab() { }
	// RVA: 0x20c1ab0 VA: 0x75946d9ab0
	public Void .ctor() { }
	// RVA: 0x20c1b74 VA: 0x75946d9b74
	private Void <>xLuaBaseProxy_OnUpdate(Card P0) { }
	// RVA: 0x20c1b7c VA: 0x75946d9b7c
	private GameObject <>xLuaBaseProxy_GetPrefab() { }
}
```