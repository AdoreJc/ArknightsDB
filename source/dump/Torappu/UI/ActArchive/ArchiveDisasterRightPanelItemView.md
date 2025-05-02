# ArchiveDisasterRightPanelItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TwoStateToggle _titleBgToggle`

- `Text _levelName`

- `Text _effect`


## Methods

- `Void Render(DisasterItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveDisasterRightPanelItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _titleBgToggle; // 0x18
	private Text _levelName; // 0x20
	private GameObject[] _levelIcons; // 0x28
	private Text _effect; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30491c4 VA: 0x75956611c4
	public Void Render(DisasterItemModel itemModel) { }
	// RVA: 0x304bbf0 VA: 0x7595663bf0
	public Void .ctor() { }
}
```