# SandboxV2BuildingInfoView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _nodeName`

- `Text _buildingName`

- `GameObject _damagedIconGameObject`

- `GameObject _upgradeIconGameObject`

- `Text _playerHoldCount`

- `GameObject _bgImageGameObject`

- `GameObject _pnlTitle`


## Methods

- `Void Render(SandboxV2DungeonBuildingTrapInfo, Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BuildingInfoView : MonoBehaviour, IHotfixable
{
	private const String BUILDING_COUNT_FORMAT; // 0x0
	private Text _nodeName; // 0x18
	private Text _buildingName; // 0x20
	private GameObject _damagedIconGameObject; // 0x28
	private GameObject _upgradeIconGameObject; // 0x30
	private Text _playerHoldCount; // 0x38
	private GameObject _bgImageGameObject; // 0x40
	private GameObject _pnlTitle; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x24fd3c0 VA: 0x7594b153c0
	public Void Render(SandboxV2DungeonBuildingTrapInfo buildingTrapInfo, Int32 index, String nodeTypeName) { }
	// RVA: 0x24fd5f4 VA: 0x7594b155f4
	public Void .ctor() { }
}
```