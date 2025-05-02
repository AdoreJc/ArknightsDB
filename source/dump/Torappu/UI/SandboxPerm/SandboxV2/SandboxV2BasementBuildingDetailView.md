# SandboxV2BasementBuildingDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _buildingDetailHolder`

- `SandboxV2BuildingDetailPanel _prefabBuildingDetail`

- `Color _detailPanelBkgColor`

- `Boolean m_isInited`

- `SandboxV2BuildingDetailPanel m_buildingDetail`


## Methods

- `Void _InitIfNot()`

- `Void Render(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementBuildingDetailView : MonoBehaviour, IHotfixable
{
	private RectTransform _buildingDetailHolder; // 0x18
	private SandboxV2BuildingDetailPanel _prefabBuildingDetail; // 0x20
	private Color _detailPanelBkgColor; // 0x28
	private Boolean m_isInited; // 0x38
	private SandboxV2BuildingDetailPanel m_buildingDetail; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x250d9b4 VA: 0x7594b259b4
	private Void _InitIfNot() { }
	// RVA: 0x250dad8 VA: 0x7594b25ad8
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x250dbd4 VA: 0x7594b25bd4
	public Void .ctor() { }
}
```