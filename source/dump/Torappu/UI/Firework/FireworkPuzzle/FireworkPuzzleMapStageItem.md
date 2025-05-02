# FireworkPuzzleMapStageItem

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `GameObject _panelBtnLocked`

- `GameObject _panelBtnUnlock`

- `GameObject _panelBtnComplete`

- `GameObject _panelTomorrowUnlock`

- `Text _tomorrowUnlockDesc`

- `UIStateFinder m_stateFinder`

- `String m_cachedPuzzleId`


## Methods

- `Void Render(FireworkPuzzleItemModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleMapStageItem : MonoBehaviour, IHotfixable
{
	private GameObject _panelBtnLocked; // 0x18
	private GameObject _panelBtnUnlock; // 0x20
	private GameObject _panelBtnComplete; // 0x28
	private GameObject _panelTomorrowUnlock; // 0x30
	private Text _tomorrowUnlockDesc; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private String m_cachedPuzzleId; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28f6eac VA: 0x7594f0eeac
	public Void Render(FireworkPuzzleItemModel model) { }
	// RVA: 0x28f6fd8 VA: 0x7594f0efd8
	public Void OnClick() { }
	// RVA: 0x28f70c8 VA: 0x7594f0f0c8
	public Void .ctor() { }
}
```