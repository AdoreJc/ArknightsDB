# FireworkCraftStageBtnItem

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `Text _stageCode`

- `Text _stageName`

- `GameObject _panelSelect`

- `GameObject _specialStagePanel`

- `UIStateFinder m_stateFinder`

- `String m_cachedStageId`


## Methods

- `Void Render(CraftStageInfoModel, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftStageBtnItem : MonoBehaviour, IHotfixable
{
	private Text _stageCode; // 0x18
	private Text _stageName; // 0x20
	private GameObject[] _rankIcons; // 0x28
	private GameObject _panelSelect; // 0x30
	private GameObject _specialStagePanel; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private String m_cachedStageId; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2905bc0 VA: 0x7594f1dbc0
	public Void Render(CraftStageInfoModel model, String selectedStageId) { }
	// RVA: 0x2905d58 VA: 0x7594f1dd58
	public Void OnClick() { }
	// RVA: 0x2905e48 VA: 0x7594f1de48
	public Void .ctor() { }
}
```