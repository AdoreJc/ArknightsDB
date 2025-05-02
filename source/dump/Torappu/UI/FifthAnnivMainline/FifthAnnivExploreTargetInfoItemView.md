# FifthAnnivExploreTargetInfoItemView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `UIAtlasImage _iconImg`

- `Text _targetNameText`

- `Text _requireEventDescText`

- `TwoStateToggle _completeObjToggle`

- `UIAtlasObject _iconAtlas`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(Config, FifthAnnivExploreTargetInfoItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTargetInfoItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _iconImg; // 0x18
	private Text _targetNameText; // 0x20
	private Text _requireEventDescText; // 0x28
	private TwoStateToggle _completeObjToggle; // 0x30
	private List`1 _teamValueTypeComps; // 0x38
	private UIAtlasObject _iconAtlas; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x292fe14 VA: 0x7594f47e14
	private Void _InitIfNot() { }
	// RVA: 0x292fe88 VA: 0x7594f47e88
	public Void Render(Config config, FifthAnnivExploreTargetInfoItemViewModel viewModel) { }
	// RVA: 0x29302bc VA: 0x7594f482bc
	public Void .ctor() { }
}
```